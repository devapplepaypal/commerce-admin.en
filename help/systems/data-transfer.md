---
title: Data transfer
description: Learn about support for data transfer, including data validation.
---
# Data transfers

The import and export tools give you the ability to manage multiple records in a single operation. You can not only import new items, but also update, replace, and delete existing sets of products. For example, you can add new products to your inventory, update product data and advanced price data, and replace a set of existing products with new products. If you have a large catalog of products, it is much easier to export the data, edit the data in a spreadsheet, and import it back into your store.

In addition to the import and export tools, Adobe Commerce and Magento Open Source have processes like [catalog sync](https://experienceleague.adobe.com/docs/commerce-merchant-services/user-guides/data-services/catalog-sync.html) that export product data from the Commerce server to SaaS services. For features like [Product Recommendations](https://experienceleague.adobe.com/docs/commerce-merchant-services/product-recommendations/overview.html), this synch makes it possible to accurately return recommendations with correct names, pricing, and availability.

## Data validation

All data must pass validation before it can be imported into the store, to ensure that the values are consistent with the system database. Validation begins when you click **[!UICONTROL Check Data]**. During the process, all entities in the import file are verified for the following:

- **Attributes** - Column header names are verified to ensure that they match the corresponding attributes in the system database. The value of each attribute is checked to ensure that it meets the requirements of the data type (decimal, integer, varchar, text, and datetime).
- **Complex Data** - Values that originate from a defined set, such as a drop-down or multiple select input type, are verified to ensure that the values exist in the defined set.
- **Service Data** - The values in service data columns are verified to ensure that the properties or complex data values are consistent with what is already defined in the system database.
- **Required Values** - For new entities, the presence of required attribute values in the file is checked. For existing entities, there is no need to recheck the existence of required attribute values.
- **Separators** - Although the separators aren't visible when viewed in a spreadsheet, data values in a CSV file are separated by comma, and text values are enclosed in double-quotes. During the validation process, formatting for the separators and each set of quotes that enclose character strings are verified.

The results of the validation appear in the Validation Results section, and include the following information:

- The number of entities checked
- The number of invalid rows
- The number of errors found

If the data is valid, an _Import Success_ message appears.

![System message - file is valid](./assets/data-import-validation-message.png)<!-- zoom -->

If validation fails, read the description of each error, and correct the problem in the CSV file. For example, if a row contains an invalid SKU, the import process stops, and that row, and all subsequent rows are not imported. After correctly the problem, import the data again. If many errors are encountered, it might take several attempts to pass validation.

### Data validation messages

#### Validation

- `Product with specified SKU not found in rows: 1`
- `URL key for specified store already exists`
- `'7z' file extension is not supported`
- `TXT file extension is not supported`

#### Errors

- `Wrong field type. Type in the imported file %decimal%, expected type is %text%.`
- `Value is not allowed. Attribute value does not exist in the system.`
- `Field %column name% is required.Wrong value separator is used.`
- `Wrong encoding used. Supported character encoding is UTF-8 and Windows-1252.`
- `Imported file does not contain SKU field.`
- `SKU does not exist in the system.`
- `Column name %column name% is invalid. Should start with a letter. Alphanumeric.`
- `Imported file does not contain a header.`
- `%website name% website does not exist in the system.`
- `%storeview name% storeview does not exist in the system.`
- `Imported attribute %attribute name% does not exist in the system.`
- `Imported resource (image) could not be downloaded from external resource due to timeout or access permissions.`
- `Imported resource (image) does not exist in the local media storage.`
- `Product creation error displayed to the user equal to the one seen during manual product save.`
- `Advanced Price creation error displayed to the user equal to the one seen during the manual product save.`
- `Customer creation error displayed to the user equal to the one seen during the manual customer save.`