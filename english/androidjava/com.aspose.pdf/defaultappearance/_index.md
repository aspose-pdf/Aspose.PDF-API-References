---
title: DefaultAppearance
second_title: Aspose.PDF for Java API Reference
description: Describes default appearance of field font text size and color.
type: docs
weight: 73
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
| [DefaultAppearance(String fontName, double fontSize, Color textColor)](#DefaultAppearance-java.lang.String-double-com.aspose.pdf.java.awt.Color-) | Constructor of DefaultAppearance. |
| [DefaultAppearance(Font font, double fontSize, Color textColor)](#DefaultAppearance-com.aspose.pdf.Font-double-com.aspose.pdf.java.awt.Color-) | Constructor of DefaultAppearance. |
## Methods

| Method | Description |
| --- | --- |
| [getFontSize()](#getFontSize--) | Gets font size in default apperance. |
| [setFontSize(double value)](#setFontSize-double-) |  |
| [getTextColor()](#getTextColor--) | Gets color of text in the default appearance. |
| [setTextColor(Color color)](#setTextColor-com.aspose.pdf.java.awt.Color-) |  |
| [setTextColor(int color)](#setTextColor-int-) |  |
| [getFontName()](#getFontName--) | Gets font name in the default appearance. |
| [setFontName(String resourceName)](#setFontName-java.lang.String-) |  |
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

### DefaultAppearance(String fontName, double fontSize, Color textColor) {#DefaultAppearance-java.lang.String-double-com.aspose.pdf.java.awt.Color-}
```
public DefaultAppearance(String fontName, double fontSize, Color textColor)
```


Constructor of DefaultAppearance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Font name. |
| fontSize | double | Font size. |
| textColor | [Color](../../com.aspose.pdf.java.awt/color) | Color of text. |

### DefaultAppearance(Font font, double fontSize, Color textColor) {#DefaultAppearance-com.aspose.pdf.Font-double-com.aspose.pdf.java.awt.Color-}
```
public DefaultAppearance(Font font, double fontSize, Color textColor)
```


Constructor of DefaultAppearance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| font | [Font](../../com.aspose.pdf/font) | Font which will be used as default. |
| fontSize | double | Font size. |
| textColor | [Color](../../com.aspose.pdf.java.awt/color) | Color of text. |

### getFontSize() {#getFontSize--}
```
public double getFontSize()
```


Gets font size in default apperance.

**Returns:**
double
### setFontSize(double value) {#setFontSize-double-}
```
public void setFontSize(double value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getTextColor() {#getTextColor--}
```
public Color getTextColor()
```


Gets color of text in the default appearance.

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color)
### setTextColor(Color color) {#setTextColor-com.aspose.pdf.java.awt.Color-}
```
public void setTextColor(Color color)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.pdf.java.awt/color) |  |

### setTextColor(int color) {#setTextColor-int-}
```
public void setTextColor(int color)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | int |  |

### getFontName() {#getFontName--}
```
public String getFontName()
```


Gets font name in the default appearance.

**Returns:**
java.lang.String
### setFontName(String resourceName) {#setFontName-java.lang.String-}
```
public void setFontName(String resourceName)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resourceName | java.lang.String |  |

### getFont() {#getFont--}
```
public Font getFont()
```


Gets font specified as default for text.

**Returns:**
[Font](../../com.aspose.pdf/font)
### getText() {#getText--}
```
public String getText()
```


Gets the list of pdf operators which represent appearence.

**Returns:**
java.lang.String
