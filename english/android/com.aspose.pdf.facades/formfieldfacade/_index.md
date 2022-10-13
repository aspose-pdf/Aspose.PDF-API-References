---
title: FormFieldFacade
second_title: Aspose.PDF for Java API Reference
description: Class for representing field properties.
type: docs
weight: 26
url: /java/com.aspose.pdf.facades/formfieldfacade/
---
**Inheritance:**
java.lang.Object
```
public final class FormFieldFacade
```

Class for representing field properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [FormFieldFacade()](#FormFieldFacade--) |  |
## Fields

| Field | Description |
| --- | --- |
| [BORDER_WIDTH_UNDIFIED](#BORDER-WIDTH-UNDIFIED) | Undefined border width. |
| [BORDER_WIDTH_UNDEFINED](#BORDER-WIDTH-UNDEFINED) | Undefined border width. |
| [BORDER_WIDTH_THIN](#BORDER-WIDTH-THIN) | Defines a thin border width. |
| [BORDER_WIDTH_MEDIUM](#BORDER-WIDTH-MEDIUM) | Defines a medium border width. |
| [BORDER_WIDTH_THICK](#BORDER-WIDTH-THICK) | Defines a thick border width. |
| [BORDER_STYLE_SOLID](#BORDER-STYLE-SOLID) | Defines a solid border style. |
| [BORDER_STYLE_DASHED](#BORDER-STYLE-DASHED) | Defines a dashed border style. |
| [BORDER_STYLE_BEVELED](#BORDER-STYLE-BEVELED) | Defines a beveled border style. |
| [BORDER_STYLE_INSET](#BORDER-STYLE-INSET) | Defines an inseted border style. |
| [BORDER_STYLE_UNDERLINE](#BORDER-STYLE-UNDERLINE) | Defines an underlined border style. |
| [BORDER_STYLE_UNDEFINED](#BORDER-STYLE-UNDEFINED) | Undefined border style. |
| [ALIGN_LEFT](#ALIGN-LEFT) | Defines aglignment to left style. |
| [ALIGN_CENTER](#ALIGN-CENTER) | Defines aglignment to center style. |
| [ALIGN_RIGHT](#ALIGN-RIGHT) | Defines aglignment to right style. |
| [ALIGN_UNDEFINED](#ALIGN-UNDEFINED) | Undefined aglignment style. |
| [ALIGN_JUSTIFIED](#ALIGN-JUSTIFIED) | Defines text justification alignment style. |
| [ALIGN_TOP](#ALIGN-TOP) | Defines vertical aglignment as top style. |
| [ALIGN_MIDDLE](#ALIGN-MIDDLE) | Defines vertical aglignment as middle style. |
| [ALIGN_BOTTOM](#ALIGN-BOTTOM) | Defines vertical aglignment as bottom style. |
| [CHECK_BOX_STYLE_CIRCLE](#CHECK-BOX-STYLE-CIRCLE) | Defines a circle check box style. |
| [CHECK_BOX_STYLE_CHECK](#CHECK-BOX-STYLE-CHECK) | Defines the shape of a check box field when it checked. |
| [CHECK_BOX_STYLE_CROSS](#CHECK-BOX-STYLE-CROSS) | Defines a cross check box style. |
| [CHECK_BOX_STYLE_DIAMOND](#CHECK-BOX-STYLE-DIAMOND) | Defines a diamond check box style. |
| [CHECK_BOX_STYLE_STAR](#CHECK-BOX-STYLE-STAR) | Defines a star check box style. |
| [CHECK_BOX_STYLE_SQUARE](#CHECK-BOX-STYLE-SQUARE) | Defines a square check box style. |
| [CHECK_BOX_STYLE_UNDEFINED](#CHECK-BOX-STYLE-UNDEFINED) | Defines an undefined check box style. |
## Methods

| Method | Description |
| --- | --- |
| [getBorderColor()](#getBorderColor--) | The color of a field border. |
| [setBorderColor(Color value)](#setBorderColor-com.aspose.pdf.java.awt.Color-) |  |
| [getBorderStyle()](#getBorderStyle--) | The style of a field border. |
| [setBorderStyle(int value)](#setBorderStyle-int-) |  |
| [getBorderWidth()](#getBorderWidth--) | The width of a field border. |
| [setBorderWidth(float value)](#setBorderWidth-float-) |  |
| [getFont()](#getFont--) | Gets the font style type of a field text. |
| [setFont(int value)](#setFont-int-) | Sets the font style type of a field text. |
| [getCustomFont()](#getCustomFont--) | Gets the name of the font when this is non-standart (other then 14 standard fonts). |
| [setCustomFont(String value)](#setCustomFont-java.lang.String-) | Sets the name of the font when this is non-standart (other then 14 standard fonts). |
| [getFontSize()](#getFontSize--) | Gets the size of a field text. |
| [setFontSize(float value)](#setFontSize-float-) | Sets the size of a field text. |
| [getTextColor()](#getTextColor--) | Get the color of the field text. |
| [setTextColor(Color value)](#setTextColor-com.aspose.pdf.java.awt.Color-) | Set the color of the field text. |
| [getTextEncoding()](#getTextEncoding--) | Get the text encoding type of the field text. |
| [setTextEncoding(int value)](#setTextEncoding-int-) | Set the [EncodingType](../../com.aspose.pdf.engine.commondata.text.encoding/encodingtype) text encoding type of the field text. |
| [getAlignment()](#getAlignment--) | Get the alignment of a field text, default is left alignment. |
| [setAlignment(int value)](#setAlignment-int-) | Set the alignment of a field text, default is left alignment. |
| [getRotation()](#getRotation--) | Get the rotation of a field text. |
| [setRotation(int value)](#setRotation-int-) | Set the rotation of a field text. |
| [getCaption()](#getCaption--) | Get the normal caption of form field. |
| [setCaption(String value)](#setCaption-java.lang.String-) | Set the normal caption of form field. |
| [getButtonStyle()](#getButtonStyle--) | Get the style of check box or radio box field, defined by FormFieldFacade.CheckBoxStyle\*. |
| [setButtonStyle(int value)](#setButtonStyle-int-) | Set the style of check box or radio box field, defined by FormFieldFacade.CheckBoxStyle\*. |
| [getBox()](#getBox--) | Get a rectangle object holding field's location. |
| [setBox(Rect value)](#setBox-android.graphics.Rect-) |  |
| [setBox(Rectangle value)](#setBox-com.aspose.pdf.java.awt.Rectangle-) | Set a rectangle object holding field's location. |
| [getPosition()](#getPosition--) | Get a rectangle object holding field's location. |
| [setPosition(float[] value)](#setPosition-float---) | Set a rectangle object holding field's location. |
| [getPageNumber()](#getPageNumber--) | Get an integer value holding the number of page on which field locates. |
| [setPageNumber(int value)](#setPageNumber-int-) | Set an integer value holding the number of page on which field locates. |
| [getItems()](#getItems--) | Get an array of string, each representing an option of a combo box/list/radio box field. |
| [setItems(String[] value)](#setItems-java.lang.String---) | Set an array of string, each representing an option of a combo box/list/radio box field. |
| [getExportItems()](#getExportItems--) | Get the options for adding a list/combo/radio box |
| [setExportItems(String[][] value)](#setExportItems-java.lang.String-----) | Set the options for adding a list/combo/radio box |
| [getBackgroundColor()](#getBackgroundColor--) | Get the color of a field background, default is white. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.java.awt.Color-) | Set the color of a field background, default is white. |
| [reset()](#reset--) | Reset all visual attribtues to empty value. |
### FormFieldFacade() {#FormFieldFacade--}
```
public FormFieldFacade()
```


### BORDER_WIDTH_UNDIFIED {#BORDER-WIDTH-UNDIFIED}
```
public static final float BORDER_WIDTH_UNDIFIED
```


Undefined border width.

### BORDER_WIDTH_UNDEFINED {#BORDER-WIDTH-UNDEFINED}
```
public static final float BORDER_WIDTH_UNDEFINED
```


Undefined border width.

### BORDER_WIDTH_THIN {#BORDER-WIDTH-THIN}
```
public static final float BORDER_WIDTH_THIN
```


Defines a thin border width.

### BORDER_WIDTH_MEDIUM {#BORDER-WIDTH-MEDIUM}
```
public static final float BORDER_WIDTH_MEDIUM
```


Defines a medium border width.

### BORDER_WIDTH_THICK {#BORDER-WIDTH-THICK}
```
public static final float BORDER_WIDTH_THICK
```


Defines a thick border width.

### BORDER_STYLE_SOLID {#BORDER-STYLE-SOLID}
```
public static final int BORDER_STYLE_SOLID
```


Defines a solid border style.

### BORDER_STYLE_DASHED {#BORDER-STYLE-DASHED}
```
public static final int BORDER_STYLE_DASHED
```


Defines a dashed border style.

### BORDER_STYLE_BEVELED {#BORDER-STYLE-BEVELED}
```
public static final int BORDER_STYLE_BEVELED
```


Defines a beveled border style.

### BORDER_STYLE_INSET {#BORDER-STYLE-INSET}
```
public static final int BORDER_STYLE_INSET
```


Defines an inseted border style.

### BORDER_STYLE_UNDERLINE {#BORDER-STYLE-UNDERLINE}
```
public static final int BORDER_STYLE_UNDERLINE
```


Defines an underlined border style.

### BORDER_STYLE_UNDEFINED {#BORDER-STYLE-UNDEFINED}
```
public static final int BORDER_STYLE_UNDEFINED
```


Undefined border style.

### ALIGN_LEFT {#ALIGN-LEFT}
```
public static final int ALIGN_LEFT
```


Defines aglignment to left style.

### ALIGN_CENTER {#ALIGN-CENTER}
```
public static final int ALIGN_CENTER
```


Defines aglignment to center style.

### ALIGN_RIGHT {#ALIGN-RIGHT}
```
public static final int ALIGN_RIGHT
```


Defines aglignment to right style.

### ALIGN_UNDEFINED {#ALIGN-UNDEFINED}
```
public static final int ALIGN_UNDEFINED
```


Undefined aglignment style.

### ALIGN_JUSTIFIED {#ALIGN-JUSTIFIED}
```
public static final int ALIGN_JUSTIFIED
```


Defines text justification alignment style.

### ALIGN_TOP {#ALIGN-TOP}
```
public static final int ALIGN_TOP
```


Defines vertical aglignment as top style.

### ALIGN_MIDDLE {#ALIGN-MIDDLE}
```
public static final int ALIGN_MIDDLE
```


Defines vertical aglignment as middle style.

### ALIGN_BOTTOM {#ALIGN-BOTTOM}
```
public static final int ALIGN_BOTTOM
```


Defines vertical aglignment as bottom style.

### CHECK_BOX_STYLE_CIRCLE {#CHECK-BOX-STYLE-CIRCLE}
```
public static final int CHECK_BOX_STYLE_CIRCLE
```


Defines a circle check box style.

### CHECK_BOX_STYLE_CHECK {#CHECK-BOX-STYLE-CHECK}
```
public static final int CHECK_BOX_STYLE_CHECK
```


Defines the shape of a check box field when it checked.

### CHECK_BOX_STYLE_CROSS {#CHECK-BOX-STYLE-CROSS}
```
public static final int CHECK_BOX_STYLE_CROSS
```


Defines a cross check box style.

### CHECK_BOX_STYLE_DIAMOND {#CHECK-BOX-STYLE-DIAMOND}
```
public static final int CHECK_BOX_STYLE_DIAMOND
```


Defines a diamond check box style.

### CHECK_BOX_STYLE_STAR {#CHECK-BOX-STYLE-STAR}
```
public static final int CHECK_BOX_STYLE_STAR
```


Defines a star check box style.

### CHECK_BOX_STYLE_SQUARE {#CHECK-BOX-STYLE-SQUARE}
```
public static final int CHECK_BOX_STYLE_SQUARE
```


Defines a square check box style.

### CHECK_BOX_STYLE_UNDEFINED {#CHECK-BOX-STYLE-UNDEFINED}
```
public static final int CHECK_BOX_STYLE_UNDEFINED
```


Defines an undefined check box style.

### getBorderColor() {#getBorderColor--}
```
public Color getBorderColor()
```


The color of a field border.

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color)
### setBorderColor(Color value) {#setBorderColor-com.aspose.pdf.java.awt.Color-}
```
public void setBorderColor(Color value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf.java.awt/color) |  |

### getBorderStyle() {#getBorderStyle--}
```
public int getBorderStyle()
```


The style of a field border.

**Returns:**
int
### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBorderWidth() {#getBorderWidth--}
```
public float getBorderWidth()
```


The width of a field border.

**Returns:**
float
### setBorderWidth(float value) {#setBorderWidth-float-}
```
public void setBorderWidth(float value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFont() {#getFont--}
```
public int getFont()
```


Gets the font style type of a field text.

**Returns:**
int
### setFont(int value) {#setFont-int-}
```
public void setFont(int value)
```


Sets the font style type of a field text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCustomFont() {#getCustomFont--}
```
public String getCustomFont()
```


Gets the name of the font when this is non-standart (other then 14 standard fonts).

**Returns:**
java.lang.String
### setCustomFont(String value) {#setCustomFont-java.lang.String-}
```
public void setCustomFont(String value)
```


Sets the name of the font when this is non-standart (other then 14 standard fonts).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFontSize() {#getFontSize--}
```
public float getFontSize()
```


Gets the size of a field text.

**Returns:**
float
### setFontSize(float value) {#setFontSize-float-}
```
public void setFontSize(float value)
```


Sets the size of a field text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTextColor() {#getTextColor--}
```
public Color getTextColor()
```


Get the color of the field text.

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color)
### setTextColor(Color value) {#setTextColor-com.aspose.pdf.java.awt.Color-}
```
public void setTextColor(Color value)
```


Set the color of the field text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf.java.awt/color) |  |

### getTextEncoding() {#getTextEncoding--}
```
public int getTextEncoding()
```


Get the text encoding type of the field text.

**Returns:**
int
### setTextEncoding(int value) {#setTextEncoding-int-}
```
public void setTextEncoding(int value)
```


Set the [EncodingType](../../com.aspose.pdf.engine.commondata.text.encoding/encodingtype) text encoding type of the field text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Get the alignment of a field text, default is left alignment.

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Set the alignment of a field text, default is left alignment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRotation() {#getRotation--}
```
public int getRotation()
```


Get the rotation of a field text.

**Returns:**
int
### setRotation(int value) {#setRotation-int-}
```
public void setRotation(int value)
```


Set the rotation of a field text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCaption() {#getCaption--}
```
public String getCaption()
```


Get the normal caption of form field.

**Returns:**
java.lang.String
### setCaption(String value) {#setCaption-java.lang.String-}
```
public void setCaption(String value)
```


Set the normal caption of form field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getButtonStyle() {#getButtonStyle--}
```
public int getButtonStyle()
```


Get the style of check box or radio box field, defined by FormFieldFacade.CheckBoxStyle\*.

**Returns:**
int
### setButtonStyle(int value) {#setButtonStyle-int-}
```
public void setButtonStyle(int value)
```


Set the style of check box or radio box field, defined by FormFieldFacade.CheckBoxStyle\*.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBox() {#getBox--}
```
public Rect getBox()
```


Get a rectangle object holding field's location.

**Returns:**
android.graphics.Rect
### setBox(Rect value) {#setBox-android.graphics.Rect-}
```
public void setBox(Rect value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | android.graphics.Rect |  |

### setBox(Rectangle value) {#setBox-com.aspose.pdf.java.awt.Rectangle-}
```
public void setBox(Rectangle value)
```


Set a rectangle object holding field's location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf.java.awt/rectangle) |  |

### getPosition() {#getPosition--}
```
public float[] getPosition()
```


Get a rectangle object holding field's location.

**Returns:**
float[]
### setPosition(float[] value) {#setPosition-float---}
```
public void setPosition(float[] value)
```


Set a rectangle object holding field's location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Get an integer value holding the number of page on which field locates.

**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Set an integer value holding the number of page on which field locates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getItems() {#getItems--}
```
public String[] getItems()
```


Get an array of string, each representing an option of a combo box/list/radio box field.

**Returns:**
java.lang.String[]
### setItems(String[] value) {#setItems-java.lang.String---}
```
public void setItems(String[] value)
```


Set an array of string, each representing an option of a combo box/list/radio box field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getExportItems() {#getExportItems--}
```
public String[][] getExportItems()
```


Get the options for adding a list/combo/radio box

**Returns:**
java.lang.String[][]
### setExportItems(String[][] value) {#setExportItems-java.lang.String-----}
```
public void setExportItems(String[][] value)
```


Set the options for adding a list/combo/radio box

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[][] |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Get the color of a field background, default is white.

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color)
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.java.awt.Color-}
```
public void setBackgroundColor(Color value)
```


Set the color of a field background, default is white.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf.java.awt/color) |  |

### reset() {#reset--}
```
public void reset()
```


Reset all visual attribtues to empty value.

