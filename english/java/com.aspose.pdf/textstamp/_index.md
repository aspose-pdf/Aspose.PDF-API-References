---
title: TextStamp
second_title: Aspose.PDF for Java API Reference
description: Reresents textual stamp.
type: docs
weight: 389
url: /java/com.aspose.pdf/textstamp/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Stamp](../../com.aspose.pdf/stamp)
```
public class TextStamp extends Stamp
```

Reresents textual stamp.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextStamp(String value)](#TextStamp-java.lang.String-) | Initializes a new instance of the  TextStamp  class. |
| [TextStamp(String value, TextState textState)](#TextStamp-java.lang.String-com.aspose.pdf.TextState-) | Initializes a new instance of the  TextStamp  class. |
| [TextStamp(FormattedText formattedText)](#TextStamp-com.aspose.pdf.facades.FormattedText-) | Initializes a new instance of the  TextStamp  class with formattedText object |
## Methods

| Method | Description |
| --- | --- |
| [getDefaultFontSize()](#getDefaultFontSize--) | Default Font Size |
| [getDraw()](#getDraw--) | This property determines how stamp is drawn on page. |
| [setDraw(boolean value)](#setDraw-boolean-) | This property determines how stamp is drawn on page. |
| [getTreatYIndentAsBaseLine()](#getTreatYIndentAsBaseLine--) | Defines coordinate origin for placing text. |
| [setTreatYIndentAsBaseLine(boolean value)](#setTreatYIndentAsBaseLine-boolean-) | Defines coordinate origin for placing text. |
| [isWordWrap()](#isWordWrap--) | Defines word wrap. |
| [setWordWrap(boolean value)](#setWordWrap-boolean-) | Defines word wrap. |
| [isJustify()](#isJustify--) | Defines text justification. |
| [setJustify(boolean value)](#setJustify-boolean-) | Defines text justification. |
| [isScale()](#isScale--) | Defines scaling of the text. |
| [setScale(boolean value)](#setScale-boolean-) | Defines scaling of the text. |
| [getDefaultFont()](#getDefaultFont--) | Returns default font |
| [getValue()](#getValue--) | Gets string value which is used as stamp on the page. |
| [setValue(String value)](#setValue-java.lang.String-) | Sets string value which is used as stamp on the page. |
| [getTextState()](#getTextState--) | Gets text properties of the stamp. |
| [getTextAlignment()](#getTextAlignment--) | Alignment of the text inside the stamp. |
| [setTextAlignment(int value)](#setTextAlignment-int-) | Alignment of the text inside the stamp. |
| [put(Page page)](#put-com.aspose.pdf.Page-) | Adds textual stamp on the page. |
| [getWidth()](#getWidth--) | Desired width of the stamp on the page. |
| [setWidth(double value)](#setWidth-double-) | Desired width of the stamp on the page. |
| [getHeight()](#getHeight--) | Desired height of the stamp on the page. |
| [setHeight(double value)](#setHeight-double-) | Desired height of the stamp on the page. |
| [getMaxRowWidth()](#getMaxRowWidth--) | Max row height for WordWrap option. |
| [setMaxRowWidth(double value)](#setMaxRowWidth-double-) | Max row height for WordWrap option. |
### TextStamp(String value) {#TextStamp-java.lang.String-}
```
public TextStamp(String value)
```


Initializes a new instance of the  TextStamp  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Stamp value. |

### TextStamp(String value, TextState textState) {#TextStamp-java.lang.String-com.aspose.pdf.TextState-}
```
public TextStamp(String value, TextState textState)
```


Initializes a new instance of the  TextStamp  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Stamp value. |
| textState | [TextState](../../com.aspose.pdf/textstate) | Stamp text state. |

### TextStamp(FormattedText formattedText) {#TextStamp-com.aspose.pdf.facades.FormattedText-}
```
public TextStamp(FormattedText formattedText)
```


Initializes a new instance of the  TextStamp  class with formattedText object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | FormattedText object which contains text of the stamp. |

### getDefaultFontSize() {#getDefaultFontSize--}
```
public static float getDefaultFontSize()
```


Default Font Size

**Returns:**
float - float value
### getDraw() {#getDraw--}
```
public boolean getDraw()
```


This property determines how stamp is drawn on page. If Draw = true stamp is drawn as graphic operators and if draw = false then stamp is drawn as text.

**Returns:**
boolean - boolean value
### setDraw(boolean value) {#setDraw-boolean-}
```
public void setDraw(boolean value)
```


This property determines how stamp is drawn on page. If Draw = true stamp is drawn as graphic operators and if draw = false then stamp is drawn as text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getTreatYIndentAsBaseLine() {#getTreatYIndentAsBaseLine--}
```
public boolean getTreatYIndentAsBaseLine()
```


Defines coordinate origin for placing text. If TreatYIndentAsBaseLine = true (default when Draw = true) YIndent value will be treated as text base line. If TreatYIndentAsBaseLine = false (default when Draw = false) YIndent value will be treated as bottom (descent line) of text.

**Returns:**
boolean - boolean value
### setTreatYIndentAsBaseLine(boolean value) {#setTreatYIndentAsBaseLine-boolean-}
```
public void setTreatYIndentAsBaseLine(boolean value)
```


Defines coordinate origin for placing text. If TreatYIndentAsBaseLine = true (default when Draw = true) YIndent value will be treated as text base line. If TreatYIndentAsBaseLine = false (default when Draw = false) YIndent value will be treated as bottom (descent line) of text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isWordWrap() {#isWordWrap--}
```
public boolean isWordWrap()
```


Defines word wrap. If this property set to true and Width value specified, text will be broken in the several lines to fit into specified width. Default value: false.

**Returns:**
boolean - boolean value
### setWordWrap(boolean value) {#setWordWrap-boolean-}
```
public void setWordWrap(boolean value)
```


Defines word wrap. If this property set to true and Width value specified, text will be broken in the several lines to fit into specified width. Default value: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isJustify() {#isJustify--}
```
public boolean isJustify()
```


Defines text justification. If this property is set to true, both left and right edges of the text are aligned. Default value: false.

**Returns:**
boolean - boolean value
### setJustify(boolean value) {#setJustify-boolean-}
```
public void setJustify(boolean value)
```


Defines text justification. If this property is set to true, both left and right edges of the text are aligned. Default value: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isScale() {#isScale--}
```
public boolean isScale()
```


Defines scaling of the text. If this property is set to true and Width value specified, text will be scaled in order to fit to specified width.

**Returns:**
boolean - boolean value
### setScale(boolean value) {#setScale-boolean-}
```
public void setScale(boolean value)
```


Defines scaling of the text. If this property is set to true and Width value specified, text will be scaled in order to fit to specified width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getDefaultFont() {#getDefaultFont--}
```
public static Font getDefaultFont()
```


Returns default font

**Returns:**
[Font](../../com.aspose.pdf/font) - com.aspose.pdf.Font object
### getValue() {#getValue--}
```
public String getValue()
```


Gets string value which is used as stamp on the page.

**Returns:**
java.lang.String - String value
### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Sets string value which is used as stamp on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getTextState() {#getTextState--}
```
public TextState getTextState()
```


Gets text properties of the stamp. See  TextState  for details.

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState element
### getTextAlignment() {#getTextAlignment--}
```
public int getTextAlignment()
```


Alignment of the text inside the stamp.

**Returns:**
int - HorizontalAlignment value
### setTextAlignment(int value) {#setTextAlignment-int-}
```
public void setTextAlignment(int value)
```


Alignment of the text inside the stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HorizontalAlignment value |

### put(Page page) {#put-com.aspose.pdf.Page-}
```
public void put(Page page)
```


Adds textual stamp on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page for stamping. |

### getWidth() {#getWidth--}
```
public double getWidth()
```


Desired width of the stamp on the page.

**Returns:**
double - double value
### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Desired width of the stamp on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getHeight() {#getHeight--}
```
public double getHeight()
```


Desired height of the stamp on the page.

**Returns:**
double - double value
### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Desired height of the stamp on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getMaxRowWidth() {#getMaxRowWidth--}
```
public double getMaxRowWidth()
```


Max row height for WordWrap option.

**Returns:**
double - double value
### setMaxRowWidth(double value) {#setMaxRowWidth-double-}
```
public void setMaxRowWidth(double value)
```


Max row height for WordWrap option.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

