---
title: TextParagraph
second_title: Aspose.PDF for Java API Reference
description: Represents text paragraphs as multiline text object.
type: docs
weight: 381
url: /java/com.aspose.pdf/textparagraph/
---
**Inheritance:**
java.lang.Object
```
public final class TextParagraph
```

Represents text paragraphs as multiline text object.

--------------------

```
The example demonstrates how to create text paragraph object and append it to the Pdf page.


 Document doc = new Document(inFile);
 Page page = (Page)doc.getPages().get(1);
 // create text paragraph
 TextParagraph paragraph = new TextParagraph();

 // set the paragraph rectangle
 paragraph.setRectangle ( new Rectangle(100, 600, 200, 700));
 // set word wrapping options
 paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords);
 // append string lines
 paragraph.appendLine("the quick brown fox jumps over the lazy dog");
 paragraph.appendLine("line2");
 paragraph.appendLine("line3");
 // append the paragraph to the Pdf page with the TextBuilder
 TextBuilder textBuilder = new TextBuilder(page);
 textBuilder.appendParagraph(paragraph);
 // save Pdf document
 doc.save(outFile);
```
## Constructors

| Constructor | Description |
| --- | --- |
| [TextParagraph()](#TextParagraph--) | Creates  TextParagraph  object. |
## Methods

| Method | Description |
| --- | --- |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Sets background color for the text paragraph. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets vertical alignment for the text inside paragrph's  Rectangle . |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Sets vertical alignment for the text inside paragrph's  Rectangle . |
| [getSubsequentLinesIndent()](#getSubsequentLinesIndent--) | Gets subsequent lines indent value. |
| [setSubsequentLinesIndent(float value)](#setSubsequentLinesIndent-float-) | Sets subsequent lines indent value. |
| [getFirstLineIndent()](#getFirstLineIndent--) | Gets or sets subsequent lines indent value. |
| [setFirstLineIndent(float value)](#setFirstLineIndent-float-) | Gets or sets subsequent lines indent value. |
| [isJustify()](#isJustify--) | Gets value whether text is justified. |
| [setJustify(boolean value)](#setJustify-boolean-) | Sets value whether text is justified. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets horizontal alignment for the text inside paragrph's Rectangle. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Sets horizontal alignment for the text inside paragrph's Rectangle. |
| [getHyphenSymbol()](#getHyphenSymbol--) | Gets hyphen symbol that is used in hyphenation process. |
| [setHyphenSymbol(String value)](#setHyphenSymbol-java.lang.String-) | Sets hyphen symbol that is used in hyphenation process. |
| [getFormattingOptions()](#getFormattingOptions--) | Gets formatting options. |
| [setFormattingOptions(TextFormattingOptions value)](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Sets formatting options. |
| [getPosition()](#getPosition--) | Gets position of the paragraph. |
| [setPosition(Position value)](#setPosition-com.aspose.pdf.Position-) | Sets position of the paragraph. |
| [getTextRectangle()](#getTextRectangle--) | Gets rectangle of the text placed to the paragraph. |
| [getRectangle()](#getRectangle--) | Gets rectangle of the paragraph. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.pdf.Rectangle-) | Sets rectangle of the paragraph. |
| [getMargin()](#getMargin--) | Gets the padding. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Sets the padding. |
| [getRotation()](#getRotation--) | Gets or sets rotation angle in degrees. |
| [setRotation(double value)](#setRotation-double-) | Gets or sets rotation angle in degrees. |
| [beginEdit()](#beginEdit--) | Begins the editing of the TextParagraph. |
| [endEdit()](#endEdit--) | Ends the editing of the TextParagraph. |
| [appendLine(String line)](#appendLine-java.lang.String-) | Appends text line |
| [appendLine(String line, float lineSpacing)](#appendLine-java.lang.String-float-) | Appends text line. |
| [appendLine(String line, TextState textState)](#appendLine-java.lang.String-com.aspose.pdf.TextState-) | Appends text line with text state parameters. |
| [appendLine(String line, TextState textState, float lineSpacing)](#appendLine-java.lang.String-com.aspose.pdf.TextState-float-) | Appends text line with text state parameters |
| [appendLine(TextFragment line)](#appendLine-com.aspose.pdf.TextFragment-) | Appends text line with text state parameters. |
| [appendLine(TextFragment line, TextState textState)](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-) | Appends text line with text state parameters. |
| [appendLine(TextFragment line, TextState textState, float lineSpacing)](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-) | Appends text line with text state parameters |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.pdf.Matrix-) | Sets Rotation of the paragraph. |
| [setOldCodeCompatibilityMode(boolean value)](#setOldCodeCompatibilityMode-boolean-) | Set old code compatibility mode |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | Set background mode for the text paragraph |
### TextParagraph() {#TextParagraph--}
```
public TextParagraph()
```


Creates  TextParagraph  object.

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public void setBackgroundColor(Color value)
```


Sets background color for the text paragraph.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color object |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Gets vertical alignment for the text inside paragrph's  Rectangle .

**Returns:**
int - VerticalAlignment value
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Sets vertical alignment for the text inside paragrph's  Rectangle .

VerticalAlignment.None is equal to VerticalAlignment.Bottom.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | VerticalAlignment value |

### getSubsequentLinesIndent() {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```


Gets subsequent lines indent value.

**Returns:**
float - float value
### setSubsequentLinesIndent(float value) {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```


Sets subsequent lines indent value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### getFirstLineIndent() {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```


Gets or sets subsequent lines indent value. If set to a non-zero value, it has an advantage over the FormattingOptions.SubsequentLinesIndent value.

**Returns:**
float - float value
### setFirstLineIndent(float value) {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```


Gets or sets subsequent lines indent value. If set to a non-zero value, it has an advantage over the FormattingOptions.SubsequentLinesIndent value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### isJustify() {#isJustify--}
```
public boolean isJustify()
```


Gets value whether text is justified.

**Returns:**
boolean - boolean value
### setJustify(boolean value) {#setJustify-boolean-}
```
public void setJustify(boolean value)
```


Sets value whether text is justified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Gets horizontal alignment for the text inside paragrph's Rectangle.

HorizontalAlignment.None is equal to HorizontalAlignment.Left.

**Returns:**
int - HorizontalAlignment value
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Sets horizontal alignment for the text inside paragrph's Rectangle.

HorizontalAlignment.None is equal to HorizontalAlignment.Left.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HorizontalAlignment value |

### getHyphenSymbol() {#getHyphenSymbol--}
```
public String getHyphenSymbol()
```


Gets hyphen symbol that is used in hyphenation process.

The hyphenation symbol is "-" by default. To eliminate hyphen drawing (with wrapping procedure still in place) please set empty string string.Empty for HyphenSymbol.

**Returns:**
java.lang.String - String value
### setHyphenSymbol(String value) {#setHyphenSymbol-java.lang.String-}
```
public void setHyphenSymbol(String value)
```


Sets hyphen symbol that is used in hyphenation process.

The hyphenation symbol is "-" by default. To eliminate hyphen drawing (with wrapping procedure still in place) please set empty string string.Empty for HyphenSymbol.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getFormattingOptions() {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```


Gets formatting options.

**Returns:**
[TextFormattingOptions](../../com.aspose.pdf/textformattingoptions) - TextFormattingOptions object
### setFormattingOptions(TextFormattingOptions value) {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
```
public void setFormattingOptions(TextFormattingOptions value)
```


Sets formatting options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextFormattingOptions](../../com.aspose.pdf/textformattingoptions) | TextFormattingOptions object |

### getPosition() {#getPosition--}
```
public Position getPosition()
```


Gets position of the paragraph.

**Returns:**
[Position](../../com.aspose.pdf/position) - Position value
### setPosition(Position value) {#setPosition-com.aspose.pdf.Position-}
```
public void setPosition(Position value)
```


Sets position of the paragraph.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Position](../../com.aspose.pdf/position) | Position value |

### getTextRectangle() {#getTextRectangle--}
```
public Rectangle getTextRectangle()
```


Gets rectangle of the text placed to the paragraph.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets rectangle of the paragraph.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object
### setRectangle(Rectangle value) {#setRectangle-com.aspose.pdf.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Sets rectangle of the paragraph.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |

### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Gets the padding.

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo value
### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Sets the padding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo value |

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

### beginEdit() {#beginEdit--}
```
public void beginEdit()
```


Begins the editing of the TextParagraph.

Improves performance of TextParagraph population. Any layout calculation is suspended until EndEdit method is invoked.

Note that method invoke can't be nested.

### endEdit() {#endEdit--}
```
public void endEdit()
```


Ends the editing of the TextParagraph.

Improves performance of TextParagraph population. Any layout calculation is suspended until EndEdit method is invoked.

Note that method invoke can't be nested.

### appendLine(String line) {#appendLine-java.lang.String-}
```
public void appendLine(String line)
```


Appends text line

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| line | java.lang.String | The new line's text. |

### appendLine(String line, float lineSpacing) {#appendLine-java.lang.String-float-}
```
public void appendLine(String line, float lineSpacing)
```


Appends text line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| line | java.lang.String | The new line's text. |
| lineSpacing | float | Additional spacing (0.0 is default and corresponds to default text line height). The spacing value is added to default line spacing for the particular line, so you may specify 12.0 to get empty row AFTER a text line drawn with 12pt font. |

### appendLine(String line, TextState textState) {#appendLine-java.lang.String-com.aspose.pdf.TextState-}
```
public void appendLine(String line, TextState textState)
```


Appends text line with text state parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| line | java.lang.String | The new line's text. |
| textState | [TextState](../../com.aspose.pdf/textstate) | Text state of the new line. |

### appendLine(String line, TextState textState, float lineSpacing) {#appendLine-java.lang.String-com.aspose.pdf.TextState-float-}
```
public void appendLine(String line, TextState textState, float lineSpacing)
```


Appends text line with text state parameters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| line | java.lang.String | The new line's text. |
| textState | [TextState](../../com.aspose.pdf/textstate) | Text state of the new line. |
| lineSpacing | float | Additional spacing (0.0 is default and corresponds to default text line height). The spacing value is added to default line spacing for the particular line, so you may specify 12.0 to get empty row AFTER a text line drawn with 12pt font. |

### appendLine(TextFragment line) {#appendLine-com.aspose.pdf.TextFragment-}
```
public void appendLine(TextFragment line)
```


Appends text line with text state parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| line | [TextFragment](../../com.aspose.pdf/textfragment) | The new line's text. |

### appendLine(TextFragment line, TextState textState) {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-}
```
public void appendLine(TextFragment line, TextState textState)
```


Appends text line with text state parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| line | [TextFragment](../../com.aspose.pdf/textfragment) | The new line's text. |
| textState | [TextState](../../com.aspose.pdf/textstate) | Text state of the new line. |

### appendLine(TextFragment line, TextState textState, float lineSpacing) {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-}
```
public void appendLine(TextFragment line, TextState textState, float lineSpacing)
```


Appends text line with text state parameters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| line | [TextFragment](../../com.aspose.pdf/textfragment) | The new line's text. |
| textState | [TextState](../../com.aspose.pdf/textstate) | Text state of the new line. |
| lineSpacing | float | Additional spacing (0.0 is default and corresponds to default text line height). The spacing value is added to default line spacing for the particular line, so you may specify 12.0 to get empty row AFTER a text line drawn with 12pt font. |

### setMatrix(Matrix value) {#setMatrix-com.aspose.pdf.Matrix-}
```
public void setMatrix(Matrix value)
```


Sets Rotation of the paragraph.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.pdf/matrix) | Matrix object |

### setOldCodeCompatibilityMode(boolean value) {#setOldCodeCompatibilityMode-boolean-}
```
public void setOldCodeCompatibilityMode(boolean value)
```


Set old code compatibility mode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


Set background mode for the text paragraph

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

