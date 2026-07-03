---
title: TextFragmentState
second_title: Aspose.PDF for Java API Reference
description: <p> Represents a text state of a text fragment. </p> <hr> <pre> The example demonstrates how to change text color and font size of the text with {@code TextState} object. // Open.
type: docs
weight: 5150
url: /java/com.aspose.pdf/textfragmentstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState com.aspose.pdf.TextFragmentState, com.aspose.pdf.TextState, com.aspose.pdf.TextFragmentState

```
public final class TextFragmentState extends TextState
```

<p> Represents a text state of a text fragment. </p> <hr> <pre> The example demonstrates how to change text color and font size of the text with {@code TextState} object. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Provides a way to change following properties of the text: font ({@code TextFragmentState.Font} property) font size ({@code TextFragmentState.FontSize} property) font style ( {@code TextFragmentState.FontStyle} property) foreground color ( {@code TextFragmentState.ForegroundColor} property) background color ( {@code TextFragmentState.BackgroundColor} property) <p> Note that changing {@code TextFragmentState} properties may change inner {@code TextFragment.Segments} collection because TextFragment is an aggregate object and it may rearrange internal segments or merge them into single segment. If your requirement is to leave the {@code TextFragment.Segments} collection unchanged, please change inner segments individually. </p> @see TextFragmentAbsorber @see IDocument

## Constructors

