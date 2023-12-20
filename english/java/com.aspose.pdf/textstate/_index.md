---
title: TextState
second_title: Aspose.PDF for Java API Reference
description: Represents a text state of a text
type: docs
weight: 390
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
| [TextState(Color foregroundColor)](#TextState-java.awt.Color-) | Creates text state object with foreground color specification. |
| [TextState(Color foregroundColor, double fontSize)](#TextState-java.awt.Color-double-) | Creates text state object with foreground color and font size specification. |
| [TextState(String fontFamily)](#TextState-java.lang.String-) | Creates text state object with font family specification. |
| [TextState(String fontFamily, boolean bold, boolean italic)](#TextState-java.lang.String-boolean-boolean-) | Creates text state object with font family and font style specification. |
| [TextState(String fontFamily, double fontSize)](#TextState-java.lang.String-double-) | Creates text state object with font family and font size specification. |
## Fields

| Field | Description |
| --- | --- |
| [TabTag](#TabTag) | You can place this tag in text to declare tabulation. |
| [TabstopDefaultValue](#TabstopDefaultValue) | Default value of tabulation in widths of space character of default font. |
## Methods

| Method | Description |
| --- | --- |
| [applyChangesFrom(TextState textState)](#applyChangesFrom-com.aspose.pdf.TextState-) | Applies settings from another textState |
| [getCharacterSpacing()](#getCharacterSpacing--) | Gets character spacing of the text. |
| [setCharacterSpacing(float value)](#setCharacterSpacing-float-) | Sets character spacing of the text. |
| [getLineSpacing()](#getLineSpacing--) | Gets line spacing of the text. |
| [setLineSpacing(float value)](#setLineSpacing-float-) | Sets line spacing of the text. |
| [getHorizontalScaling()](#getHorizontalScaling--) | Gets horizontal scaling of the text. |
| [setHorizontalScaling(float value)](#setHorizontalScaling-float-) | Sets horizontal scaling of the text. |
| [isSubscript()](#isSubscript--) | Gets or sets subscript of the text. |
| [setSubscript(boolean value)](#setSubscript-boolean-) | Gets or sets subscript of the text. |
| [isSuperscript()](#isSuperscript--) | Gets superscript of the text. |
| [setSuperscript(boolean value)](#setSuperscript-boolean-) | Sets superscript of the text. |
| [getWordSpacing()](#getWordSpacing--) | Gets word spacing of the text. |
| [setWordSpacing(float value)](#setWordSpacing-float-) | Sets word spacing of the text. |
| [isInvisible()](#isInvisible--) | Gets the invisibility of text. |
| [setInvisible(boolean value)](#setInvisible-boolean-) | Sets the invisibility of text. |
| [getRenderingMode()](#getRenderingMode--) | Gets or sets rendering mode of text. |
| [setRenderingMode(int value)](#setRenderingMode-int-) | Gets or sets rendering mode of text. |
| [getFontSize()](#getFontSize--) | Gets font size of the text. |
| [setFontSizeSuppressedUpdate(float value)](#setFontSizeSuppressedUpdate-float-) | Sets font size of the text wish suppressed update. |
| [setFontSize(float value)](#setFontSize-float-) | Sets font size of the text. |
| [getTextHeight()](#getTextHeight--) | Gets text height. |
| [getFont()](#getFont--) | Gets font of the text. |
| [setFontSuppressedUpdate(Font value)](#setFontSuppressedUpdate-com.aspose.pdf.Font-) | Gets font of the text wish suppressed update. |
| [setFont(Font value)](#setFont-com.aspose.pdf.Font-) | Gets font of the text. |
| [getForegroundColor()](#getForegroundColor--) | Gets foreground color of the text. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.pdf.Color-) | Sets foreground color of the text. |
| [getStrokingColor()](#getStrokingColor--) | Gets or sets foreground color of the text. |
| [setStrokingColor(Color value)](#setStrokingColor-com.aspose.pdf.Color-) | Gets or sets foreground color of the text. |
| [isUnderline()](#isUnderline--) | Gets underline for the text, represented by the  TextFragment  object |
| [setUnderline(boolean value)](#setUnderline-boolean-) | Sets underline for the text, represented by the  TextFragment  object |
| [getStrikeOut()](#getStrikeOut--) | Gets strikeout for the text, represented by the  TextFragment  object |
| [setStrikeOut(boolean value)](#setStrikeOut-boolean-) | Sets strikeout for the text, represented by the  TextFragment  object |
| [getBackgroundColor()](#getBackgroundColor--) | Gets background color of the text. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Sets background color of the text. |
| [getFontStyle()](#getFontStyle--) | Sets font style of the text. |
| [setFontStyle(int value)](#setFontStyle-int-) | Sets font style of the text. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets horizontal alignment for the text. |
| [setHorizontalAlignment(HorizontalAlignment value)](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Sets horizontal alignment for the text. |
| [measureString(String str, boolean insideLine)](#measureString-java.lang.String-boolean-) | Measures the string. |
| [measureString(String str)](#measureString-java.lang.String-) | Measures the string. |
| [measureHeight(char character)](#measureHeight-char-) | Measures character height. |
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
| fontSize | double | Font size. |

### TextState(Color foregroundColor) {#TextState-java.awt.Color-}
```
public TextState(Color foregroundColor)
```


Creates text state object with foreground color specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| foregroundColor | java.awt.Color | Foreground color. |

### TextState(Color foregroundColor, double fontSize) {#TextState-java.awt.Color-double-}
```
public TextState(Color foregroundColor, double fontSize)
```


Creates text state object with foreground color and font size specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| foregroundColor | java.awt.Color | Foreground color. |
| fontSize | double | Font size. |

### TextState(String fontFamily) {#TextState-java.lang.String-}
```
public TextState(String fontFamily)
```


Creates text state object with font family specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFamily | java.lang.String | Font family. |

### TextState(String fontFamily, boolean bold, boolean italic) {#TextState-java.lang.String-boolean-boolean-}
```
public TextState(String fontFamily, boolean bold, boolean italic)
```


Creates text state object with font family and font style specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFamily | java.lang.String | Font family. |
| bold | boolean | Bold font style. |
| italic | boolean | Italic font style. |

### TextState(String fontFamily, double fontSize) {#TextState-java.lang.String-double-}
```
public TextState(String fontFamily, double fontSize)
```


Creates text state object with font family and font size specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFamily | java.lang.String | Font family. |
| fontSize | double | Font size. |

### TabTag {#TabTag}
```
public static final String TabTag
```


You can place this tag in text to declare tabulation.

--------------------

It has effect only in couple with  TabStops .

### TabstopDefaultValue {#TabstopDefaultValue}
```
public final float TabstopDefaultValue
```


Default value of tabulation in widths of space character of default font.

### applyChangesFrom(TextState textState) {#applyChangesFrom-com.aspose.pdf.TextState-}
```
public void applyChangesFrom(TextState textState)
```


Applies settings from another textState

--------------------

Only those properties will be copied that were changed explicitly.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textState | [TextState](../../com.aspose.pdf/textstate) | Text state object. |

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


Sets character spacing of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### getLineSpacing() {#getLineSpacing--}
```
public float getLineSpacing()
```


Gets line spacing of the text.

**Returns:**
float - float value

--------------------

Note that the value is not preserved as a text characteristic within the document. The LineSpacing property getter works for an object in case it was explicitly set previously with LineSpacing setter for those object. The property is used by runtime in context of current generation/modification process.
### setLineSpacing(float value) {#setLineSpacing-float-}
```
public void setLineSpacing(float value)
```


Sets line spacing of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value

--------------------

Note that the value is not preserved as a text characteristic within the document. The LineSpacing property getter works for an object in case it was explicitly set previously with LineSpacing setter for those object. The property is used by runtime in context of current generation/modification process. |

### getHorizontalScaling() {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```


Gets horizontal scaling of the text.

**Returns:**
float - float value
### setHorizontalScaling(float value) {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```


Sets horizontal scaling of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### isSubscript() {#isSubscript--}
```
public boolean isSubscript()
```


Gets or sets subscript of the text.

**Returns:**
boolean - boolean value
### setSubscript(boolean value) {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```


Gets or sets subscript of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isSuperscript() {#isSuperscript--}
```
public boolean isSuperscript()
```


Gets superscript of the text.

**Returns:**
boolean - boolean value
### setSuperscript(boolean value) {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```


Sets superscript of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getWordSpacing() {#getWordSpacing--}
```
public float getWordSpacing()
```


Gets word spacing of the text.

**Returns:**
float - float value
### setWordSpacing(float value) {#setWordSpacing-float-}
```
public void setWordSpacing(float value)
```


Sets word spacing of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### isInvisible() {#isInvisible--}
```
public boolean isInvisible()
```


Gets the invisibility of text. This basically reflects the  RenderingMode (\#getRenderingMode\#getRenderingMode/\#setRenderingMode(int)\#setRenderingMode(int)) state, except for some special cases (like clipping).

**Returns:**
boolean - boolean value
### setInvisible(boolean value) {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```


Sets the invisibility of text. This basically reflects the  RenderingMode (\#getRenderingMode\#getRenderingMode/\#setRenderingMode(int)\#setRenderingMode(int)) state, except for some special cases (like clipping).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getRenderingMode() {#getRenderingMode--}
```
public int getRenderingMode()
```


Gets or sets rendering mode of text.

**Returns:**
int - TextRenderingMode element
### setRenderingMode(int value) {#setRenderingMode-int-}
```
public void setRenderingMode(int value)
```


Gets or sets rendering mode of text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | TextRenderingMode element |

### getFontSize() {#getFontSize--}
```
public float getFontSize()
```


Gets font size of the text.

**Returns:**
float - float value
### setFontSizeSuppressedUpdate(float value) {#setFontSizeSuppressedUpdate-float-}
```
public void setFontSizeSuppressedUpdate(float value)
```


Sets font size of the text wish suppressed update.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### setFontSize(float value) {#setFontSize-float-}
```
public void setFontSize(float value)
```


Sets font size of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### getTextHeight() {#getTextHeight--}
```
public float getTextHeight()
```


Gets text height.

**Returns:**
float - float value
### getFont() {#getFont--}
```
public Font getFont()
```


Gets font of the text.

**Returns:**
[Font](../../com.aspose.pdf/font) - Font object
### setFontSuppressedUpdate(Font value) {#setFontSuppressedUpdate-com.aspose.pdf.Font-}
```
public void setFontSuppressedUpdate(Font value)
```


Gets font of the text wish suppressed update.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) | Font object |

### setFont(Font value) {#setFont-com.aspose.pdf.Font-}
```
public void setFont(Font value)
```


Gets font of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) | Font object |

### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Gets foreground color of the text.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color value
### setForegroundColor(Color value) {#setForegroundColor-com.aspose.pdf.Color-}
```
public void setForegroundColor(Color value)
```


Sets foreground color of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color value |

### getStrokingColor() {#getStrokingColor--}
```
public Color getStrokingColor()
```


Gets or sets foreground color of the text.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color instance
### setStrokingColor(Color value) {#setStrokingColor-com.aspose.pdf.Color-}
```
public void setStrokingColor(Color value)
```


Gets or sets foreground color of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color instance |

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Gets underline for the text, represented by the  TextFragment  object

**Returns:**
boolean - boolean value
### setUnderline(boolean value) {#setUnderline-boolean-}
```
public void setUnderline(boolean value)
```


Sets underline for the text, represented by the  TextFragment  object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getStrikeOut() {#getStrikeOut--}
```
public boolean getStrikeOut()
```


Gets strikeout for the text, represented by the  TextFragment  object

**Returns:**
boolean - boolean value
### setStrikeOut(boolean value) {#setStrikeOut-boolean-}
```
public void setStrikeOut(boolean value)
```


Sets strikeout for the text, represented by the  TextFragment  object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets background color of the text.

--------------------

Note that the value is not preserved as a text characteristic within the document. The BackgroundColor property getter works for an object in case it was explicitly set previously with BackgroundColor setter for those object. The property is used by runtime in context of current generation/modification process.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color value
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public void setBackgroundColor(Color value)
```


Sets background color of the text.

--------------------

Note that the value is not preserved as a text characteristic within the document. The BackgroundColor property getter works for an object in case it was explicitly set previously with BackgroundColor setter for those object. The property is used by runtime in context of current generation/modification process.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color value |

### getFontStyle() {#getFontStyle--}
```
public int getFontStyle()
```


Sets font style of the text.

**Returns:**
int - FontStyles element
### setFontStyle(int value) {#setFontStyle-int-}
```
public void setFontStyle(int value)
```


Sets font style of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | FontStyles value |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```


Gets horizontal alignment for the text.

--------------------

HorizontalAlignment.None is equal to HorizontalAlignment.Left. Note that TextState.HorizontalAlignment property works in new document generation scenarios only.

**Returns:**
[HorizontalAlignment](../../com.aspose.pdf/horizontalalignment) - HorizontalAlignment value
### setHorizontalAlignment(HorizontalAlignment value) {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
```
public void setHorizontalAlignment(HorizontalAlignment value)
```


Sets horizontal alignment for the text.

--------------------

HorizontalAlignment.None is equal to HorizontalAlignment.Left. Note that TextState.HorizontalAlignment property works in new document generation scenarios only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HorizontalAlignment](../../com.aspose.pdf/horizontalalignment) | HorizontalAlignment value |

### measureString(String str, boolean insideLine) {#measureString-java.lang.String-boolean-}
```
public double measureString(String str, boolean insideLine)
```


Measures the string.

--------------------

insideLine indicate that the string is not ending. in case part of the whole string is measured - the insideLine should be true. in case the whole string is measured the insideLine should be false. in other words: in case insideLine = true only character widths are taken into account. no additional transformations are taken into account in case insideLine = false end of the string is handled properly - italic transformation is taken into account.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String | String value |
| insideLine | boolean | boolean value |

**Returns:**
double - double value
### measureString(String str) {#measureString-java.lang.String-}
```
public double measureString(String str)
```


Measures the string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String | The string. |

**Returns:**
double - Width of the string represented with this text state.
### measureHeight(char character) {#measureHeight-char-}
```
public double measureHeight(char character)
```


Measures character height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| character | char | Character to measure. |

**Returns:**
double - Height of the character if we could get it from font; otherwise 0.
### calculateFontSize(String str, Rectangle rect) {#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-}
```
public double calculateFontSize(String str, Rectangle rect)
```


Calculates the font size for the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String | String value |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |

**Returns:**
double - double value
