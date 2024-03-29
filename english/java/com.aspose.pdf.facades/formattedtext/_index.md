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
| [FormattedText(String text, FontColor fontColor, FontStyle fontStyle, int encodingType, boolean embedded, float textSize)](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontStyle-int-boolean-float-) | Initializes FormattedText. |
| [FormattedText(String text, FontColor fontColor, FontStyle textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontStyle-int-boolean-float-float-) | Initialize FormattedText. |
| [FormattedText(String text, Color color, FontStyle textFont, int textEncoding, boolean embedded, float textSize)](#FormattedText-java.lang.String-java.awt.Color-com.aspose.pdf.facades.FontStyle-int-boolean-float-) | Initializes FormattedText. |
| [FormattedText(String text, Color textColor, FontStyle textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)](#FormattedText-java.lang.String-java.awt.Color-com.aspose.pdf.facades.FontStyle-int-boolean-float-float-) | Initializes FormattedText. |
| [FormattedText(String text, FontColor textColor, FontColor backColor, FontStyle textFont, int textEncoding, boolean embedded, float textSize)](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontStyle-int-boolean-float-) | Initializes FormattedText. |
| [FormattedText(String text, FontColor textColor, FontColor backColor, FontStyle textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontStyle-int-boolean-float-float-) | Initializes FormattedText. |
| [FormattedText(String text, Color textColor, Color backColor, FontStyle textFont, int encoding, boolean embedded, float textSize)](#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-com.aspose.pdf.facades.FontStyle-int-boolean-float-) | Initializes FormattedText. |
| [FormattedText(String text, Color textColor, Color backColor, FontStyle textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)](#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-com.aspose.pdf.facades.FontStyle-int-boolean-float-float-) | Initializes FormattedText. |
| [FormattedText(String text, Color textColor, Color backColor, String fontName, int textEncoding, boolean embedded, float fontSize)](#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-java.lang.String-int-boolean-float-) | Initializes FormattedText. |
| [FormattedText(String text, Color textColor, Color backColor)](#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-) | Initializes FormattedText. |
| [FormattedText(String text, Color textColor, String fontName, int textEncoding, boolean embedded, float fontSize)](#FormattedText-java.lang.String-java.awt.Color-java.lang.String-int-boolean-float-) | Initializes FormattedText. |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | For Internal usage only |
| [getFirstLine()](#getFirstLine--) | Gets first line |
| [getTextColor()](#getTextColor--) | Internal Gets text color |
| [getBackColor()](#getBackColor--) | Internal Gets back color |
| [getFont()](#getFont--) | Gets font |
| [getFontSize()](#getFontSize--) | Gets font size |
| [getTextHeight()](#getTextHeight--) | Gets height of text. |
| [getTextWidth()](#getTextWidth--) | Gets width of text. |
| [addNewLineText(String newLineText)](#addNewLineText-java.lang.String-) | Adds a new line to the FormattedText object and sets the newLineText to the next line's text. |
| [addNewLineText(String newLineText, float lineSpacing)](#addNewLineText-java.lang.String-float-) | Adds a new line to the FormattedText object and sets the newLineText to the next line's text. |
| [isCjk()](#isCjk--) | Checks if text is CJK (Chinese, Japanese, or Korean). |
| [setCjkFontStyle()](#setCjkFontStyle--) | Changes FormattedText font style for CJK (Chinese, Japanese, or Korean) font. |
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

### FormattedText(String text, FontColor fontColor, FontStyle fontStyle, int encodingType, boolean embedded, float textSize) {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontStyle-int-boolean-float-}
```
public FormattedText(String text, FontColor fontColor, FontStyle fontStyle, int encodingType, boolean embedded, float textSize)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content of the string. |
| fontColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | Color of the text. |
| fontStyle | [FontStyle](../../com.aspose.pdf.facades/fontstyle) | Style of the text. |
| encodingType | int | Encoding type (value of EncodingType enumeration). |
| embedded | boolean | True if the font will be embedded. |
| textSize | float | Size of the text. |

### FormattedText(String text, FontColor fontColor, FontStyle textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing) {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontStyle-int-boolean-float-float-}
```
public FormattedText(String text, FontColor fontColor, FontStyle textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)
```


Initialize FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content of the string. |
| fontColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | Color of the text. |
| textFont | [FontStyle](../../com.aspose.pdf.facades/fontstyle) | Font of the text. |
| textEncoding | int | Encoding of the text. |
| embedded | boolean | True if text will be embedded. |
| textSize | float | Size of the text. |
| lineSpacing | float | Additional spacing. |

### FormattedText(String text, Color color, FontStyle textFont, int textEncoding, boolean embedded, float textSize) {#FormattedText-java.lang.String-java.awt.Color-com.aspose.pdf.facades.FontStyle-int-boolean-float-}
```
public FormattedText(String text, Color color, FontStyle textFont, int textEncoding, boolean embedded, float textSize)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content of the string. |
| color | java.awt.Color | Color of the text. |
| textFont | [FontStyle](../../com.aspose.pdf.facades/fontstyle) | Font of the text. |
| textEncoding | int | Encoding of the text. |
| embedded | boolean | True if text will be embedded. |
| textSize | float | Size of the text. |

### FormattedText(String text, Color textColor, FontStyle textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing) {#FormattedText-java.lang.String-java.awt.Color-com.aspose.pdf.facades.FontStyle-int-boolean-float-float-}
```
public FormattedText(String text, Color textColor, FontStyle textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text contents of the string. |
| textColor | java.awt.Color | Color of the text. |
| textFont | [FontStyle](../../com.aspose.pdf.facades/fontstyle) | Font of the text. |
| textEncoding | int | Encoding of the text. |
| embedded | boolean | If true font will be embedded. |
| textSize | float | Size of the text. |
| lineSpacing | float | Additional spacing. |

### FormattedText(String text, FontColor textColor, FontColor backColor, FontStyle textFont, int textEncoding, boolean embedded, float textSize) {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontStyle-int-boolean-float-}
```
public FormattedText(String text, FontColor textColor, FontColor backColor, FontStyle textFont, int textEncoding, boolean embedded, float textSize)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content of the string. |
| textColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | Color of the text. |
| backColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | Color of background. |
| textFont | [FontStyle](../../com.aspose.pdf.facades/fontstyle) | Font of the text. |
| textEncoding | int | Encoding of the text. |
| embedded | boolean | If true font will be embedded. |
| textSize | float | Size of the text. |

### FormattedText(String text, FontColor textColor, FontColor backColor, FontStyle textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing) {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontStyle-int-boolean-float-float-}
```
public FormattedText(String text, FontColor textColor, FontColor backColor, FontStyle textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content. |
| textColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | Color of the text. |
| backColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | Color of background. |
| textFont | [FontStyle](../../com.aspose.pdf.facades/fontstyle) | Font of the text. |
| textEncoding | int | Encoding of the text. |
| embedded | boolean | If true font will be embedded. |
| textSize | float | Size of the text. |
| lineSpacing | float | Additional spacing. |

### FormattedText(String text, Color textColor, Color backColor, FontStyle textFont, int encoding, boolean embedded, float textSize) {#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-com.aspose.pdf.facades.FontStyle-int-boolean-float-}
```
public FormattedText(String text, Color textColor, Color backColor, FontStyle textFont, int encoding, boolean embedded, float textSize)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content of the string. |
| textColor | java.awt.Color | Color of the text. |
| backColor | java.awt.Color | Color of background. |
| textFont | [FontStyle](../../com.aspose.pdf.facades/fontstyle) | Font of the text. |
| encoding | int | Encoding of the text. |
| embedded | boolean | True if font will be embedded. |
| textSize | float | Size of the text. |

### FormattedText(String text, Color textColor, Color backColor, FontStyle textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing) {#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-com.aspose.pdf.facades.FontStyle-int-boolean-float-float-}
```
public FormattedText(String text, Color textColor, Color backColor, FontStyle textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text contents of the string. |
| textColor | java.awt.Color | Color of the text. |
| backColor | java.awt.Color | Color of the background. |
| textFont | [FontStyle](../../com.aspose.pdf.facades/fontstyle) | Font of the text. |
| textEncoding | int | Encoding of the text. |
| embedded | boolean | If true font is embedded. |
| textSize | float | Size of the text. |
| lineSpacing | float | Additional spacing. |

### FormattedText(String text, Color textColor, Color backColor, String fontName, int textEncoding, boolean embedded, float fontSize) {#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-java.lang.String-int-boolean-float-}
```
public FormattedText(String text, Color textColor, Color backColor, String fontName, int textEncoding, boolean embedded, float fontSize)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content. |
| textColor | java.awt.Color | Color of the text. |
| backColor | java.awt.Color | Color of background. |
| fontName | java.lang.String | Font of the text. |
| textEncoding | int | Encoding of the text. |
| embedded | boolean | If true font will be embedded. |
| fontSize | float | Size of the text. |

### FormattedText(String text, Color textColor, Color backColor) {#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-}
```
public FormattedText(String text, Color textColor, Color backColor)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content. |
| textColor | java.awt.Color | Color of the text. |
| backColor | java.awt.Color | Color of background. |

### FormattedText(String text, Color textColor, String fontName, int textEncoding, boolean embedded, float fontSize) {#FormattedText-java.lang.String-java.awt.Color-java.lang.String-int-boolean-float-}
```
public FormattedText(String text, Color textColor, String fontName, int textEncoding, boolean embedded, float fontSize)
```


Initializes FormattedText.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content. |
| textColor | java.awt.Color | Color of the text. |
| fontName | java.lang.String | Font of the text. |
| textEncoding | int | Encoding of the text. |
| embedded | boolean | If true font will be embedded. |
| fontSize | float | Size of the text. |

### getText() {#getText--}
```
public System.Collections.Generic.List<String> getText()
```


For Internal usage only

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Internal object
### getFirstLine() {#getFirstLine--}
```
public String getFirstLine()
```


Gets first line

**Returns:**
java.lang.String - String value
### getTextColor() {#getTextColor--}
```
public System.Drawing.Color getTextColor()
```


Internal Gets text color

**Returns:**
[Color](../../com.aspose.ms.system.drawing/color) - Color element
### getBackColor() {#getBackColor--}
```
public System.Drawing.Color getBackColor()
```


Internal Gets back color

**Returns:**
[Color](../../com.aspose.ms.system.drawing/color) - Color element
### getFont() {#getFont--}
```
public Font getFont()
```


Gets font

**Returns:**
[Font](../../com.aspose.pdf/font) - Font element
### getFontSize() {#getFontSize--}
```
public float getFontSize()
```


Gets font size

**Returns:**
float - float value
### getTextHeight() {#getTextHeight--}
```
public float getTextHeight()
```


Gets height of text.

**Returns:**
float - float value
### getTextWidth() {#getTextWidth--}
```
public float getTextWidth()
```


Gets width of text.

**Returns:**
float - float value
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

### isCjk() {#isCjk--}
```
public final boolean isCjk()
```


Checks if text is CJK (Chinese, Japanese, or Korean).

**Returns:**
boolean - True if text is CJK. Otherwise false.
### setCjkFontStyle() {#setCjkFontStyle--}
```
public final void setCjkFontStyle()
```


Changes FormattedText font style for CJK (Chinese, Japanese, or Korean) font.

