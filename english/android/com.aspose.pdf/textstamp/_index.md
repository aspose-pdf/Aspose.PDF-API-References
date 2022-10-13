---
title: TextStamp
second_title: Aspose.PDF for Java API Reference
description: Reresents textual stamp.
type: docs
weight: 309
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
| [TextStamp(FormattedText formattedText)](#TextStamp-com.aspose.pdf.facades.FormattedText-) | Initializes a new instance of the  TextStamp  class with formattedText object |
## Fields

| Field | Description |
| --- | --- |
| [DefaultFontSize](#DefaultFontSize) |  |
## Methods

| Method | Description |
| --- | --- |
| [getDefaultFont()](#getDefaultFont--) |  |
| [getValue()](#getValue--) | Gets string value which is used as stamp on the page. |
| [setValue(String value)](#setValue-java.lang.String-) | Sets string value which is used as stamp on the page. |
| [getTextState()](#getTextState--) | Gets text properties of the stamp. |
| [getTextAlignment()](#getTextAlignment--) | Alignment of the text inside the stamp. |
| [setTextAlignment(int value)](#setTextAlignment-int-) |  |
| [put(Page page)](#put-com.aspose.pdf.Page-) | Adds textual stamp on the page. |
### TextStamp(String value) {#TextStamp-java.lang.String-}
```
public TextStamp(String value)
```


Initializes a new instance of the  TextStamp  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Stamp value. |

### TextStamp(FormattedText formattedText) {#TextStamp-com.aspose.pdf.facades.FormattedText-}
```
public TextStamp(FormattedText formattedText)
```


Initializes a new instance of the  TextStamp  class with formattedText object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) |  |

### DefaultFontSize {#DefaultFontSize}
```
public static final float DefaultFontSize
```


### getDefaultFont() {#getDefaultFont--}
```
public static Font getDefaultFont()
```




**Returns:**
[Font](../../com.aspose.pdf/font)
### getValue() {#getValue--}
```
public String getValue()
```


Gets string value which is used as stamp on the page.

**Returns:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Sets string value which is used as stamp on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextState() {#getTextState--}
```
public TextState getTextState()
```


Gets text properties of the stamp. See  TextState  for details.

**Returns:**
[TextState](../../com.aspose.pdf/textstate)
### getTextAlignment() {#getTextAlignment--}
```
public int getTextAlignment()
```


Alignment of the text inside the stamp.

**Returns:**
int
### setTextAlignment(int value) {#setTextAlignment-int-}
```
public void setTextAlignment(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### put(Page page) {#put-com.aspose.pdf.Page-}
```
public void put(Page page)
```


Adds textual stamp on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page for stamping. |

