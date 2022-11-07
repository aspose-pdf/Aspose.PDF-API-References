---
title: TextState
second_title: Aspose.PDF for Java API Reference
description: Represents a text state of a text
type: docs
weight: 310
url: /java/com.aspose.pdf/textstate/
---
**Inheritance:**
java.lang.Object
```
public class TextState
```

Represents a text state of a text
## Constructors

| Constructor | Description |
| --- | --- |
| [TextState()](#TextState--) | Creates text state object. |
| [TextState(double fontSize)](#TextState-double-) | Creates text state object with font size specification. |
| [TextState(Color foregroundColor)](#TextState-com.aspose.pdf.java.awt.Color-) | Creates text state object with foreground color specification. |
| [TextState(System.Drawing.Color foregroundColor)](#TextState-com.aspose.ms.System.Drawing.Color-) |  |
| [TextState(Color foregroundColor, double fontSize)](#TextState-com.aspose.pdf.java.awt.Color-double-) | Creates text state object with foreground color and font size specification. |
| [TextState(System.Drawing.Color foregroundColor, double fontSize)](#TextState-com.aspose.ms.System.Drawing.Color-double-) |  |
| [TextState(String fontFamily)](#TextState-java.lang.String-) | Creates text state object with font family specification. |
| [TextState(String fontFamily, boolean bold, boolean italic)](#TextState-java.lang.String-boolean-boolean-) | Creates text state object with font family and font style specification. |
| [TextState(String fontFamily, double fontSize)](#TextState-java.lang.String-double-) | Creates text state object with font family and font size specification. |
## Methods

| Method | Description |
| --- | --- |
| [applyChangesFrom(TextState textState)](#applyChangesFrom-com.aspose.pdf.TextState-) | Applies settings from another textState |
| [getCharacterSpacing()](#getCharacterSpacing--) | Gets character spacing of the text. |
| [setCharacterSpacing(float value)](#setCharacterSpacing-float-) |  |
| [getLineSpacing()](#getLineSpacing--) | Gets or sets Note that the value is not preserved as a text characteristic within the document. |
| [setLineSpacing(float value)](#setLineSpacing-float-) |  |
| [getHorizontalScaling()](#getHorizontalScaling--) |  |
| [setHorizontalScaling(float value)](#setHorizontalScaling-float-) |  |
| [getWordSpacing()](#getWordSpacing--) |  |
| [setWordSpacing(float value)](#setWordSpacing-float-) |  |
| [getFontSize()](#getFontSize--) | Gets or sets font size of the text. |
| [setFontSize(float value)](#setFontSize-float-) |  |
| [getFont()](#getFont--) | Gets or sets font of the text. |
| [setFont(Font value)](#setFont-com.aspose.pdf.Font-) |  |
| [getForegroundColor()](#getForegroundColor--) | Gets or sets foreground color of the text. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.pdf.java.awt.Color-) |  |
| [getUnderline()](#getUnderline--) | Sets underline for the text, represented by the  TextFragment  object |
| [setUnderline(boolean value)](#setUnderline-boolean-) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.java.awt.Color-) | Sets background color of the text. |
| [getBackgroundColor()](#getBackgroundColor--) | Sets background color of the text. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) |  |
| [setFontStyle(int value)](#setFontStyle-int-) | Sets font style of the text. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets or sets horizontal alignment for the text. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) |  |
| [calculateFontSize(String str, Rectangle rect)](#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-) | Calculates the font size for the rectangle. |
### TextState() {#TextState--}
```
public TextState()
```


Creates text state object.

### TextState(double fontSize) {#TextState-double-}
```
public TextState(double fontSize)
```


Creates text state object with font size specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontSize | double |  |

### TextState(Color foregroundColor) {#TextState-com.aspose.pdf.java.awt.Color-}
```
public TextState(Color foregroundColor)
```


Creates text state object with foreground color specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| foregroundColor | [Color](../../com.aspose.pdf.java.awt/color) |  |

### TextState(System.Drawing.Color foregroundColor) {#TextState-com.aspose.ms.System.Drawing.Color-}
```
public TextState(System.Drawing.Color foregroundColor)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| foregroundColor | com.aspose.ms.System.Drawing.Color |  |

### TextState(Color foregroundColor, double fontSize) {#TextState-com.aspose.pdf.java.awt.Color-double-}
```
public TextState(Color foregroundColor, double fontSize)
```


Creates text state object with foreground color and font size specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| foregroundColor | [Color](../../com.aspose.pdf.java.awt/color) |  |
| fontSize | double |  |

### TextState(System.Drawing.Color foregroundColor, double fontSize) {#TextState-com.aspose.ms.System.Drawing.Color-double-}
```
public TextState(System.Drawing.Color foregroundColor, double fontSize)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| foregroundColor | com.aspose.ms.System.Drawing.Color |  |
| fontSize | double |  |

### TextState(String fontFamily) {#TextState-java.lang.String-}
```
public TextState(String fontFamily)
```


Creates text state object with font family specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFamily | java.lang.String |  |

### TextState(String fontFamily, boolean bold, boolean italic) {#TextState-java.lang.String-boolean-boolean-}
```
public TextState(String fontFamily, boolean bold, boolean italic)
```


Creates text state object with font family and font style specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFamily | java.lang.String |  |
| bold | boolean |  |
| italic | boolean |  |

### TextState(String fontFamily, double fontSize) {#TextState-java.lang.String-double-}
```
public TextState(String fontFamily, double fontSize)
```


Creates text state object with font family and font size specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFamily | java.lang.String |  |
| fontSize | double |  |

### applyChangesFrom(TextState textState) {#applyChangesFrom-com.aspose.pdf.TextState-}
```
public void applyChangesFrom(TextState textState)
```


Applies settings from another textState

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textState | [TextState](../../com.aspose.pdf/textstate) |  |

### getCharacterSpacing() {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```


Gets character spacing of the text.

**Returns:**
float - float value
### setCharacterSpacing(float value) {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLineSpacing() {#getLineSpacing--}
```
public float getLineSpacing()
```


Gets or sets Note that the value is not preserved as a text characteristic within the document. The LineSpacing property getter works for an object in case it was explicitly set previously with LineSpacing setter for those object. The property is used by runtime in context of current generation/modification process.

**Returns:**
float - 
### setLineSpacing(float value) {#setLineSpacing-float-}
```
public void setLineSpacing(float value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHorizontalScaling() {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```




**Returns:**
float
### setHorizontalScaling(float value) {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWordSpacing() {#getWordSpacing--}
```
public float getWordSpacing()
```




**Returns:**
float
### setWordSpacing(float value) {#setWordSpacing-float-}
```
public void setWordSpacing(float value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFontSize() {#getFontSize--}
```
public float getFontSize()
```


Gets or sets font size of the text.

**Returns:**
float
### setFontSize(float value) {#setFontSize-float-}
```
public void setFontSize(float value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFont() {#getFont--}
```
public Font getFont()
```


Gets or sets font of the text.

**Returns:**
[Font](../../com.aspose.pdf/font)
### setFont(Font value) {#setFont-com.aspose.pdf.Font-}
```
public void setFont(Font value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) |  |

### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Gets or sets foreground color of the text.

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color)
### setForegroundColor(Color value) {#setForegroundColor-com.aspose.pdf.java.awt.Color-}
```
public void setForegroundColor(Color value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf.java.awt/color) |  |

### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Sets underline for the text, represented by the  TextFragment  object

**Returns:**
boolean
### setUnderline(boolean value) {#setUnderline-boolean-}
```
public void setUnderline(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.java.awt.Color-}
```
public void setBackgroundColor(Color value)
```


Sets background color of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf.java.awt/color) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Sets background color of the text.

--------------------

Note that the value is not preserved as a text characteristic within the document. The BackgroundColor property getter works for an object in case it was explicitly set previously with BackgroundColor setter for those object. The property is used by runtime in context of current generation/modification process.

**Returns:**
[Color](../../com.aspose.ms.system.drawing/color)
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public void setBackgroundColor(Color value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) |  |

### setFontStyle(int value) {#setFontStyle-int-}
```
public void setFontStyle(int value)
```


Sets font style of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Gets or sets horizontal alignment for the text.

--------------------

HorizontalAlignment.None is equal to HorizontalAlignment.Left. Note that TextState.HorizontalAlignment property works in new document deneration generation scenarios only.

**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### calculateFontSize(String str, Rectangle rect) {#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-}
```
public double calculateFontSize(String str, Rectangle rect)
```


Calculates the font size for the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String |  |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) |  |

**Returns:**
double - 
