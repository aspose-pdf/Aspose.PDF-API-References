---
title: TextState
linktitle: TextState
second_title: Aspose.PDF for Java API Reference
description: Represents a text state of a text
type: docs
weight: 5340
url: /java/com.aspose.pdf/textstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState

```
public class TextState extends Object
```

Represents a text state of a text

## Fields

| Field | Description |
| --- | --- |
| [TabstopDefaultValue](#TabstopDefaultValue) | Default value of tabulation in widths of space character of default font. |

## Constructors

| Constructor | Description |
| --- | --- |
| [TextState](#TextState--) | Creates text state object. |
| [TextState](#TextState-java.awt.Color-) | Creates text state object. |
| [TextState](#TextState-java.awt.Color-double-) | Creates text state object. |
| [TextState](#TextState-double-) | Creates text state object with font size specification. |
| [TextState](#TextState-java.lang.String-) | Creates text state object. |
| [TextState](#TextState-java.lang.String-boolean-boolean-) | Creates text state object. |
| [TextState](#TextState-java.lang.String-double-) | Creates text state object. |

## Methods

| Method | Description |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> Applies settings from another textState </p> <hr> <p> Only those properties will be copied that were changed explicitly. </p> |
| [calculateFontSize](#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-) | Calculates the font size for the rectangle. |
| [getBackgroundColor](#getBackgroundColor--) | <p> Gets background color of the text. </p> <hr> <p> Note that the value is not preserved as a text characteristic within the document. The BackgroundColor property getter works for an object in case it was explicitly set previously with BackgroundColor setter for those object. The property is used by runtime in context of current generation/modification process. </p> |
| [getCharacterSpacing](#getCharacterSpacing--) | Gets character spacing of the text. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | Gets or sets text CoordinateOrigin. If CoordinateOrigin is Descender, the text Y coordinate corresponds to the font's lowest point. If CoordinateOrigin is BaseLine, the text Y coordinate corresponds to the font's baseline. The default value is Descender. If the font's Descent value is too big, text can be rendered higher than other fonts. In this case, CoordinateOrigin BaseLine can be selected for better text rendering. |
| [getFont](#getFont--) | Gets font of the text. |
| [getfontSize](#getfontSize--) | Represent getfontSize method |
| [getFontSize](#getFontSize--) | Gets font size of the text. |
| [getFontStyle](#getFontStyle--) | Sets font style of the text. |
| [getForegroundColor](#getForegroundColor--) | Gets foreground color of the text. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> Gets horizontal alignment for the text. </p> <hr> <p> HorizontalAlignment.None is equal to HorizontalAlignment.Left. Note that TextState.HorizontalAlignment property works in new document generation scenarios only. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | Gets horizontal scaling of the text. |
| [getLineSpacing](#getLineSpacing--) | <p> Gets line spacing of the text. </p> |
| [getRenderingMode](#getRenderingMode--) | Gets or sets rendering mode of text. |
| [getStrokingColor](#getStrokingColor--) | Gets or sets foreground color of the text. |
| [getTabTag](#getTabTag--) | <p> You can place this tag in text to declare tabulation. </p> <hr> <p> It has effect only in couple with {@code TabStops}. </p> |
| [getTextHeight](#getTextHeight--) | Gets text height. |
| [getWordSpacing](#getWordSpacing--) | Gets word spacing of the text. |
| [isInvisible](#isInvisible--) | Gets the invisibility of text. This basically reflects the {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}) state, except for some special cases (like clipping). |
| [isStrikeOut](#isStrikeOut--) | Gets strikeout for the text, represented by the {@code TextFragment} object |
| [isSubscript](#isSubscript--) | Gets or sets subscript of the text. |
| [isSuperscript](#isSuperscript--) | Gets superscript of the text. |
| [isUnderline](#isUnderline--) | Gets underline for the text, represented by the {@code TextFragment} object |
| [measureHeight](#measureHeight-char-) | Measures character height. |
| [measureString](#measureString-java.lang.String-) | Measures the string. |
| [measureString](#measureString-java.lang.String-boolean-) | <p> Measures the string. </p> <hr> <p> insideLine indicate that the string is not ending. in case part of the whole string is measured - the insideLine should be true. in case the whole string is measured the insideLine should be false. in other words: in case insideLine = true only character widths are taken into account. no additional transformations are taken into account in case insideLine = false end of the string is handled properly - italic transformation is taken into account. </p> |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Sets background color of the text. |
| [setCharacterSpacing](#setCharacterSpacing-float-) | Sets character spacing of the text. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | Gets or sets text CoordinateOrigin. If CoordinateOrigin is Descender, the text Y coordinate corresponds to the font's lowest point. If CoordinateOrigin is BaseLine, the text Y coordinate corresponds to the font's baseline. The default value is Descender. If the font's Descent value is too big, text can be rendered higher than other fonts. In this case, CoordinateOrigin BaseLine can be selected for better text rendering. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Gets font of the text. |
| [setFontSize](#setFontSize-float-) | Sets font size of the text. |
| [setFontSizeSuppressedUpdate](#setFontSizeSuppressedUpdate-float-) | Sets font size of the text wish suppressed update. |
| [setFontStyle](#setFontStyle-int-) | Sets font style of the text. |
| [setFontSuppressedUpdate](#setFontSuppressedUpdate-com.aspose.pdf.Font-) | Gets font of the text wish suppressed update. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Sets foreground color of the text. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> Sets horizontal alignment for the text. </p> <hr> <p> HorizontalAlignment.None is equal to HorizontalAlignment.Left. Note that TextState.HorizontalAlignment property works in new document generation scenarios only. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | Sets horizontal scaling of the text. |
| [setInvisible](#setInvisible-boolean-) | Sets the invisibility of text. This basically reflects the {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}) state, except for some special cases (like clipping). |
| [setLineSpacing](#setLineSpacing-float-) | <p> Sets line spacing of the text. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | Gets or sets rendering mode of text. |
| [setStrikeOut](#setStrikeOut-boolean-) | Sets strikeout for the text, represented by the {@code TextFragment} object |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | Gets or sets foreground color of the text. |
| [setSubscript](#setSubscript-boolean-) | Gets or sets subscript of the text. |
| [setSuperscript](#setSuperscript-boolean-) | Sets superscript of the text. |
| [setUnderline](#setUnderline-boolean-) | Sets underline for the text, represented by the {@code TextFragment} object |
| [setWordSpacing](#setWordSpacing-float-) | Sets word spacing of the text. |

### TabstopDefaultValue {#TabstopDefaultValue}
```
public final float TabstopDefaultValue
```

Default value of tabulation in widths of space character of default font.

### TextState {#TextState--}
```
public TextState()
```

Creates text state object.

### TextState {#TextState-java.awt.Color-}
Creates text state object.

### TextState {#TextState-java.awt.Color-double-}
Creates text state object.

### TextState {#TextState-double-}
```
public TextState(double fontSize)
```

Creates text state object with font size specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontSize |  | Font size. |

### TextState {#TextState-java.lang.String-}
Creates text state object.

### TextState {#TextState-java.lang.String-boolean-boolean-}
Creates text state object.

### TextState {#TextState-java.lang.String-double-}
Creates text state object.

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> Applies settings from another textState </p> <hr> <p> Only those properties will be copied that were changed explicitly. </p>

### calculateFontSize {#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-}
Calculates the font size for the rectangle.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

<p> Gets background color of the text. </p> <hr> <p> Note that the value is not preserved as a text characteristic within the document. The BackgroundColor property getter works for an object in case it was explicitly set previously with BackgroundColor setter for those object. The property is used by runtime in context of current generation/modification process. </p>

**Returns:**
Color value

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

Gets character spacing of the text.

**Returns:**
float value

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

Gets or sets text CoordinateOrigin. If CoordinateOrigin is Descender, the text Y coordinate corresponds to the font's lowest point. If CoordinateOrigin is BaseLine, the text Y coordinate corresponds to the font's baseline. The default value is Descender. If the font's Descent value is too big, text can be rendered higher than other fonts. In this case, CoordinateOrigin BaseLine can be selected for better text rendering.

**Returns:**
CoordinateOrigin element

### getFont {#getFont--}
```
public Font getFont()
```

Gets font of the text.

**Returns:**
Font object

### getfontSize {#getfontSize--}
```
public float getfontSize()
```

Represent getfontSize method

**Returns:**
float value

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Gets font size of the text.

**Returns:**
float value

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

Sets font style of the text.

**Returns:**
FontStyles element @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

Gets foreground color of the text.

**Returns:**
Color value

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> Gets horizontal alignment for the text. </p> <hr> <p> HorizontalAlignment.None is equal to HorizontalAlignment.Left. Note that TextState.HorizontalAlignment property works in new document generation scenarios only. </p>

**Returns:**
HorizontalAlignment value @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

Gets horizontal scaling of the text.

**Returns:**
float value

### getLineSpacing {#getLineSpacing--}
```
public float getLineSpacing()
```

<p> Gets line spacing of the text. </p>

**Returns:**
float value <hr> <p> Note that the value is not preserved as a text characteristic within the document. The LineSpacing property getter works for an object in case it was explicitly set previously with LineSpacing setter for those object. The property is used by runtime in context of current generation/modification process. </p>

### getRenderingMode {#getRenderingMode--}
```
public TextRenderingMode getRenderingMode()
```

Gets or sets rendering mode of text.

**Returns:**
TextRenderingMode element @see TextRenderingMode

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

Gets or sets foreground color of the text.

**Returns:**
Color instance

### getTabTag {#getTabTag--}
```
public final String getTabTag()
```

<p> You can place this tag in text to declare tabulation. </p> <hr> <p> It has effect only in couple with {@code TabStops}. </p>

**Returns:**
String value "#$TAB"

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

Gets text height.

**Returns:**
float value

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

Gets word spacing of the text.

**Returns:**
float value

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

Gets the invisibility of text. This basically reflects the {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}) state, except for some special cases (like clipping).

**Returns:**
boolean value

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

Gets strikeout for the text, represented by the {@code TextFragment} object

**Returns:**
boolean value

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

Gets or sets subscript of the text.

**Returns:**
boolean value

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

Gets superscript of the text.

**Returns:**
boolean value

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

Gets underline for the text, represented by the {@code TextFragment} object

**Returns:**
boolean value

### measureHeight {#measureHeight-char-}
```
public double measureHeight(char character)
```

Measures character height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| character |  | Character to measure. |

**Returns:**
Height of the character if we could get it from font; otherwise 0.

### measureString {#measureString-java.lang.String-}
Measures the string.

### measureString {#measureString-java.lang.String-boolean-}
<p> Measures the string. </p> <hr> <p> insideLine indicate that the string is not ending. in case part of the whole string is measured - the insideLine should be true. in case the whole string is measured the insideLine should be false. in other words: in case insideLine = true only character widths are taken into account. no additional transformations are taken into account in case insideLine = false end of the string is handled properly - italic transformation is taken into account. </p>

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Sets background color of the text.

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

Sets character spacing of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
Gets or sets text CoordinateOrigin. If CoordinateOrigin is Descender, the text Y coordinate corresponds to the font's lowest point. If CoordinateOrigin is BaseLine, the text Y coordinate corresponds to the font's baseline. The default value is Descender. If the font's Descent value is too big, text can be rendered higher than other fonts. In this case, CoordinateOrigin BaseLine can be selected for better text rendering.

### setFont {#setFont-com.aspose.pdf.Font-}
Gets font of the text.

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Sets font size of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setFontSizeSuppressedUpdate {#setFontSizeSuppressedUpdate-float-}
```
public void setFontSizeSuppressedUpdate(float value)
```

Sets font size of the text wish suppressed update.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

Sets font style of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | FontStyles value @see FontStyles |

### setFontSuppressedUpdate {#setFontSuppressedUpdate-com.aspose.pdf.Font-}
Gets font of the text wish suppressed update.

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Sets foreground color of the text.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> Sets horizontal alignment for the text. </p> <hr> <p> HorizontalAlignment.None is equal to HorizontalAlignment.Left. Note that TextState.HorizontalAlignment property works in new document generation scenarios only. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

Sets horizontal scaling of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

Sets the invisibility of text. This basically reflects the {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}) state, except for some special cases (like clipping).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setLineSpacing {#setLineSpacing-float-}
```
public void setLineSpacing(float value)
```

<p> Sets line spacing of the text. </p>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value <hr> <p> Note that the value is not preserved as a text characteristic within the document. The LineSpacing property getter works for an object in case it was explicitly set previously with LineSpacing setter for those object. The property is used by runtime in context of current generation/modification process. </p> |

### setRenderingMode {#setRenderingMode-com.aspose.pdf.TextRenderingMode-}
Gets or sets rendering mode of text.

### setStrikeOut {#setStrikeOut-boolean-}
```
public void setStrikeOut(boolean value)
```

Sets strikeout for the text, represented by the {@code TextFragment} object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setStrokingColor {#setStrokingColor-com.aspose.pdf.Color-}
Gets or sets foreground color of the text.

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

Gets or sets subscript of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

Sets superscript of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setUnderline {#setUnderline-boolean-}
```
public void setUnderline(boolean value)
```

Sets underline for the text, represented by the {@code TextFragment} object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setWordSpacing {#setWordSpacing-float-}
```
public void setWordSpacing(float value)
```

Sets word spacing of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |
