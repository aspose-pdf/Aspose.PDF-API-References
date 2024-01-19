---
title: DefaultAppearance
second_title: Aspose.PDF for Java API Reference
description: Describes default appearance of field font text size and color.
type: docs
weight: 81
url: /java/com.aspose.pdf/defaultappearance/
---
**Inheritance:**
java.lang.Object
```
public final class DefaultAppearance
```

Describes default appearance of field (font, text size and color).
## Constructors

| Constructor | Description |
| --- | --- |
| [DefaultAppearance()](#DefaultAppearance--) | Constructor of DefaultAppearance. |
| [DefaultAppearance(IPdfDictionary engineDict)](#DefaultAppearance-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [DefaultAppearance(IPdfPrimitive appearance)](#DefaultAppearance-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
| [DefaultAppearance(String fontName, double fontSize, Color textColor)](#DefaultAppearance-java.lang.String-double-java.awt.Color-) | Constructor of DefaultAppearance. |
| [DefaultAppearance(Font font, double fontSize, Color textColor)](#DefaultAppearance-com.aspose.pdf.Font-double-java.awt.Color-) | Constructor of DefaultAppearance. |
## Methods

| Method | Description |
| --- | --- |
| [getFontSize()](#getFontSize--) | Gets font size in default appearance. |
| [setFontSize(double value)](#setFontSize-double-) | Sets font size in default appearance. |
| [getTextColor()](#getTextColor--) | Gets color of text in the default appearance. |
| [setTextColor(Color color)](#setTextColor-java.awt.Color-) | Sets color of text in the default appearance. |
| [getFontName()](#getFontName--) | Gets font name in the default appearance. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Gets font name in the default appearance. |
| [getFontResourceName()](#getFontResourceName--) | Gets font name in the default appearance. |
| [setFontResourceName(String value)](#setFontResourceName-java.lang.String-) | Gets font name in the default appearance. |
| [getFont()](#getFont--) | Gets font specified as default for text. |
| [getText()](#getText--) | Gets the list of pdf operators which represent appearence. |
### DefaultAppearance() {#DefaultAppearance--}
```
public DefaultAppearance()
```


Constructor of DefaultAppearance.

### DefaultAppearance(IPdfDictionary engineDict) {#DefaultAppearance-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public DefaultAppearance(IPdfDictionary engineDict)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| engineDict | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) |  |

### DefaultAppearance(IPdfPrimitive appearance) {#DefaultAppearance-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public DefaultAppearance(IPdfPrimitive appearance)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| appearance | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) |  |

### DefaultAppearance(String fontName, double fontSize, Color textColor) {#DefaultAppearance-java.lang.String-double-java.awt.Color-}
```
public DefaultAppearance(String fontName, double fontSize, Color textColor)
```


Constructor of DefaultAppearance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Font name. |
| fontSize | double | Font size. |
| textColor | java.awt.Color | Color of text. |

### DefaultAppearance(Font font, double fontSize, Color textColor) {#DefaultAppearance-com.aspose.pdf.Font-double-java.awt.Color-}
```
public DefaultAppearance(Font font, double fontSize, Color textColor)
```


Constructor of DefaultAppearance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| font | [Font](../../com.aspose.pdf/font) | Font which will be used as default. |
| fontSize | double | Font size. |
| textColor | java.awt.Color | Color of text. |

### getFontSize() {#getFontSize--}
```
public double getFontSize()
```


Gets font size in default appearance.

**Returns:**
double - font size
### setFontSize(double value) {#setFontSize-double-}
```
public void setFontSize(double value)
```


Sets font size in default appearance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | font size |

### getTextColor() {#getTextColor--}
```
public Color getTextColor()
```


Gets color of text in the default appearance.

**Returns:**
[Color](../../java.awt/color) - Color object
### setTextColor(Color color) {#setTextColor-java.awt.Color-}
```
public void setTextColor(Color color)
```


Sets color of text in the default appearance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | java.awt.Color | Color object |

### getFontName() {#getFontName--}
```
public String getFontName()
```


Gets font name in the default appearance.

**Returns:**
java.lang.String - String value
### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


Gets font name in the default appearance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getFontResourceName() {#getFontResourceName--}
```
public final String getFontResourceName()
```


Gets font name in the default appearance.

**Returns:**
java.lang.String - String value
### setFontResourceName(String value) {#setFontResourceName-java.lang.String-}
```
public final void setFontResourceName(String value)
```


Gets font name in the default appearance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getFont() {#getFont--}
```
public Font getFont()
```


Gets font specified as default for text.

**Returns:**
[Font](../../com.aspose.pdf/font) - Font value
### getText() {#getText--}
```
public String getText()
```


Gets the list of pdf operators which represent appearence.

**Returns:**
java.lang.String - String value