| Constructor | Description |
| --- | --- |
| [TextFragmentState](#TextFragmentState-com.aspose.pdf.TextFragment-) | Initializes new instance of the {@code TextFragmentState} object with specified {@code TextFragment} object. This {@code TextFragmentState} initialization is not supported. TextFragmentState is only available with {@code TextFragment.TextState} property. |

## Methods

| Method | Description |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> Applies settings from another textState </p> |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-boolean-) | Applies settings from another textState |
| [getBackgroundColor](#getBackgroundColor--) | Sets background color of the text, represented by the {@code TextFragment} object |
| [getCharacterSpacing](#getCharacterSpacing--) | Gets character spacing of the text, represented by the {@code TextFragment} object. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | Gets or sets text CoordinateOrigin. If CoordinateOrigin is Descender, the text Y coordinate corresponds to the font's lowest point. If CoordinateOrigin is BaseLine, the text Y coordinate corresponds to the font's baseline. The default value is Descender. If the font's Descent value is too big, text can be rendered higher than other fonts. In this case, CoordinateOrigin BaseLine can be selected for better text rendering. |
| [getDrawTextRectangleBorder](#getDrawTextRectangleBorder--) | Gets if text rectangle border drawn flag. |
| [getFont](#getFont--) | Gets font of the text, represented by the {@code TextFragment} object |
| [getFontSize](#getFontSize--) | Gets font size of the text, represented by the {@code TextFragment} object |
| [getFontStyle](#getFontStyle--) | Sets font style of the text, represented by the {@code TextFragment} object |
| [getForegroundColor](#getForegroundColor--) | Gets foreground color of the text, represented by the {@code TextFragment} object |
| [getFormattingOptions](#getFormattingOptions--) | Gets or sets formatting options. Setting of the options will be effective in generator scenarios only. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> Gets horizontal alignment for the text. </p> <hr> <p> HorizontalAlignment.None is equal to HorizontalAlignment.Left. Note that TextFragmentState.VerticalAlignment property works in new document generation scenarios only. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | Gets horizontal scaling of the text, represented by the {@code TextFragment} object. |
| [getLineSpacing](#getLineSpacing--) | <p> Gets line spacing of the text. </p> |
| [getRenderingMode](#getRenderingMode--) | Gets or sets rendering mode of the text. |
| [getRotation](#getRotation--) | Gets or sets rotation angle in degrees. |
| [getStrokingColor](#getStrokingColor--) | Gets or sets color stroking operations of {@code TextFragment} rendering (stroke text, rectangle border) |
| [getTabStops](#getTabStops--) | <p> Gets tabstops for the text. </p> <hr> <p> Note that Tabstops property works in new document generation scenarios only. Tabstops may be added during {@code TextFragment} initialization. Tabstops must be constructed before the text. </p> |
| [getTextHeight](#getTextHeight--) | Gets text height, represented by the {@code TextFragment} object |
| [getWordSpacing](#getWordSpacing--) | Gets word spacing of the text. |
| [isFitRectangle](#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-) | Checks if input string could be placed inside defined rectangle. |
| [isInvisible](#isInvisible--) | Gets invisibility of the text. |
| [isStrikeOut](#isStrikeOut--) | Gets or sets strikeout for the text, represented by the {@link TextFragment} object |
| [isSubscript](#isSubscript--) | Gets or sets subscript of the text, represented by the {@code TextFragment} object. |
| [isSuperscript](#isSuperscript--) | Gets or sets superscript of the text, represented by the {@code TextFragment} object. |
| [isUnderline](#isUnderline--) | Gets or sets underline for the text, represented by the {@link TextFragment} object |
| [measureHeight](#measureHeight-char-) | Measures character height. |
| [measureString](#measureString-java.lang.String-) | Measures the string. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Sets background color of the text, represented by the TextFragment object |
| [setCharacterSpacing](#setCharacterSpacing-float-) | Sets character spacing of the text, represented by the {@code TextFragment} object. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | Gets or sets text CoordinateOrigin. If CoordinateOrigin is Descender, the text Y coordinate corresponds to the font's lowest point. If CoordinateOrigin is BaseLine, the text Y coordinate corresponds to the font's baseline. The default value is Descender. If the font's Descent value is too big, text can be rendered higher than other fonts. In this case, CoordinateOrigin BaseLine can be selected for better text rendering. |
| [setDrawTextRectangleBorder](#setDrawTextRectangleBorder-boolean-) | Sets if text rectangle border drawn flag. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Sets font of the text, represented by the {@code TextFragment} object |
| [setFontSize](#setFontSize-float-) | Sets font size of the text, represented by the {@code TextFragment} object |
| [setFontStyle](#setFontStyle-int-) | Sets font style of the text, represented by the {@link TextFragment} object |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Sets foreground color of the text, represented by the {@code TextFragment} object |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Gets or sets formatting options. Setting of the options will be effective in generator scenarios only. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> Sets horizontal alignment for the text. </p> <hr> <p> HorizontalAlignment.None is equal to HorizontalAlignment.Left. Note that TextFragmentState.VerticalAlignment property works in new document generation scenarios only. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | Sets horizontal scaling of the text, represented by the {@code TextFragment} object. |
| [setInvisible](#setInvisible-boolean-) | Sets invisibility of the text. |
| [setLineSpacing](#setLineSpacing-float-) | <p> Sets line spacing of the text. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | Gets or sets rendering mode of the text. |
| [setRotation](#setRotation-double-) | Gets or sets rotation angle in degrees. |
| [setStrikeOut](#setStrikeOut-boolean-) | Sets strikeout for the text, represented by the {@code TextFragment} object |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | Gets or sets color stroking operations of {@code TextFragment} rendering (stroke text, rectangle border) |
| [setSubscript](#setSubscript-boolean-) | Gets or sets subscript of the text, represented by the {@code TextFragment} object. |
| [setSuperscript](#setSuperscript-boolean-) | Gets or sets superscript of the text, represented by the {@code TextFragment} object. |
| [setUnderline](#setUnderline-boolean-) | Sets underline for the text, represented by the {@code TextFragment} object |
| [setWordSpacing](#setWordSpacing-float-) | Sets word spacing of the text. |

### TextFragmentState {#TextFragmentState-com.aspose.pdf.TextFragment-}
Initializes new instance of the {@code TextFragmentState} object with specified {@code TextFragment} object. This {@code TextFragmentState} initialization is not supported. TextFragmentState is only available with {@code TextFragment.TextState} property.

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> Applies settings from another textState </p>

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-boolean-}
Applies settings from another textState

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Sets background color of the text, represented by the {@code TextFragment} object

**Returns:**
value Color object

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

Gets character spacing of the text, represented by the {@code TextFragment} object.

**Returns:**
float value

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

Gets or sets text CoordinateOrigin. If CoordinateOrigin is Descender, the text Y coordinate corresponds to the font's lowest point. If CoordinateOrigin is BaseLine, the text Y coordinate corresponds to the font's baseline. The default value is Descender. If the font's Descent value is too big, text can be rendered higher than other fonts. In this case, CoordinateOrigin BaseLine can be selected for better text rendering.

**Returns:**
CoordinateOrigin element

### getDrawTextRectangleBorder {#getDrawTextRectangleBorder--}
```
public boolean getDrawTextRectangleBorder()
```

Gets if text rectangle border drawn flag.

**Returns:**
boolean value

### getFont {#getFont--}
```
public Font getFont()
```

Gets font of the text, represented by the {@code TextFragment} object

**Returns:**
Font value

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Gets font size of the text, represented by the {@code TextFragment} object

**Returns:**
float value

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

Sets font style of the text, represented by the {@code TextFragment} object

**Returns:**
FontStyles element @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

Gets foreground color of the text, represented by the {@code TextFragment} object

**Returns:**
Color object

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

Gets or sets formatting options. Setting of the options will be effective in generator scenarios only.

**Returns:**
TextFormattingOptions instance

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> Gets horizontal alignment for the text. </p> <hr> <p> HorizontalAlignment.None is equal to HorizontalAlignment.Left. Note that TextFragmentState.VerticalAlignment property works in new document generation scenarios only. </p>

**Returns:**
HorizontalAlignment value @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

Gets horizontal scaling of the text, represented by the {@code TextFragment} object.

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

Gets or sets rendering mode of the text.

**Returns:**
TextRenderingMode element

### getRotation {#getRotation--}
```
public double getRotation()
```

Gets or sets rotation angle in degrees.

**Returns:**
double value

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

Gets or sets color stroking operations of {@code TextFragment} rendering (stroke text, rectangle border)

**Returns:**
Color instance

### getTabStops {#getTabStops--}
```
public TabStops getTabStops()
```

<p> Gets tabstops for the text. </p> <hr> <p> Note that Tabstops property works in new document generation scenarios only. Tabstops may be added during {@code TextFragment} initialization. Tabstops must be constructed before the text. </p>

**Returns:**
TabStops object

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

Gets text height, represented by the {@code TextFragment} object

**Returns:**
float value

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

Gets word spacing of the text.

**Returns:**
float value

### isFitRectangle {#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-}
Checks if input string could be placed inside defined rectangle.

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

Gets invisibility of the text.

**Returns:**
boolean value

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

Gets or sets strikeout for the text, represented by the {@link TextFragment} object

**Returns:**
boolean value

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

Gets or sets subscript of the text, represented by the {@code TextFragment} object.

**Returns:**
boolean value

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

Gets or sets superscript of the text, represented by the {@code TextFragment} object.

**Returns:**
value boolean value

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

Gets or sets underline for the text, represented by the {@link TextFragment} object

**Returns:**
boolean value

### measureHeight {#measureHeight-char-}
```
public final double measureHeight(char character)
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

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Sets background color of the text, represented by the TextFragment object

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

Sets character spacing of the text, represented by the {@code TextFragment} object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
Gets or sets text CoordinateOrigin. If CoordinateOrigin is Descender, the text Y coordinate corresponds to the font's lowest point. If CoordinateOrigin is BaseLine, the text Y coordinate corresponds to the font's baseline. The default value is Descender. If the font's Descent value is too big, text can be rendered higher than other fonts. In this case, CoordinateOrigin BaseLine can be selected for better text rendering.

### setDrawTextRectangleBorder {#setDrawTextRectangleBorder-boolean-}
```
public void setDrawTextRectangleBorder(boolean value)
```

Sets if text rectangle border drawn flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setFont {#setFont-com.aspose.pdf.Font-}
Sets font of the text, represented by the {@code TextFragment} object

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Sets font size of the text, represented by the {@code TextFragment} object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

Sets font style of the text, represented by the {@link TextFragment} object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value @see FontStyles |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Sets foreground color of the text, represented by the {@code TextFragment} object

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
Gets or sets formatting options. Setting of the options will be effective in generator scenarios only.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> Sets horizontal alignment for the text. </p> <hr> <p> HorizontalAlignment.None is equal to HorizontalAlignment.Left. Note that TextFragmentState.VerticalAlignment property works in new document generation scenarios only. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

Sets horizontal scaling of the text, represented by the {@code TextFragment} object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

Sets invisibility of the text.

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
Gets or sets rendering mode of the text.

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Gets or sets rotation angle in degrees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

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
Gets or sets color stroking operations of {@code TextFragment} rendering (stroke text, rectangle border)

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

Gets or sets subscript of the text, represented by the {@code TextFragment} object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

Gets or sets superscript of the text, represented by the {@code TextFragment} object.

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
