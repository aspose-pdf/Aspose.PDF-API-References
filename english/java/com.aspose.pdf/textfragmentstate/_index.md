---
title: TextFragmentState
second_title: Aspose.PDF for Java API Reference
description: Represents a text state of a text fragment.
type: docs
weight: 375
url: /java/com.aspose.pdf/textfragmentstate/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.TextState](../../com.aspose.pdf/textstate)
```
public final class TextFragmentState extends TextState
```

Represents a text state of a text fragment.

--------------------

```
The example demonstrates how to change text color and font size of the text with ```
TextState
``` object.
 
  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");
  
  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Accept the absorber for first page
  doc.getPages().get(1).accept(absorber);
  
  // Change foreground color of the first text occurrence
  absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED);
  // Change font size of the first text occurrence
  absorber.getTextFragments().get(1).getTextState().setFontSize ( 15);
  
  // Save document
  doc.save("D:\\Tests\\output.pdf");
```

--------------------

Provides a way to change following properties of the text: font ( TextFragmentState.Font  property) font size ( TextFragmentState.FontSize  property) font style (  TextFragmentState.FontStyle  property) foreground color (  TextFragmentState.ForegroundColor  property) background color (  TextFragmentState.BackgroundColor  property) Note that changing  TextFragmentState  properties may change inner  TextFragment.Segments  collection because TextFragment is an aggregate object and it may rearrange internal segments or merge them into single segment. If your requirement is to leave the  TextFragment.Segments  collection unchanged, please change inner segments individually.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextFragmentState(TextFragment fragment)](#TextFragmentState-com.aspose.pdf.TextFragment-) | Initializes new instance of the  TextFragmentState  object with specified  TextFragment  object. |
## Methods

| Method | Description |
| --- | --- |
| [getCharacterSpacing()](#getCharacterSpacing--) | Gets character spacing of the text, represented by the  TextFragment  object. |
| [setCharacterSpacing(float value)](#setCharacterSpacing-float-) | Sets character spacing of the text, represented by the  TextFragment  object. |
| [getHorizontalScaling()](#getHorizontalScaling--) | Gets horizontal scaling of the text, represented by the  TextFragment  object. |
| [setHorizontalScaling(float value)](#setHorizontalScaling-float-) | Sets horizontal scaling of the text, represented by the  TextFragment  object. |
| [getWordSpacing()](#getWordSpacing--) | Gets word spacing of the text. |
| [setWordSpacing(float value)](#setWordSpacing-float-) | Sets word spacing of the text. |
| [getRenderingMode()](#getRenderingMode--) | Gets or sets rendering mode of the text. |
| [setRenderingMode(int value)](#setRenderingMode-int-) | Gets or sets rendering mode of the text. |
| [isSubscript()](#isSubscript--) | Gets or sets subscript of the text, represented by the  TextFragment  object. |
| [setSubscript(boolean value)](#setSubscript-boolean-) | Gets or sets subscript of the text, represented by the  TextFragment  object. |
| [isInvisible()](#isInvisible--) | Gets invisibility of the text. |
| [setInvisible(boolean value)](#setInvisible-boolean-) | Sets invisibility of the text. |
| [isSuperscript()](#isSuperscript--) | Gets or sets superscript of the text, represented by the  TextFragment  object. |
| [setSuperscript(boolean value)](#setSuperscript-boolean-) | Gets or sets superscript of the text, represented by the  TextFragment  object. |
| [getTabStops()](#getTabStops--) | Gets tabstops for the text. |
| [getLineSpacing()](#getLineSpacing--) | Gets line spacing of the text. |
| [setLineSpacing(float value)](#setLineSpacing-float-) | Sets line spacing of the text. |
| [getForegroundColor()](#getForegroundColor--) | Gets foreground color of the text, represented by the  TextFragment  object |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.pdf.Color-) | Sets foreground color of the text, represented by the  TextFragment  object |
| [getStrokingColor()](#getStrokingColor--) | Gets or sets color stroking operations of  TextFragment  rendering (stroke text, rectangle border) |
| [setStrokingColor(Color value)](#setStrokingColor-com.aspose.pdf.Color-) | Gets or sets color stroking operations of  TextFragment  rendering (stroke text, rectangle border) |
| [getBackgroundColor()](#getBackgroundColor--) | Sets background color of the text, represented by the  TextFragment  object |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Sets background color of the text, represented by the [TextFragment](../../com.aspose.pdf/textfragment) object |
| [isUnderline()](#isUnderline--) | Gets or sets underline for the text, represented by the [TextFragment](../../com.aspose.pdf/textfragment) object |
| [setUnderline(boolean value)](#setUnderline-boolean-) | Sets underline for the text, represented by the  TextFragment  object |
| [setStrikeOut(boolean value)](#setStrikeOut-boolean-) | Sets strikeout for the text, represented by the  TextFragment  object |
| [getFontStyle()](#getFontStyle--) | Sets font style of the text, represented by the  TextFragment  object |
| [setFontStyle(int value)](#setFontStyle-int-) | Sets font style of the text, represented by the [TextFragment](../../com.aspose.pdf/textfragment) object |
| [getFont()](#getFont--) | Gets font of the text, represented by the  TextFragment  object |
| [setFont(Font value)](#setFont-com.aspose.pdf.Font-) | Sets font of the text, represented by the  TextFragment  object |
| [getFontSize()](#getFontSize--) | Gets font size of the text, represented by the  TextFragment  object |
| [setFontSize(float value)](#setFontSize-float-) | Sets font size of the text, represented by the  TextFragment  object |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets horizontal alignment for the text. |
| [setHorizontalAlignment(HorizontalAlignment value)](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Sets horizontal alignment for the text. |
| [getFormattingOptions()](#getFormattingOptions--) | Gets or sets formatting options. |
| [setFormattingOptions(TextFormattingOptions value)](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Gets or sets formatting options. |
| [getTextHeight()](#getTextHeight--) | Gets text height, represented by the  TextFragment  object |
| [getRotation()](#getRotation--) | Gets or sets rotation angle in degrees. |
| [setRotation(double value)](#setRotation-double-) | Gets or sets rotation angle in degrees. |
| [getDrawTextRectangleBorder()](#getDrawTextRectangleBorder--) | Gets if text rectangle border drawn flag. |
| [setDrawTextRectangleBorder(boolean value)](#setDrawTextRectangleBorder-boolean-) | Sets if text rectangle border drawn flag. |
| [measureString(String str)](#measureString-java.lang.String-) | Measures the string. |
| [applyChangesFrom(TextState textState)](#applyChangesFrom-com.aspose.pdf.TextState-) | Applies settings from another textState |
| [applyChangesFrom(TextState textState, boolean groupChangesOnly)](#applyChangesFrom-com.aspose.pdf.TextState-boolean-) | Applies settings from another textState |
### TextFragmentState(TextFragment fragment) {#TextFragmentState-com.aspose.pdf.TextFragment-}
```
public TextFragmentState(TextFragment fragment)
```


Initializes new instance of the  TextFragmentState  object with specified  TextFragment  object. This  TextFragmentState  initialization is not supported. TextFragmentState is only available with  TextFragment.TextState  property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fragment | [TextFragment](../../com.aspose.pdf/textfragment) | Text fragment object. |

### getCharacterSpacing() {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```


Gets character spacing of the text, represented by the  TextFragment  object.

**Returns:**
float - float value
### setCharacterSpacing(float value) {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```


Sets character spacing of the text, represented by the  TextFragment  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### getHorizontalScaling() {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```


Gets horizontal scaling of the text, represented by the  TextFragment  object.

**Returns:**
float - float value
### setHorizontalScaling(float value) {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```


Sets horizontal scaling of the text, represented by the  TextFragment  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

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

### getRenderingMode() {#getRenderingMode--}
```
public int getRenderingMode()
```


Gets or sets rendering mode of the text.

**Returns:**
int
### setRenderingMode(int value) {#setRenderingMode-int-}
```
public void setRenderingMode(int value)
```


Gets or sets rendering mode of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isSubscript() {#isSubscript--}
```
public boolean isSubscript()
```


Gets or sets subscript of the text, represented by the  TextFragment  object.

**Returns:**
boolean - boolean value
### setSubscript(boolean value) {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```


Gets or sets subscript of the text, represented by the  TextFragment  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isInvisible() {#isInvisible--}
```
public boolean isInvisible()
```


Gets invisibility of the text.

**Returns:**
boolean - boolean value
### setInvisible(boolean value) {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```


Sets invisibility of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isSuperscript() {#isSuperscript--}
```
public boolean isSuperscript()
```


Gets or sets superscript of the text, represented by the  TextFragment  object.

**Returns:**
boolean - value boolean value
### setSuperscript(boolean value) {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```


Gets or sets superscript of the text, represented by the  TextFragment  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getTabStops() {#getTabStops--}
```
public TabStops getTabStops()
```


Gets tabstops for the text.

--------------------

Note that Tabstops property works in new document generation scenarios only. Tabstops may be added during  TextFragment  initialization. Tabstops must be constructed before the text.

**Returns:**
[TabStops](../../com.aspose.pdf/tabstops) - TabStops object
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

### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Gets foreground color of the text, represented by the  TextFragment  object

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object
### setForegroundColor(Color value) {#setForegroundColor-com.aspose.pdf.Color-}
```
public void setForegroundColor(Color value)
```


Sets foreground color of the text, represented by the  TextFragment  object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color object |

### getStrokingColor() {#getStrokingColor--}
```
public Color getStrokingColor()
```


Gets or sets color stroking operations of  TextFragment  rendering (stroke text, rectangle border)

**Returns:**
[Color](../../com.aspose.pdf/color)
### setStrokingColor(Color value) {#setStrokingColor-com.aspose.pdf.Color-}
```
public void setStrokingColor(Color value)
```


Gets or sets color stroking operations of  TextFragment  rendering (stroke text, rectangle border)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Sets background color of the text, represented by the  TextFragment  object

**Returns:**
[Color](../../com.aspose.pdf/color) - value Color object
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public void setBackgroundColor(Color value)
```


Sets background color of the text, represented by the [TextFragment](../../com.aspose.pdf/textfragment) object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) |  |

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Gets or sets underline for the text, represented by the [TextFragment](../../com.aspose.pdf/textfragment) object

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

### setStrikeOut(boolean value) {#setStrikeOut-boolean-}
```
public void setStrikeOut(boolean value)
```


Sets strikeout for the text, represented by the  TextFragment  object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getFontStyle() {#getFontStyle--}
```
public int getFontStyle()
```


Sets font style of the text, represented by the  TextFragment  object

**Returns:**
int - FontStyles element
### setFontStyle(int value) {#setFontStyle-int-}
```
public void setFontStyle(int value)
```


Sets font style of the text, represented by the [TextFragment](../../com.aspose.pdf/textfragment) object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getFont() {#getFont--}
```
public Font getFont()
```


Gets font of the text, represented by the  TextFragment  object

**Returns:**
[Font](../../com.aspose.pdf/font) - Font value
### setFont(Font value) {#setFont-com.aspose.pdf.Font-}
```
public void setFont(Font value)
```


Sets font of the text, represented by the  TextFragment  object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) | Font value |

### getFontSize() {#getFontSize--}
```
public float getFontSize()
```


Gets font size of the text, represented by the  TextFragment  object

**Returns:**
float - float value
### setFontSize(float value) {#setFontSize-float-}
```
public void setFontSize(float value)
```


Sets font size of the text, represented by the  TextFragment  object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```


Gets horizontal alignment for the text.

--------------------

HorizontalAlignment.None is equal to HorizontalAlignment.Left. Note that TextFragmentState.VerticalAlignment property works in new document generation scenarios only.

**Returns:**
[HorizontalAlignment](../../com.aspose.pdf/horizontalalignment) - HorizontalAlignment value
### setHorizontalAlignment(HorizontalAlignment value) {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
```
public void setHorizontalAlignment(HorizontalAlignment value)
```


Sets horizontal alignment for the text.

--------------------

HorizontalAlignment.None is equal to HorizontalAlignment.Left. Note that TextFragmentState.VerticalAlignment property works in new document generation scenarios only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HorizontalAlignment](../../com.aspose.pdf/horizontalalignment) | HorizontalAlignment value |

### getFormattingOptions() {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```


Gets or sets formatting options. Setting of the options will be effective in generator scenarios only.

**Returns:**
[TextFormattingOptions](../../com.aspose.pdf/textformattingoptions) - TextFormattingOptions instance
### setFormattingOptions(TextFormattingOptions value) {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
```
public void setFormattingOptions(TextFormattingOptions value)
```


Gets or sets formatting options. Setting of the options will be effective in generator scenarios only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextFormattingOptions](../../com.aspose.pdf/textformattingoptions) | TextFormattingOptions instance |

### getTextHeight() {#getTextHeight--}
```
public float getTextHeight()
```


Gets text height, represented by the  TextFragment  object

**Returns:**
float - float value
### getRotation() {#getRotation--}
```
public double getRotation()
```


Gets or sets rotation angle in degrees.

**Returns:**
double - double value
### setRotation(double value) {#setRotation-double-}
```
public void setRotation(double value)
```


Gets or sets rotation angle in degrees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getDrawTextRectangleBorder() {#getDrawTextRectangleBorder--}
```
public boolean getDrawTextRectangleBorder()
```


Gets if text rectangle border drawn flag.

**Returns:**
boolean - boolean value
### setDrawTextRectangleBorder(boolean value) {#setDrawTextRectangleBorder-boolean-}
```
public void setDrawTextRectangleBorder(boolean value)
```


Sets if text rectangle border drawn flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

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
double - double value, Width of the string.
### applyChangesFrom(TextState textState) {#applyChangesFrom-com.aspose.pdf.TextState-}
```
public void applyChangesFrom(TextState textState)
```


Applies settings from another textState

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textState | [TextState](../../com.aspose.pdf/textstate) | Text state object.

--------------------

Only those properties will be copied that were changed explicitly. |

### applyChangesFrom(TextState textState, boolean groupChangesOnly) {#applyChangesFrom-com.aspose.pdf.TextState-boolean-}
```
public void applyChangesFrom(TextState textState, boolean groupChangesOnly)
```


Applies settings from another textState

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textState | [TextState](../../com.aspose.pdf/textstate) | Text state object. |
| groupChangesOnly | boolean | if true inherit group changes only (without isolating the segments into single segment) |

