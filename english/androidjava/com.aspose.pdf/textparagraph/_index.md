---
title: TextParagraph
second_title: Aspose.PDF for Java API Reference
description: Represents text paragraphs as multiline text object.
type: docs
weight: 303
url: /java/com.aspose.pdf/textparagraph/
---
**Inheritance:**
java.lang.Object
```
public final class TextParagraph
```

Represents text paragraphs as multiline text object.

--------------------

> ```
> The example demonstrates how to create text paragraph object and append it to the Pdf page.
>   
>  Document doc = new Document(inFile);
>  Page page = (Page)doc.getPages().get(1);
>  // create text paragraph
>  TextParagraph paragraph = new TextParagraph();
>             
>  // set the paragraph rectangle
>  paragraph.setRectangle ( new Rectangle(100, 600, 200, 700));
>  // set word wrapping options
>  paragraph.FormattingOptions.setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords);
>  // append string lines
>  paragraph.apendLine("the quick brown fox jumps over the lazy dog");
>  paragraph.appendLine("line2");
>  paragraph.appendLine("line3");
>  // append the paragraph to the Pdf page with the TextBuilder
>  TextBuilder textBuilder = new TextBuilder(page);
>  textBuilder.appendParagraph(paragraph);
>  // save Pdf document
>  doc.save(outFile);
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [TextParagraph()](#TextParagraph--) | Creates  TextParagraph  object. |
## Fields

| Field | Description |
| --- | --- |
| [oldCodeCompatibilityMode](#oldCodeCompatibilityMode) |  |
| [backgroundMode](#backgroundMode) | background mode for the text paragraph TextBackgroundMode.class |
## Methods

| Method | Description |
| --- | --- |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.java.awt.Color-) | Sets background color for the text paragraph. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Sets vertical alignment for the text inside paragrph's  Rectangle . |
| [getSubsequentLinesIndent()](#getSubsequentLinesIndent--) | Gets or sets subsequent lines indent value. |
| [setSubsequentLinesIndent(float value)](#setSubsequentLinesIndent-float-) |  |
| [getJustify()](#getJustify--) | Gets value whether text is justified. |
| [setJustify(boolean value)](#setJustify-boolean-) | Sets value whether text is justified. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets or sets horizontal alignment for the text inside paragrph's . |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) |  |
| [getFormattingOptions()](#getFormattingOptions--) | Gets formatting options. |
| [setFormattingOptions(TextFormattingOptions value)](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Sets formatting options. |
| [getPosition()](#getPosition--) | Gets position of the paragraph. |
| [setPosition(Position value)](#setPosition-com.aspose.pdf.Position-) | Sets position of the paragraph. |
| [getTextRectangle()](#getTextRectangle--) | Gets rectangle of the text placed to the paragraph. |
| [getRectangle()](#getRectangle--) | Gets rectangle of the paragraph. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.pdf.Rectangle-) | Sets rectangle of the paragraph. |
| [getMargin()](#getMargin--) | Gets or sets the padding. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) |  |
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
### TextParagraph() {#TextParagraph--}
```
public TextParagraph()
```


Creates  TextParagraph  object.

### oldCodeCompatibilityMode {#oldCodeCompatibilityMode}
```
public boolean oldCodeCompatibilityMode
```


### backgroundMode {#backgroundMode}
```
public int backgroundMode
```


background mode for the text paragraph TextBackgroundMode.class

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.java.awt.Color-}
```
public void setBackgroundColor(Color value)
```


Sets background color for the text paragraph.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf.java.awt/color) |  |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Sets vertical alignment for the text inside paragrph's  Rectangle .

--------------------

VerticalAlignment.None is equal to VerticalAlignment.Bottom.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSubsequentLinesIndent() {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```


Gets or sets subsequent lines indent value.

**Returns:**
float
### setSubsequentLinesIndent(float value) {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getJustify() {#getJustify--}
```
public boolean getJustify()
```


Gets value whether text is justified.

**Returns:**
boolean
### setJustify(boolean value) {#setJustify-boolean-}
```
public void setJustify(boolean value)
```


Sets value whether text is justified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Gets or sets horizontal alignment for the text inside paragrph's .  HorizontalAlignment.None is equal to HorizontalAlignment.Left.

**Returns:**
int - 
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormattingOptions() {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```


Gets formatting options.

**Returns:**
[TextFormattingOptions](../../com.aspose.pdf/textformattingoptions)
### setFormattingOptions(TextFormattingOptions value) {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
```
public void setFormattingOptions(TextFormattingOptions value)
```


Sets formatting options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextFormattingOptions](../../com.aspose.pdf/textformattingoptions) |  |

### getPosition() {#getPosition--}
```
public Position getPosition()
```


Gets position of the paragraph.

**Returns:**
[Position](../../com.aspose.pdf/position)
### setPosition(Position value) {#setPosition-com.aspose.pdf.Position-}
```
public void setPosition(Position value)
```


Sets position of the paragraph.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Position](../../com.aspose.pdf/position) |  |

### getTextRectangle() {#getTextRectangle--}
```
public Rectangle getTextRectangle()
```


Gets rectangle of the text placed to the paragraph.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - 
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets rectangle of the paragraph.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.pdf.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Sets rectangle of the paragraph.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) |  |

### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Gets or sets the padding.

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - 
### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) |  |

### beginEdit() {#beginEdit--}
```
public void beginEdit()
```


Begins the editing of the TextParagraph.  Improves performance of TextParagraph population. Any layout calculation is suspended until EndEdit method is invoked. Note that method invoke can't be nested.

### endEdit() {#endEdit--}
```
public void endEdit()
```


Ends the editing of the TextParagraph.  Improves performance of TextParagraph population. Any layout calculation is suspended until EndEdit method is invoked. Note that method invoke can't be nested.

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
| value | [Matrix](../../com.aspose.pdf/matrix) |  |

