---
title: FormattedText
second_title: Aspose.PDF for Java API Reference
description: Class which represents formatted text.
type: docs
weight: 27
url: /java/com.aspose.pdf.facades/formattedtext/
---
**Inheritance:**
java.lang.Object
```
public final class FormattedText
```

Class which represents formatted text. Contains information about text and its color, size, style.
## Constructors

| Constructor | Description |
| --- | --- |
| [FormattedText()](#FormattedText--) | Initializes FormattedText. |
| [FormattedText(String text)](#FormattedText-java.lang.String-) | Initializes FormattedText. |
| [FormattedText(String text, FontColor fontColor, int fontStyle, int encodingType, boolean embedded, float textSize)](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-int-int-boolean-float-) | Initializes FormattedText. |
| [FormattedText(String text, FontColor fontColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-int-int-boolean-float-float-) | Initialize FormattedText. |
| [FormattedText(String text, Color color, int textFont, int textEncoding, boolean embedded, float textSize)](#FormattedText-java.lang.String-com.aspose.pdf.java.awt.Color-int-int-boolean-float-) | Initializes FormattedText. |
| [FormattedText(String text, Color textColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)](#FormattedText-java.lang.String-com.aspose.pdf.java.awt.Color-int-int-boolean-float-float-) | Initializes FormattedText. |
| [FormattedText(String text, FontColor textColor, FontColor backColor, int textFont, int textEncoding, boolean embedded, float textSize)](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-int-int-boolean-float-) | Initializes FormattedText. |
| [FormattedText(String text, FontColor textColor, FontColor backColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-int-int-boolean-float-float-) | Initializes FormattedText. |
| [FormattedText(String text, Color textColor, Color backColor, int textFont, int encoding, boolean embedded, float textSize)](#FormattedText-java.lang.String-com.aspose.pdf.java.awt.Color-com.aspose.pdf.java.awt.Color-int-int-boolean-float-) | Initializes FormattedText. |
| [FormattedText(String text, Color textColor, Color backColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)](#FormattedText-java.lang.String-com.aspose.pdf.java.awt.Color-com.aspose.pdf.java.awt.Color-int-int-boolean-float-float-) | Initializes FormattedText. |
| [FormattedText(String text, Color textColor, Color backColor, String fontName, int textEncoding, boolean embedded, float fontSize)](#FormattedText-java.lang.String-com.aspose.pdf.java.awt.Color-com.aspose.pdf.java.awt.Color-java.lang.String-int-boolean-float-) | Initializes FormattedText. |
| [FormattedText(String text, Color textColor, Color backColor)](#FormattedText-java.lang.String-com.aspose.pdf.java.awt.Color-com.aspose.pdf.java.awt.Color-) | Initializes FormattedText. |
| [FormattedText(String text, Color textColor, String fontName, int textEncoding, boolean embedded, float fontSize)](#FormattedText-java.lang.String-com.aspose.pdf.java.awt.Color-java.lang.String-int-boolean-float-) | Initializes FormattedText. |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) |  |
| [getMpCustomLineSpacing()](#getMpCustomLineSpacing--) |  |
| [getFirstLine()](#getFirstLine--) | Gets first line |
| [getTextColor()](#getTextColor--) | Gets text color |
| [getBackColor()](#getBackColor--) | Gets back color |
| [getFont()](#getFont--) | Gets font |
| [getFontSize()](#getFontSize--) | Gets font size |
| [getTextHeight()](#getTextHeight--) | Gets height of text. |
| [getTextWidth()](#getTextWidth--) | Gets width of text. |
| [addNewLineText(String newLineText)](#addNewLineText-java.lang.String-) | Adds a new line to the FormattedText object and sets the newLineText to the next line's text. |
| [addNewLineText(String newLineText, float lineSpacing)](#addNewLineText-java.lang.String-float-) | Adds a new line to the FormattedText object and sets the newLineText to the next line's text. |
### FormattedText() {#FormattedText--}
```
public FormattedText()
```


Initializes FormattedText.

### FormattedText(String text) {#FormattedText-java.lang.String-}
```
public FormattedText(String text)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text which contained in FormattedText. |

### FormattedText(String text, FontColor fontColor, int fontStyle, int encodingType, boolean embedded, float textSize) {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-int-int-boolean-float-}
```
public FormattedText(String text, FontColor fontColor, int fontStyle, int encodingType, boolean embedded, float textSize)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content of the string. |
| fontColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | Color of the text. |
| fontStyle | int | Style of the text. |
| encodingType | int | Encoding type (value of EncodingType enumeration). |
| embedded | boolean | True if the font will be embedded. |
| textSize | float | Size of the text. |

### FormattedText(String text, FontColor fontColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing) {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-int-int-boolean-float-float-}
```
public FormattedText(String text, FontColor fontColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)
```


Initialize FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content of the string. |
| fontColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | Color of the text. |
| textFont | int | Font of the text. |
| textEncoding | int | Encoding of the text. |
| embedded | boolean | True if text will be embedded. |
| textSize | float | Size of the text. |
| lineSpacing | float | Additional spacing. |

### FormattedText(String text, Color color, int textFont, int textEncoding, boolean embedded, float textSize) {#FormattedText-java.lang.String-com.aspose.pdf.java.awt.Color-int-int-boolean-float-}
```
public FormattedText(String text, Color color, int textFont, int textEncoding, boolean embedded, float textSize)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content of the string. |
| color | [Color](../../com.aspose.pdf.java.awt/color) |  |
| textFont | int |  |
| textEncoding | int |  |
| embedded | boolean |  |
| textSize | float |  |

### FormattedText(String text, Color textColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing) {#FormattedText-java.lang.String-com.aspose.pdf.java.awt.Color-int-int-boolean-float-float-}
```
public FormattedText(String text, Color textColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text contents of the string. |
| textColor | [Color](../../com.aspose.pdf.java.awt/color) | Color of the text. |
| textFont | int | Font of the text. |
| textEncoding | int | Encoding of the text. |
| embedded | boolean | If true font will be embedded. |
| textSize | float | Size of the text. |
| lineSpacing | float | Additional spacing. |

### FormattedText(String text, FontColor textColor, FontColor backColor, int textFont, int textEncoding, boolean embedded, float textSize) {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-int-int-boolean-float-}
```
public FormattedText(String text, FontColor textColor, FontColor backColor, int textFont, int textEncoding, boolean embedded, float textSize)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content of the string. |
| textColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | Color of the text. |
| backColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | Color of background. |
| textFont | int | Font of the text. |
| textEncoding | int | Encoding of the text. |
| embedded | boolean | If true font will be embedded. |
| textSize | float | Size of the text. |

### FormattedText(String text, FontColor textColor, FontColor backColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing) {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-int-int-boolean-float-float-}
```
public FormattedText(String text, FontColor textColor, FontColor backColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content. |
| textColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | Color of the text. |
| backColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | Color of background. |
| textFont | int | Font of the text. |
| textEncoding | int | Encoding of the text. |
| embedded | boolean | If true font will be embedded. |
| textSize | float | Size of the text. |
| lineSpacing | float | Additional spacing. |

### FormattedText(String text, Color textColor, Color backColor, int textFont, int encoding, boolean embedded, float textSize) {#FormattedText-java.lang.String-com.aspose.pdf.java.awt.Color-com.aspose.pdf.java.awt.Color-int-int-boolean-float-}
```
public FormattedText(String text, Color textColor, Color backColor, int textFont, int encoding, boolean embedded, float textSize)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content of the string. |
| textColor | [Color](../../com.aspose.pdf.java.awt/color) | Color of the text. |
| backColor | [Color](../../com.aspose.pdf.java.awt/color) | Color of background. |
| textFont | int | Font of the text. |
| encoding | int | Encoding of the text. |
| embedded | boolean | True if font will be embedded. |
| textSize | float | Size of the text. |

### FormattedText(String text, Color textColor, Color backColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing) {#FormattedText-java.lang.String-com.aspose.pdf.java.awt.Color-com.aspose.pdf.java.awt.Color-int-int-boolean-float-float-}
```
public FormattedText(String text, Color textColor, Color backColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text contents of the string. |
| textColor | [Color](../../com.aspose.pdf.java.awt/color) | Color of the text. |
| backColor | [Color](../../com.aspose.pdf.java.awt/color) | Color of the background. |
| textFont | int | Font of the text. |
| textEncoding | int | Encoding of the text. |
| embedded | boolean | If true font is embedded. |
| textSize | float | Size of the text. |
| lineSpacing | float | Additional spacing. |

### FormattedText(String text, Color textColor, Color backColor, String fontName, int textEncoding, boolean embedded, float fontSize) {#FormattedText-java.lang.String-com.aspose.pdf.java.awt.Color-com.aspose.pdf.java.awt.Color-java.lang.String-int-boolean-float-}
```
public FormattedText(String text, Color textColor, Color backColor, String fontName, int textEncoding, boolean embedded, float fontSize)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content. |
| textColor | [Color](../../com.aspose.pdf.java.awt/color) | Color of the text. |
| backColor | [Color](../../com.aspose.pdf.java.awt/color) | Color of background. |
| fontName | java.lang.String | Font of the text. |
| textEncoding | int | Encoding of the text. |
| embedded | boolean | If true font will be embedded. |
| fontSize | float | Size of the text. |

### FormattedText(String text, Color textColor, Color backColor) {#FormattedText-java.lang.String-com.aspose.pdf.java.awt.Color-com.aspose.pdf.java.awt.Color-}
```
public FormattedText(String text, Color textColor, Color backColor)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content. |
| textColor | [Color](../../com.aspose.pdf.java.awt/color) | Color of the text. |
| backColor | [Color](../../com.aspose.pdf.java.awt/color) | Color of background. |

### FormattedText(String text, Color textColor, String fontName, int textEncoding, boolean embedded, float fontSize) {#FormattedText-java.lang.String-com.aspose.pdf.java.awt.Color-java.lang.String-int-boolean-float-}
```
public FormattedText(String text, Color textColor, String fontName, int textEncoding, boolean embedded, float fontSize)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content. |
| textColor | [Color](../../com.aspose.pdf.java.awt/color) | Color of the text. |
| fontName | java.lang.String | Font of the text. |
| textEncoding | int | Encoding of the text. |
| embedded | boolean | If true font will be embedded. |
| fontSize | float | Size of the text. |

### getText() {#getText--}
```
public System.Collections.ArrayList getText()
```




**Returns:**
com.aspose.ms.System.Collections.ArrayList
### getMpCustomLineSpacing() {#getMpCustomLineSpacing--}
```
public System.Collections.Hashtable getMpCustomLineSpacing()
```




**Returns:**
com.aspose.ms.System.Collections.Hashtable
### getFirstLine() {#getFirstLine--}
```
public String getFirstLine()
```


Gets first line

**Returns:**
java.lang.String - 
### getTextColor() {#getTextColor--}
```
public Color getTextColor()
```


Gets text color

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color) - 
### getBackColor() {#getBackColor--}
```
public Color getBackColor()
```


Gets back color

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color) - 
### getFont() {#getFont--}
```
public Font getFont()
```


Gets font

**Returns:**
[Font](../../com.aspose.pdf/font) - 
### getFontSize() {#getFontSize--}
```
public float getFontSize()
```


Gets font size

**Returns:**
float - 
### getTextHeight() {#getTextHeight--}
```
public float getTextHeight()
```


Gets height of text.

**Returns:**
float
### getTextWidth() {#getTextWidth--}
```
public float getTextWidth()
```


Gets width of text.

**Returns:**
float
### addNewLineText(String newLineText) {#addNewLineText-java.lang.String-}
```
public void addNewLineText(String newLineText)
```


Adds a new line to the FormattedText object and sets the newLineText to the next line's text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newLineText | java.lang.String | Text of new added line. |

### addNewLineText(String newLineText, float lineSpacing) {#addNewLineText-java.lang.String-float-}
```
public void addNewLineText(String newLineText, float lineSpacing)
```


Adds a new line to the FormattedText object and sets the newLineText to the next line's text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newLineText | java.lang.String | Text of new added line. |
| lineSpacing | float | Spacing of the line. |

