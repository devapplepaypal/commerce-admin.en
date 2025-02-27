---
title: Layout - Tabs
description: Learn about the Tabs content type, used to add a set of tabs in the [!DNL Page Builder] stage.
exl-id: e83d248d-7cf3-4ccc-a03d-ede32c7e71ae
---
# Layout - Tabs

Use the _Tabs_ content type to add a set of tabs in the [[!DNL Page Builder] stage](workspace.md#stage). When you drag the Tabs placeholder from the panel to the stage, a single default tab initially appears. You can add more tabs to create a full set. The width of the tab set is determined by the width of its parent container and padding settings.

![Set of tabs](./assets/pb-layout-tab-example.png)<!-- zoom -->

{{$include /help/_includes/page-builder-save-timeout.md}}

## Toolboxes

When you are working with the _Tabs_ content type, you add and edit individual tabs and the tabs container that holds one or more tabs. Each tab has its own toolbox that you use to design tabs on the [!DNL Page Builder] stage.

### Individual tab toolbox

![Tab toolbox](./assets/pb-layout-tab1-toolbox.png)<!-- zoom -->

|Tool|Icon|Description|
|--- |--- |--- |
|Move|![Move icon](./assets/pb-icon-move.png)<!-- width="25px" -->|This control next to the tab label is used to move the individual tab to another position in the tab set.|
|Settings|![Settings icon](./assets/pb-icon-settings.png)<!-- width="25px" -->|Opens the Edit Tabs page, where you can change the properties of the individual tab.|
|Duplicate|![Duplicate icon](./assets/pb-icon-duplicate.png)<!-- width="25px" -->|Makes a copy of the tab.|
|Remove|![Remove icon](./assets/pb-icon-remove.png)<!-- width="25px" -->|Deletes the tab from the tab set.|

{style="table-layout:auto"}

### Tabs container toolbox

![Tab container toolbox](./assets/pb-tabs-toolbox-settings.png)<!-- zoom -->

|Tool|Icon|Description|
|--- |--- |--- |
|Move|![Move icon](./assets/pb-icon-move.png)<!-- width="25px" -->|Moves the set of tabs to another position on the grid in the parent container.|
|Add|![Add icon](./assets/pb-icon-add.png)<!-- width="25px" -->|Adds a tab to the tab set.|
|(label)|[!UICONTROL Tabs]|Identifies the current container as a tab set. Hover over the top border of the container to see the toolbox.|
|Settings|![Settings icon](./assets/pb-icon-settings.png)<!-- width="25px" -->|Opens the Edit Tab page, where you can change the properties of the container.|
|Hide|![Hide icon](./assets/pb-icon-hide.png)<!-- width="25px" -->|Hides the tab container.|
|Show|![Show icon](./assets/pb-icon-show.png)<!-- width="25px" -->|Shows the hidden tab container.|
|Duplicate|![Duplicate icon](./assets/pb-icon-duplicate.png)<!-- width="25px" -->|Makes a copy of the current tab.|
|Remove|![Remove icon](./assets/pb-icon-remove.png)<!-- width="25px" -->|Deletes the current tab set from the stage.|

{style="table-layout:auto"}

## Add an individual tab

1. In the [!DNL Page Builder] panel under _[!UICONTROL Layout]_, drag the **[!UICONTROL Tabs]** placeholder directly to the stage or to a row or column on the stage.

   ![Dragging tabs to a row](./assets/pb-layout-tabs-drag-row.png)<!-- zoom -->

1. Click the **[!UICONTROL Tab 1]** label to display the individual tab toolbox and choose the _Settings_ (![Settings icon](./assets/pb-icon-settings.png)<!-- width="20px" --> ) icon.

1. Enter the **[!UICONTROL Tab Name]** that you want to use as a label.

   ![Entering the tab name](./assets/pb-layout-tab1-toolbox-settings-general-tab-name.png)<!-- zoom -->

1. If needed, enter the **[!UICONTROL Minimum Height]** for the tab.

   This value can be a number with any valid CSS unit (such as `100px`, `50%`, `50em`, `100vh`) or a calculation (such as `100vh - 237px`).

1. Choose a **[!UICONTROL Vertical Alignment]** setting to align any content containers that are added to the tab (Top, Center, or Bottom).

1. If needed, set the other options using the following sections as guidance:

   - [[!UICONTROL Background]][background]
   - [[!UICONTROL Advanced]][advanced]

1. In the upper-right corner, click **[!UICONTROL Save]** to apply the settings and return to the [!DNL Page Builder] workspace.

## Add a set of tabs

The following steps start with an individual tab and create a set of three tabs within a tabs container. If you do not already have an individual tab, follow the previous instructions to add a single tab to the stage.

1. Hover over the tabs container to display the toolbox and choose the _Add_ (![Add icon](./assets/pb-icon-add.png)) icon.

1. Click in the **[!UICONTROL Tab 2]** label to display the cursor and enter you own label for the tab.

1. Click the second tab again on the stage and choose the _Duplicate_ (![Duplicate icon](./assets/pb-icon-duplicate.png)) icon.

1. Click in the YourName **[!UICONTROL Copy]** label to display the cursor and enter you own label for the third tab.

![Matching set of tabs with toolbox](./assets/pb-layout-tabs3-toolbox-main.png)<!-- zoom -->

## Move a tab within the set

1. Click the tab that you want to move.

1. Select and drag the _Move_ (![Move icon](./assets/pb-icon-move.png)) icon, which appears just before the tab label text, to a new position within the tab set.

## Add content to a tab

You can any content type to a tab just as you can to a row. Use the following steps for adding a text content type as an example.

1. Click the tab where you want to add the content.

1. In the [!DNL Page Builder] panel, expand **[!UICONTROL Elements]** and drag a **Text** placeholder to the tab.

1. Enter or paste some text in the editor and use the editor toolbar to format it as needed.

   See [Elements - Text](text.md) for more information about working with the tex content type.

   ![Editing text content added on the tab](./assets/pb-layout-tab-text.png)<!-- zoom -->

1. In the upper-right corner, click **[!UICONTROL Save]**.

## Change individual tab settings

1. Hover over an individual tab to display the toolbox and choose the _Settings_ (![Settings icon](./assets/pb-icon-settings.png)<!-- width="20px" --> ) icon.

1. If needed, change any of the basic settings for the tab:

   - **[!UICONTROL Tab Name]** - Enter revised text for the tab label. You can also modify the label directly on the stage.

   - **[!UICONTROL Minimum Height]** - Enter as pixels if you want to override the automatic height. For example, you might set the minimum height to match the height of a background image to ensure that the full image is visible.

   - **[!UICONTROL Vertical Alignment]** - Choose the vertical position of content containers that are added to the tab.

1. Change the other settings as needed using the following sections for details.

1. When complete, click **[!UICONTROL Save]** to apply the settings and return to the [!DNL Page Builder] workspace.

### Background

- **[!UICONTROL Background Color]** - Specify the background color by choosing a swatch, clicking the color picker, or by entering a valid color name or equivalent hexadecimal value. This setting determines the background color of the row. You can also adjust the opacity of the color.

   ![No color (default)](./assets/pb-settings-background-color-no-color.png)<!-- zoom -->

   You can enter a value in three ways:

   - A predefined color name, such as `White`

   - The hexadecimal color value for the color, such as `#ffffff`

   - The rgba value for the color, with opacity percent, such as `rgba(255, 255, 255, 0.75)`

   If you want to choose a color, click the swatch to the left of the _No Color_ box.

   ![Choosing a color swatch](./assets/pb-settings-background-color-picker-swatch.png)<!-- zoom -->

   If you click the color box to open the color picker again, the box below the slider shows the current red, green, blue, and alpha values (rgba). The last number indicates the current opacity percentage as a decimal. You can use the slider to adjust the opacity, or enter the desired decimal value.

   ![Setting opacity](./assets/pb-settings-background-color.png)<!-- zoom -->

   >[!NOTE]
   >
   >[!DNL Page Builder] also supports a transparency layer, or _alpha channel_, in background images that can be used to create backgrounds with varying degrees of opacity.

- **[!UICONTROL Background Image]** - If needed, use the provided tools to choose a background image to apply to the tab:

   | Tool | Description |
   |--- |--- |
   | [!UICONTROL Upload] | Uploads an image file from your local computer to the gallery and then applies it as the background image for the tab. |
   | [!UICONTROL Select from Gallery] | Prompts you to choose an existing image from the gallery as the background image for the tab. |
   | ![Camera icon](./assets/pb-icon-camera.png)<!-- width="25px" --> |  Allows you to either drag the image to the camera tile or browse to the image in your local file system. |

   {style="table-layout:auto"}

- **[!UICONTROL Background Mobile Image]** - If needed, use the same tools to choose a different background image to be used for display on mobile devices.

- **[!UICONTROL Background Size]** - Choose how the background image is scaled in relation to the width of the tab:

   | Option | Description |
   |--- |--- |
   | `Cover` | The background image covers the full width of the tab. |
   | `Contain` | The background image is limited to the width of the tab area. |
   | `Auto` | Applies the size from the current style sheet. |

   {style="table-layout:auto"}

- **[!UICONTROL Background Position]** - Choose how the background image is anchored in relation to the tab: `Top Left` / `Top Center` / `Top Right` / `Center Left` / `Center` / `Center Right` / `Bottom Left` / `Bottom Center` / `Bottom Right`

- **[!UICONTROL Background Attachment]** - Choose the attachment type to determine how the background image moves in relation to the scrolling page:

   | Option | Description|
   | --- | --- |
   | `Scroll` | The attached background image is synchronized to move down as the page scrolls.|
   | `Fixed` |(Not available for mobile) The background image does not move as the container scrolls over the image and is fixed at the specified background position.|

   {style="table-layout:auto"}

- **[!UICONTROL Background Repeat]** - Set to `Yes` to repeat the background image to fill the available space in the tab.

### Advanced

- To control the horizontal alignment of content containers that are added to the tab, choose an **[!UICONTROL Alignment]** .

   | Option | Description|
   | --- | --- |
   | `Default` | Applies the alignment default setting that is specified in the style sheet of the current theme. |
   | `Left` | Aligns the content containers along the left border of the tab, with allowance for any padding that is specified. |
   | `Center` | Aligns the content container in the center of the tab, with allowance for any padding that is specified. |
   | `Right` | Aligns the content container along the right border of the tab, with allowance for any padding that is specified. |

   {style="table-layout:auto"}

- Set the **[!UICONTROL Border]** style that is applied to all four sides of the tab container:

   | Option | Description|
   | --- | --- |
   | `Default` | Applies the default border style that is specified by the associated style sheet. |
   | `None` | Does not provide any visible indication of the container borders. |
   | `Dotted` | The container border appears as a dotted line. |
   | `Dashed` | The container border appears as a dashed line. |
   | `Solid` | The container border appears as a solid line. |
   | `Double` | The container border appears as a double line. |
   | `Groove` | The container border appears as a grooved line. |
   | `Ridge` | The container border appears as a ridged line. |
   | `Inset` | The container border appears as an inset line. |
   | `Outset` | The container border appears as an outset line. |

   {style="table-layout:auto"}

- If you set a border style other than `None`, complete the border display options:

   ![Border Color](./assets/pb-settings-border-color.png)<!-- zoom -->

   | Option | Description |
   | ------ |------------ |
   | [!UICONTROL Border Color] | Specify the color by choosing a swatch, clicking the color picker, or by entering a valid color name or equivalent hexadecimal value. |
   | [!UICONTROL Border Width] | Enter the number of pixels for the border line width. |
   | [!UICONTROL Border Radius] | Enter the number of pixels to define the size of the radius that is used to round each corner of the border. |

   {style="table-layout:auto"}

   The row in the following example has a border radius of 15.

   ![Row with border radius of 15](./assets/pb-settings-border-radius-15.png)<!-- zoom -->

- (Optional) Specify the names of **[!UICONTROL CSS classes]** from the current style sheet to apply to the column container.

   Separate multiple class names with a space.

- Enter values, in pixels, for the **[!UICONTROL Margins and Padding]** to specify the outer margins and inner padding of the column.

   Enter each corresponding value in the tab container diagram.

   | Container area | Description|
   | -------------- | ---------- |
   | [!UICONTROL Margins] | The amount of blank space that is applied to the outside edge of all sides of the container. Options: `Top` / `Right` / `Bottom` / `Left` |
   | [!UICONTROL Padding] | The amount of blank space that is applied to the inside edge of all sides of the container. Options: `Top` / `Right` / `Bottom` / `Left` |

   {style="table-layout:auto"}

## Change tab set settings

1. Hover over the top border of the tab set container to display the toolbox and choose the _Settings_ (![Settings icon](./assets/pb-icon-settings.png)<!-- width="20px" --> ) icon.

1. If needed, change the **[!UICONTROL Default Active Tab]**.

   Choose the tab in the set that you want to be active when the page is loaded.

1. Enter the **[!UICONTROL Minimum Height]**, in pixels, if you want to override the automatic height for the tab set.

1. To position the navigation tabs along the top of the tab set, choose the **[!UICONTROL Tab Navigation Alignment]** (`Left`, `Center`, or `Right`).

   ![Right-aligned navigation tabs](./assets/pb-layout-tabs-navigation-alignment-right.png)<!-- zoom -->

1. Set the Advanced options for the tab set:

   - To control the positioning of the tab set within the parent container, choose an **[!UICONTROL Alignment]**:

      | Option | Description|
      | ------ | ---------- |
      | `Default` | Applies the alignment default setting that is specified in the style sheet of the current theme. |
      | `Left` | Aligns the tab set along the left border of the parent container, with allowance for any padding that is specified. |
      | `Center` | Aligns the tab set in the center of the parent container, with allowance for any padding that is specified. |
      | `Right` | Aligns the tab set along the right border of the parent container, with allowance for any padding that is specified. |

      {style="table-layout:auto"}

   - Set the **[!UICONTROL Border]** style applied to all four sides of the tabs container:

      | Option | Description|
      | ------ | ---------- |
      | `Default` | Applies the default border style that is specified by the associated style sheet. |
      | `None` | Does not provide any visible indication of the container borders. |
      | `Dotted` | The container border appears as a dotted line. |
      | `Dashed` | The container border appears as a dashed line. |
      | `Solid` | The container border appears as a solid line. |
      | `Double` | The container border appears as a double line. |
      | `Groove` | The container border appears as a grooved line. |
      | `Ridge` | The container border appears as a ridged line. |
      | `Inset` | The container border appears as an inset line. |
      | `Outset` | The container border appears as an outset line. |

      {style="table-layout:auto"}

   - If you set a border style other than `None`, complete the border display options:

      | Option | Description |
      | ------ |------------ |
      | [!UICONTROL Border Color] | Specify the color by choosing a swatch, clicking the color picker, or by entering a valid color name or equivalent hexadecimal value. |
      | [!UICONTROL Border Width] | Enter the number of pixels for the border line width. |
      | [!UICONTROL Border Radius] | Enter the number of pixels to define the size of the radius that is used to round each corner of the border. |

      {style="table-layout:auto"}

   - (Optional) Specify the names of **[!UICONTROL CSS classes]** from the current style sheet to apply to the tabs container.

      Separate multiple class names with a space.

   - Enter values, in pixels, for the **[!UICONTROL Margins and Padding]** to determine the outer margins and inner padding of the tabs container.

      Enter the corresponding values in the tabs container diagram.

      | Container area | Description |
      | -------------- | ---------- |
      | [!UICONTROL Margins] |The amount of blank space that is applied to the outside edge of all sides of the container. Options: `Top` / `Right` / `Bottom` / `Left` |
      | [!UICONTROL Padding] | The amount of blank space that is applied to the inside edge of all sides of the container. Options: `Top` / `Right` / `Bottom` / `Left` |

      {style="table-layout:auto"}

1. When complete, click **[!UICONTROL Save]** to apply the settings and return to the [!DNL Page Builder] workspace.

[background]: #background
[advanced]: #advanced
