---
title: TextStamp
second_title: Aspose.PDF for Java API Reference
description: Reresents textual stamp.
type: docs
weight: 5320
url: /java/com.aspose.pdf/textstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp

```
public class TextStamp extends Stamp
```

Reresents textual stamp.

## Constructors

| Constructor | Description |
| --- | --- |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-) | Initializes a new instance of the {@code TextStamp} class with formattedText object |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-) | Initializes a new instance of the {@code TextStamp} class with formattedText object |
| [TextStamp](#TextStamp-java.lang.String-) | Initializes a new instance of the {@code TextStamp} class. |
| [TextStamp](#TextStamp-java.lang.String-com.aspose.pdf.TextState-) | Initializes a new instance of the TextStamp class. |

## Methods

| Method | Description |
| --- | --- |
| [getAutoAdjustFontSizePrecision](#getAutoAdjustFontSizePrecision--) | Automatically adjust font size precision. Default value: 0.1; |
| [getAutoAdjustFontSizeToFitStampRectangle](#getAutoAdjustFontSizeToFitStampRectangle--) | If enabled, the font size will be automatically adjusted to fit the stamp rectangle of size: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) and {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). Default width and height are derived from the page rectangle. |
| [getDefaultFont](#getDefaultFont--) | Returns default font |
| [getDefaultFontSize](#getDefaultFontSize--) | Default Font Size |
| [getDraw](#getDraw--) | This property determines how stamp is drawn on page. If Draw = true stamp is drawn as graphic operators and if draw = false then stamp is drawn as text. |
| [getFontSize](#getFontSize--) | Actual font size after the stamp has been placed. (May differ from the initial font size provided through the constructor if the 'AutoAdjustFontSizeToFitStampRectangle' option is enabled.) |
| [getHeight](#getHeight--) | Desired height of the stamp on the page. |
| [getMaxRowWidth](#getMaxRowWidth--) | Max row height for WordWrap option. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Gets or sets mode that defines behavior in case fonts don't contain requested characters. |
| [getReplacementFont](#getReplacementFont--) | Gets or sets font used for replacing if user font does not contain required character. |
| [getTextAlignment](#getTextAlignment--) | Alignment of the text inside the stamp. |
| [getTextState](#getTextState--) | Gets text properties of the stamp. See {@code TextState} for details. |
| [getTreatYIndentAsBaseLine](#getTreatYIndentAsBaseLine--) | Defines coordinate origin for placing text. If TreatYIndentAsBaseLine = true (default when Draw = true) YIndent value will be treated as text base line. If TreatYIndentAsBaseLine = false (default when Draw = false) YIndent value will be treated as bottom (descent line) of text. |
| [getValue](#getValue--) | Gets string value which is used as stamp on the page. |
| [getWidth](#getWidth--) | Desired width of the stamp on the page. |
| [getWordWrapMode](#getWordWrapMode--) | Gets or sets the word wrap mode for text rendering. |
| [isJustify](#isJustify--) | Defines text justification. If this property is set to true, both left and right edges of the text are aligned. Default value: false. |
| [isScale](#isScale--) | Defines scaling of the text. If this property is set to true and Width value specified, text will be scaled in order to fit to specified width. |
| [isWordWrap](#isWordWrap--) | Defines word wrap. If this property set to true and Width value specified, text will be broken in the several lines to fit into specified width. Default value: false. |
| [put](#put-com.aspose.pdf.Page-) | Adds textual stamp on the page. |
| [setAutoAdjustFontSizePrecision](#setAutoAdjustFontSizePrecision-float-) | Automatically adjust font size precision. Default value: 0.1; |
| [setAutoAdjustFontSizeToFitStampRectangle](#setAutoAdjustFontSizeToFitStampRectangle-boolean-) | If enabled, the font size will be automatically adjusted to fit the stamp rectangle of size: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) and {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). Default width and height are derived from the page rectangle. |
| [setDraw](#setDraw-boolean-) | This property determines how stamp is drawn on page. If Draw = true stamp is drawn as graphic operators and if draw = false then stamp is drawn as text. |
| [setHeight](#setHeight-double-) | Desired height of the stamp on the page. |
| [setJustify](#setJustify-boolean-) | Defines text justification. If this property is set to true, both left and right edges of the text are aligned. Default value: false. |
| [setMaxRowWidth](#setMaxRowWidth-double-) | Max row height for WordWrap option. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-int-) | Gets or sets mode that defines behavior in case fonts don't contain requested characters. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | Gets or sets font used for replacing if user font does not contain required character. |
| [setScale](#setScale-boolean-) | Defines scaling of the text. If this property is set to true and Width value specified, text will be scaled in order to fit to specified width. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Alignment of the text inside the stamp. |
| [setTreatYIndentAsBaseLine](#setTreatYIndentAsBaseLine-boolean-) | Defines coordinate origin for placing text. If TreatYIndentAsBaseLine = true (default when Draw = true) YIndent value will be treated as text base line. If TreatYIndentAsBaseLine = false (default when Draw = false) YIndent value will be treated as bottom (descent line) of text. |
| [setValue](#setValue-java.lang.String-) | Sets string value which is used as stamp on the page. |
| [setWidth](#setWidth-double-) | Desired width of the stamp on the page. |
| [setWordWrap](#setWordWrap-boolean-) | Defines word wrap. If this property set to true and Width value specified, text will be broken in the several lines to fit into specified width. Default value: false. |
| [setWordWrapMode](#setWordWrapMode-int-) | Gets or sets the word wrap mode for text rendering. |

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-}
Initializes a new instance of the {@code TextStamp} class with formattedText object

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-}
Initializes a new instance of the {@code TextStamp} class with formattedText object

### TextStamp {#TextStamp-java.lang.String-}
Initializes a new instance of the {@code TextStamp} class.

### TextStamp {#TextStamp-java.lang.String-com.aspose.pdf.TextState-}
Initializes a new instance of the TextStamp class.

### getAutoAdjustFontSizePrecision {#getAutoAdjustFontSizePrecision--}
```
public final float getAutoAdjustFontSizePrecision()
```

Automatically adjust font size precision. Default value: 0.1;

**Returns:**
float value

### getAutoAdjustFontSizeToFitStampRectangle {#getAutoAdjustFontSizeToFitStampRectangle--}
```
public final boolean getAutoAdjustFontSizeToFitStampRectangle()
```

If enabled, the font size will be automatically adjusted to fit the stamp rectangle of size: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) and {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). Default width and height are derived from the page rectangle.

**Returns:**
boolean value

### getDefaultFont {#getDefaultFont--}
```
public static Font getDefaultFont()
```

Returns default font

**Returns:**
com.aspose.pdf.Font object

### getDefaultFontSize {#getDefaultFontSize--}
```
public static float getDefaultFontSize()
```

Default Font Size

**Returns:**
float value

### getDraw {#getDraw--}
```
public boolean getDraw()
```

This property determines how stamp is drawn on page. If Draw = true stamp is drawn as graphic operators and if draw = false then stamp is drawn as text.

**Returns:**
boolean value

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

Actual font size after the stamp has been placed. (May differ from the initial font size provided through the constructor if the 'AutoAdjustFontSizeToFitStampRectangle' option is enabled.)

**Returns:**
float value

### getHeight {#getHeight--}
```
public double getHeight()
```

Desired height of the stamp on the page.

**Returns:**
double value

### getMaxRowWidth {#getMaxRowWidth--}
```
public double getMaxRowWidth()
```

Max row height for WordWrap option.

**Returns:**
double value

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public final int getNoCharacterBehavior()
```

Gets or sets mode that defines behavior in case fonts don't contain requested characters.

**Returns:**
NoCharacterAction element

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

Gets or sets font used for replacing if user font does not contain required character.

**Returns:**
Font instance

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

Alignment of the text inside the stamp.

**Returns:**
HorizontalAlignment value @see HorizontalAlignment

### getTextState {#getTextState--}
```
public TextState getTextState()
```

Gets text properties of the stamp. See {@code TextState} for details.

**Returns:**
TextState element

### getTreatYIndentAsBaseLine {#getTreatYIndentAsBaseLine--}
```
public boolean getTreatYIndentAsBaseLine()
```

Defines coordinate origin for placing text. If TreatYIndentAsBaseLine = true (default when Draw = true) YIndent value will be treated as text base line. If TreatYIndentAsBaseLine = false (default when Draw = false) YIndent value will be treated as bottom (descent line) of text.

**Returns:**
boolean value

### getValue {#getValue--}
```
public String getValue()
```

Gets string value which is used as stamp on the page.

**Returns:**
String value

### getWidth {#getWidth--}
```
public double getWidth()
```

Desired width of the stamp on the page.

**Returns:**
double value

### getWordWrapMode {#getWordWrapMode--}
```
public final int getWordWrapMode()
```

Gets or sets the word wrap mode for text rendering.

**Returns:**
WordWrapMode element

### isJustify {#isJustify--}
```
public boolean isJustify()
```

Defines text justification. If this property is set to true, both left and right edges of the text are aligned. Default value: false.

**Returns:**
boolean value

### isScale {#isScale--}
```
public boolean isScale()
```

Defines scaling of the text. If this property is set to true and Width value specified, text will be scaled in order to fit to specified width.

**Returns:**
boolean value

### isWordWrap {#isWordWrap--}
```
@Deprecated public boolean isWordWrap()
```

Defines word wrap. If this property set to true and Width value specified, text will be broken in the several lines to fit into specified width. Default value: false.

**Returns:**
boolean value @deprecated "Use WordWrapMode instead."

### put {#put-com.aspose.pdf.Page-}
Adds textual stamp on the page.

### setAutoAdjustFontSizePrecision {#setAutoAdjustFontSizePrecision-float-}
```
public final void setAutoAdjustFontSizePrecision(float value)
```

Automatically adjust font size precision. Default value: 0.1;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setAutoAdjustFontSizeToFitStampRectangle {#setAutoAdjustFontSizeToFitStampRectangle-boolean-}
```
public final void setAutoAdjustFontSizeToFitStampRectangle(boolean value)
```

If enabled, the font size will be automatically adjusted to fit the stamp rectangle of size: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) and {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). Default width and height are derived from the page rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setDraw {#setDraw-boolean-}
```
public void setDraw(boolean value)
```

This property determines how stamp is drawn on page. If Draw = true stamp is drawn as graphic operators and if draw = false then stamp is drawn as text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Desired height of the stamp on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

Defines text justification. If this property is set to true, both left and right edges of the text are aligned. Default value: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setMaxRowWidth {#setMaxRowWidth-double-}
```
public void setMaxRowWidth(double value)
```

Max row height for WordWrap option.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setNoCharacterBehavior {#setNoCharacterBehavior-int-}
```
public final void setNoCharacterBehavior(int value)
```

Gets or sets mode that defines behavior in case fonts don't contain requested characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | NoCharacterAction element |

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
Gets or sets font used for replacing if user font does not contain required character.

### setScale {#setScale-boolean-}
```
public void setScale(boolean value)
```

Defines scaling of the text. If this property is set to true and Width value specified, text will be scaled in order to fit to specified width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
Alignment of the text inside the stamp.

### setTreatYIndentAsBaseLine {#setTreatYIndentAsBaseLine-boolean-}
```
public void setTreatYIndentAsBaseLine(boolean value)
```

Defines coordinate origin for placing text. If TreatYIndentAsBaseLine = true (default when Draw = true) YIndent value will be treated as text base line. If TreatYIndentAsBaseLine = false (default when Draw = false) YIndent value will be treated as bottom (descent line) of text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setValue {#setValue-java.lang.String-}
Sets string value which is used as stamp on the page.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Desired width of the stamp on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setWordWrap {#setWordWrap-boolean-}
```
@Deprecated public void setWordWrap(boolean value)
```

Defines word wrap. If this property set to true and Width value specified, text will be broken in the several lines to fit into specified width. Default value: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value @deprecated "Use WordWrapMode instead." |

### setWordWrapMode {#setWordWrapMode-int-}
```
public final void setWordWrapMode(int value)
```

Gets or sets the word wrap mode for text rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | WordWrapMode element @see WordWrapMode |
