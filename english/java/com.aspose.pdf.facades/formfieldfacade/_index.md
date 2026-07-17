---
title: FormFieldFacade
linktitle: FormFieldFacade
second_title: Aspose.PDF for Java API Reference
description: Class for representing field properties.
type: docs
weight: 220
url: /java/com.aspose.pdf.facades/formfieldfacade/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.FormFieldFacade

```
public final class FormFieldFacade extends Object
```

Class for representing field properties.

## Fields

| Field | Description |
| --- | --- |
| [ALIGN_BOTTOM](#ALIGN_BOTTOM) | Defines vertical alignment as bottom style. |
| [ALIGN_CENTER](#ALIGN_CENTER) | Defines aglignment to center style. |
| [ALIGN_JUSTIFIED](#ALIGN_JUSTIFIED) | Defines text justification alignment style. |
| [ALIGN_LEFT](#ALIGN_LEFT) | Defines aglignment to left style. |
| [ALIGN_MIDDLE](#ALIGN_MIDDLE) | Defines vertical alignment as middle style. |
| [ALIGN_RIGHT](#ALIGN_RIGHT) | Defines alignment to right style. |
| [ALIGN_TOP](#ALIGN_TOP) | Defines vertical alignment as top style. |
| [ALIGN_UNDEFINED](#ALIGN_UNDEFINED) | Undefined alignment style. |
| [BORDER_STYLE_BEVELED](#BORDER_STYLE_BEVELED) | Defines a beveled border style. |
| [BORDER_STYLE_DASHED](#BORDER_STYLE_DASHED) | Defines a dashed border style. |
| [BORDER_STYLE_INSET](#BORDER_STYLE_INSET) | Defines an inseted border style. |
| [BORDER_STYLE_SOLID](#BORDER_STYLE_SOLID) | Defines a solid border style. |
| [BORDER_STYLE_UNDEFINED](#BORDER_STYLE_UNDEFINED) | Undefined border style. |
| [BORDER_STYLE_UNDERLINE](#BORDER_STYLE_UNDERLINE) | Defines an underlined border style. |
| [BORDER_WIDTH_MEDIUM](#BORDER_WIDTH_MEDIUM) | Defines a medium border width. |
| [BORDER_WIDTH_THICK](#BORDER_WIDTH_THICK) | Defines a thick border width. |
| [BORDER_WIDTH_THIN](#BORDER_WIDTH_THIN) | Defines a thin border width. |
| [BORDER_WIDTH_UNDEFINED](#BORDER_WIDTH_UNDEFINED) | Undefined border width. |
| [BORDER_WIDTH_UNDIFIED](#BORDER_WIDTH_UNDIFIED) | Undefined border width. |
| [CHECK_BOX_STYLE_CHECK](#CHECK_BOX_STYLE_CHECK) | Defines the shape of a check box field when it checked. |
| [CHECK_BOX_STYLE_CIRCLE](#CHECK_BOX_STYLE_CIRCLE) | Defines a circle check box style. |
| [CHECK_BOX_STYLE_CROSS](#CHECK_BOX_STYLE_CROSS) | Defines a cross check box style. |
| [CHECK_BOX_STYLE_DIAMOND](#CHECK_BOX_STYLE_DIAMOND) | Defines a diamond check box style. |
| [CHECK_BOX_STYLE_SQUARE](#CHECK_BOX_STYLE_SQUARE) | Defines a square check box style. |
| [CHECK_BOX_STYLE_STAR](#CHECK_BOX_STYLE_STAR) | Defines a star check box style. |
| [CHECK_BOX_STYLE_UNDEFINED](#CHECK_BOX_STYLE_UNDEFINED) | Defines an undefined check box style. |

## Constructors

| Constructor | Description |
| --- | --- |
| [FormFieldFacade](#FormFieldFacade--) |  |

## Methods

| Method | Description |
| --- | --- |
| [getAlignment](#getAlignment--) | Get the alignment of a field text, default is left alignment. |
| [getBackgroudColor](#getBackgroudColor--) | Obsolete property. Use BackgroundColor. This method is Deprecated. |
| [getBackgroundColor](#getBackgroundColor--) | Get the color of a field background, default is white. |
| [getBorderColor](#getBorderColor--) | Gets color of a field border. |
| [getBorderStyle](#getBorderStyle--) | Gets style of a field border. |
| [getBorderWidth](#getBorderWidth--) | Get width of a field border. |
| [getBox](#getBox--) | Get a rectangle object holding field's location. |
| [getButtonStyle](#getButtonStyle--) | Get the style of check box or radio box field, defined by FormFieldFacade.CheckBoxStyle*. |
| [getCaption](#getCaption--) | Get the normal caption of form field. |
| [getCustomFont](#getCustomFont--) | Gets the name of the font when this is non-standart (other then 14 standard fonts). |
| [getExportItems](#getExportItems--) | Get the options for adding a list/combo/radio box |
| [getFont](#getFont--) | Gets the font style type of a field text. |
| [getFontSize](#getFontSize--) | Gets the size of a field text. |
| [getItems](#getItems--) | Get an array of string, each representing an option of a combo box/list/radio box field. |
| [getPageNumber](#getPageNumber--) | Get an integer value holding the number of page on which field locates. |
| [getPosition](#getPosition--) | Get a rectangle object holding field's location. |
| [getRotation](#getRotation--) | Get the rotation of a field text. |
| [getTextColor](#getTextColor--) | Get the color of the field text. |
| [getTextEncoding](#getTextEncoding--) | Get the text encoding type of the field text. |
| [reset](#reset--) | Reset all visual attribtues to empty value. |
| [setAlignment](#setAlignment-int-) | Set the alignment of a field text, default is left alignment. |
| [setBackgroudColor](#setBackgroudColor-java.awt.Color-) | Deprecated. |
| [setBackgroundColor](#setBackgroundColor-java.awt.Color-) | Set the color of a field background, default is white. |
| [setBorderColor](#setBorderColor-java.awt.Color-) | Sets color of a field border. |
| [setBorderStyle](#setBorderStyle-int-) | Sets style of a field border. |
| [setBorderWidth](#setBorderWidth-float-) | Set width of a field border. |
| [setBox](#setBox-java.awt.Rectangle-) | Set a rectangle object holding field's location. |
| [setButtonStyle](#setButtonStyle-int-) | Set the style of check box or radio box field, defined by FormFieldFacade.CheckBoxStyle*. |
| [setCaption](#setCaption-java.lang.String-) | Set the normal caption of form field. |
| [setCustomFont](#setCustomFont-java.lang.String-) | Sets the name of the font when this is non-standart (other then 14 standard fonts). |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | Set the options for adding a list/combo/radio box |
| [setFont](#setFont-com.aspose.pdf.facades.FontStyle-) | Sets the font style type of a field text. |
| [setFontSize](#setFontSize-float-) | Sets the size of a field text. |
| [setItems](#setItems-java.lang.String:A-) | Set an array of string, each representing an option of a combo box/list/radio box field. |
| [setPageNumber](#setPageNumber-int-) | Set an integer value holding the number of page on which field locates. |
| [setPosition](#setPosition-float:A-) | Set a rectangle object holding field's location. |
| [setRotation](#setRotation-int-) | Set the rotation of a field text. |
| [setTextColor](#setTextColor-java.awt.Color-) | Set the color of the field text. |
| [setTextEncoding](#setTextEncoding-int-) | Set the {@link EncodingType} text encoding type of the field text. |

### ALIGN_BOTTOM {#ALIGN_BOTTOM}
```
public static final int ALIGN_BOTTOM
```

Defines vertical alignment as bottom style.

### ALIGN_CENTER {#ALIGN_CENTER}
```
public static final int ALIGN_CENTER
```

Defines aglignment to center style.

### ALIGN_JUSTIFIED {#ALIGN_JUSTIFIED}
```
public static final int ALIGN_JUSTIFIED
```

Defines text justification alignment style.

### ALIGN_LEFT {#ALIGN_LEFT}
```
public static final int ALIGN_LEFT
```

Defines aglignment to left style.

### ALIGN_MIDDLE {#ALIGN_MIDDLE}
```
public static final int ALIGN_MIDDLE
```

Defines vertical alignment as middle style.

### ALIGN_RIGHT {#ALIGN_RIGHT}
```
public static final int ALIGN_RIGHT
```

Defines alignment to right style.

### ALIGN_TOP {#ALIGN_TOP}
```
public static final int ALIGN_TOP
```

Defines vertical alignment as top style.

### ALIGN_UNDEFINED {#ALIGN_UNDEFINED}
```
public static final int ALIGN_UNDEFINED
```

Undefined alignment style.

### BORDER_STYLE_BEVELED {#BORDER_STYLE_BEVELED}
```
public static final int BORDER_STYLE_BEVELED
```

Defines a beveled border style.

### BORDER_STYLE_DASHED {#BORDER_STYLE_DASHED}
```
public static final int BORDER_STYLE_DASHED
```

Defines a dashed border style.

### BORDER_STYLE_INSET {#BORDER_STYLE_INSET}
```
public static final int BORDER_STYLE_INSET
```

Defines an inseted border style.

### BORDER_STYLE_SOLID {#BORDER_STYLE_SOLID}
```
public static final int BORDER_STYLE_SOLID
```

Defines a solid border style.

### BORDER_STYLE_UNDEFINED {#BORDER_STYLE_UNDEFINED}
```
public static final int BORDER_STYLE_UNDEFINED
```

Undefined border style.

### BORDER_STYLE_UNDERLINE {#BORDER_STYLE_UNDERLINE}
```
public static final int BORDER_STYLE_UNDERLINE
```

Defines an underlined border style.

### BORDER_WIDTH_MEDIUM {#BORDER_WIDTH_MEDIUM}
```
public static final float BORDER_WIDTH_MEDIUM
```

Defines a medium border width.

### BORDER_WIDTH_THICK {#BORDER_WIDTH_THICK}
```
public static final float BORDER_WIDTH_THICK
```

Defines a thick border width.

### BORDER_WIDTH_THIN {#BORDER_WIDTH_THIN}
```
public static final float BORDER_WIDTH_THIN
```

Defines a thin border width.

### BORDER_WIDTH_UNDEFINED {#BORDER_WIDTH_UNDEFINED}
```
public static final float BORDER_WIDTH_UNDEFINED
```

Undefined border width.

### BORDER_WIDTH_UNDIFIED {#BORDER_WIDTH_UNDIFIED}
```
@Deprecated public static final float BORDER_WIDTH_UNDIFIED
```

Undefined border width.

### CHECK_BOX_STYLE_CHECK {#CHECK_BOX_STYLE_CHECK}
```
public static final int CHECK_BOX_STYLE_CHECK
```

Defines the shape of a check box field when it checked.

### CHECK_BOX_STYLE_CIRCLE {#CHECK_BOX_STYLE_CIRCLE}
```
public static final int CHECK_BOX_STYLE_CIRCLE
```

Defines a circle check box style.

### CHECK_BOX_STYLE_CROSS {#CHECK_BOX_STYLE_CROSS}
```
public static final int CHECK_BOX_STYLE_CROSS
```

Defines a cross check box style.

### CHECK_BOX_STYLE_DIAMOND {#CHECK_BOX_STYLE_DIAMOND}
```
public static final int CHECK_BOX_STYLE_DIAMOND
```

Defines a diamond check box style.

### CHECK_BOX_STYLE_SQUARE {#CHECK_BOX_STYLE_SQUARE}
```
public static final int CHECK_BOX_STYLE_SQUARE
```

Defines a square check box style.

### CHECK_BOX_STYLE_STAR {#CHECK_BOX_STYLE_STAR}
```
public static final int CHECK_BOX_STYLE_STAR
```

Defines a star check box style.

### CHECK_BOX_STYLE_UNDEFINED {#CHECK_BOX_STYLE_UNDEFINED}
```
public static final int CHECK_BOX_STYLE_UNDEFINED
```

Defines an undefined check box style.

### FormFieldFacade {#FormFieldFacade--}
```
public FormFieldFacade()
```



### getAlignment {#getAlignment--}
```
public int getAlignment()
```

Get the alignment of a field text, default is left alignment.

**Returns:**
int value

### getBackgroudColor {#getBackgroudColor--}
```
@Deprecated public Color getBackgroudColor()
```

Obsolete property. Use BackgroundColor. This method is Deprecated.

**Returns:**
background color

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Get the color of a field background, default is white.

**Returns:**
Color element

### getBorderColor {#getBorderColor--}
```
public Color getBorderColor()
```

Gets color of a field border.

**Returns:**
color of a field border.

### getBorderStyle {#getBorderStyle--}
```
public int getBorderStyle()
```

Gets style of a field border.

**Returns:**
style of a field border.

### getBorderWidth {#getBorderWidth--}
```
public float getBorderWidth()
```

Get width of a field border.

**Returns:**
width of a field border.

### getBox {#getBox--}
```
public Rectangle getBox()
```

Get a rectangle object holding field's location.

**Returns:**
Rectangle element

### getButtonStyle {#getButtonStyle--}
```
public int getButtonStyle()
```

Get the style of check box or radio box field, defined by FormFieldFacade.CheckBoxStyle*.

**Returns:**
int value

### getCaption {#getCaption--}
```
public String getCaption()
```

Get the normal caption of form field.

**Returns:**
String value

### getCustomFont {#getCustomFont--}
```
public String getCustomFont()
```

Gets the name of the font when this is non-standart (other then 14 standard fonts).

**Returns:**
String value

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

Get the options for adding a list/combo/radio box

**Returns:**
array of String value

### getFont {#getFont--}
```
public FontStyle getFont()
```

Gets the font style type of a field text.

**Returns:**
FontStyle element @see FontStyle

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Gets the size of a field text.

**Returns:**
float value

### getItems {#getItems--}
```
public String [] getItems()
```

Get an array of string, each representing an option of a combo box/list/radio box field.

**Returns:**
array of String value

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Get an integer value holding the number of page on which field locates.

**Returns:**
int value

### getPosition {#getPosition--}
```
public float[] getPosition()
```

Get a rectangle object holding field's location.

**Returns:**
array of float value

### getRotation {#getRotation--}
```
public int getRotation()
```

Get the rotation of a field text.

**Returns:**
int value

### getTextColor {#getTextColor--}
```
public Color getTextColor()
```

Get the color of the field text.

**Returns:**
Color element

### getTextEncoding {#getTextEncoding--}
```
public int getTextEncoding()
```

Get the text encoding type of the field text.

**Returns:**
EncodingType element @see EncodingType

### reset {#reset--}
```
public void reset()
```

Reset all visual attribtues to empty value.

### setAlignment {#setAlignment-int-}
```
public void setAlignment(int value)
```

Set the alignment of a field text, default is left alignment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setBackgroudColor {#setBackgroudColor-java.awt.Color-}
Deprecated.

### setBackgroundColor {#setBackgroundColor-java.awt.Color-}
Set the color of a field background, default is white.

### setBorderColor {#setBorderColor-java.awt.Color-}
Sets color of a field border.

### setBorderStyle {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```

Sets style of a field border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | style of a field border. |

### setBorderWidth {#setBorderWidth-float-}
```
public void setBorderWidth(float value)
```

Set width of a field border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | width of a field border. |

### setBox {#setBox-java.awt.Rectangle-}
Set a rectangle object holding field's location.

### setButtonStyle {#setButtonStyle-int-}
```
public void setButtonStyle(int value)
```

Set the style of check box or radio box field, defined by FormFieldFacade.CheckBoxStyle*.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setCaption {#setCaption-java.lang.String-}
Set the normal caption of form field.

### setCustomFont {#setCustomFont-java.lang.String-}
Sets the name of the font when this is non-standart (other then 14 standard fonts).

### setExportItems {#setExportItems-java.lang.String:A:A-}
Set the options for adding a list/combo/radio box

### setFont {#setFont-com.aspose.pdf.facades.FontStyle-}
Sets the font style type of a field text.

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Sets the size of a field text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setItems {#setItems-java.lang.String:A-}
Set an array of string, each representing an option of a combo box/list/radio box field.

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Set an integer value holding the number of page on which field locates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setPosition {#setPosition-float:A-}
```
public void setPosition(float[] value)
```

Set a rectangle object holding field's location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | array of float value |

### setRotation {#setRotation-int-}
```
public void setRotation(int value)
```

Set the rotation of a field text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setTextColor {#setTextColor-java.awt.Color-}
Set the color of the field text.

### setTextEncoding {#setTextEncoding-int-}
```
public void setTextEncoding(int value)
```

Set the {@link EncodingType} text encoding type of the field text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | EncodingType element @see EncodingType |
