---
title: TextParagraph
linktitle: TextParagraph
second_title: Aspose.PDF for Java API Reference
description: <p> Represents text paragraphs as multiline text object. </p> <hr> <pre> The example demonstrates how to create text paragraph object and append it to the Pdf page. Document doc.
type: docs
weight: 5200
url: /java/com.aspose.pdf/textparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextParagraph

```
public final class TextParagraph extends Object
```

<p> Represents text paragraphs as multiline text object. </p> <hr> <pre> The example demonstrates how to create text paragraph object and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre>

## Constructors

| Constructor | Description |
| --- | --- |
| [TextParagraph](#TextParagraph--) | Creates {@code TextParagraph} object. |

## Methods

| Method | Description |
| --- | --- |
| [appendLine](#appendLine-java.lang.String-) | Appends text line |
| [appendLine](#appendLine-java.lang.String-float-) | Appends text line. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-) | Appends text line with text state parameters. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-float-) | Appends text line with text state parameters |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-) | Appends text line with text state parameters. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-) | Appends text line with text state parameters. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-) | Appends text line with text state parameters |
| [beginEdit](#beginEdit--) | Begins the editing of the TextParagraph. <p> Improves performance of TextParagraph population. Any layout calculation is suspended until EndEdit method is invoked. <p> Note that method invoke can't be nested. </p> |
| [endEdit](#endEdit--) | Ends the editing of the TextParagraph. <p> Improves performance of TextParagraph population. Any layout calculation is suspended until EndEdit method is invoked. <p> Note that method invoke can't be nested. </p> |
| [getFirstLineIndent](#getFirstLineIndent--) | Gets or sets subsequent lines indent value. If set to a non-zero value, it has an advantage over the FormattingOptions.SubsequentLinesIndent value. |
| [getFormattingOptions](#getFormattingOptions--) | Gets formatting options. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Gets horizontal alignment for the text inside paragrph's Rectangle. HorizontalAlignment.None is equal to HorizontalAlignment.Left. |
| [getHyphenSymbol](#getHyphenSymbol--) | Gets hyphen symbol that is used in hyphenation process. The hyphenation symbol is "-" by default. To eliminate hyphen drawing (with wrapping procedure still in place) please set empty string string.Empty for HyphenSymbol. |
| [getMargin](#getMargin--) | Gets the padding. |
| [getPosition](#getPosition--) | Gets position of the paragraph. |
| [getRectangle](#getRectangle--) | Gets rectangle of the paragraph. |
| [getRotation](#getRotation--) | Gets or sets rotation angle in degrees. |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | Gets subsequent lines indent value. |
| [getTextRectangle](#getTextRectangle--) | Gets rectangle of the text placed to the paragraph. |
| [getVerticalAlignment](#getVerticalAlignment--) | <p> Gets vertical alignment for the text inside paragrph's {@code Rectangle}. </p> |
| [isJustify](#isJustify--) | Gets value whether text is justified. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Sets background color for the text paragraph. |
| [setBackgroundMode](#setBackgroundMode-int-) | Set background mode for the text paragraph |
| [setFirstLineIndent](#setFirstLineIndent-float-) | Gets or sets subsequent lines indent value. If set to a non-zero value, it has an advantage over the FormattingOptions.SubsequentLinesIndent value. |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Sets formatting options. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Sets horizontal alignment for the text inside paragrph's Rectangle. HorizontalAlignment.None is equal to HorizontalAlignment.Left. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | Sets hyphen symbol that is used in hyphenation process. The hyphenation symbol is "-" by default. To eliminate hyphen drawing (with wrapping procedure still in place) please set empty string string.Empty for HyphenSymbol. |
| [setJustify](#setJustify-boolean-) | Sets value whether text is justified. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Sets the padding. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Sets Rotation of the paragraph. |
| [setOldCodeCompatibilityMode](#setOldCodeCompatibilityMode-boolean-) | Set old code compatibility mode |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | Sets position of the paragraph. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Sets rectangle of the paragraph. |
| [setRotation](#setRotation-double-) | Gets or sets rotation angle in degrees. |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | Sets subsequent lines indent value. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Sets vertical alignment for the text inside paragrph's {@code Rectangle}. VerticalAlignment.None is equal to VerticalAlignment.Bottom. |

### TextParagraph {#TextParagraph--}
```
public TextParagraph()
```

Creates {@code TextParagraph} object.

### appendLine {#appendLine-java.lang.String-}
Appends text line

### appendLine {#appendLine-java.lang.String-float-}
Appends text line.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-}
Appends text line with text state parameters.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-float-}
Appends text line with text state parameters

### appendLine {#appendLine-com.aspose.pdf.TextFragment-}
Appends text line with text state parameters.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-}
Appends text line with text state parameters.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-}
Appends text line with text state parameters

### beginEdit {#beginEdit--}
```
public void beginEdit()
```

Begins the editing of the TextParagraph. <p> Improves performance of TextParagraph population. Any layout calculation is suspended until EndEdit method is invoked. <p> Note that method invoke can't be nested. </p>

### endEdit {#endEdit--}
```
public void endEdit()
```

Ends the editing of the TextParagraph. <p> Improves performance of TextParagraph population. Any layout calculation is suspended until EndEdit method is invoked. <p> Note that method invoke can't be nested. </p>

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

Gets or sets subsequent lines indent value. If set to a non-zero value, it has an advantage over the FormattingOptions.SubsequentLinesIndent value.

**Returns:**
float value

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

Gets formatting options.

**Returns:**
TextFormattingOptions object

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Gets horizontal alignment for the text inside paragrph's Rectangle. HorizontalAlignment.None is equal to HorizontalAlignment.Left.

**Returns:**
HorizontalAlignment value @see HorizontalAlignment

### getHyphenSymbol {#getHyphenSymbol--}
```
public String getHyphenSymbol()
```

Gets hyphen symbol that is used in hyphenation process. The hyphenation symbol is "-" by default. To eliminate hyphen drawing (with wrapping procedure still in place) please set empty string string.Empty for HyphenSymbol.

**Returns:**
String value

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Gets the padding.

**Returns:**
MarginInfo value

### getPosition {#getPosition--}
```
public Position getPosition()
```

Gets position of the paragraph.

**Returns:**
Position value

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Gets rectangle of the paragraph.

**Returns:**
Rectangle object

### getRotation {#getRotation--}
```
public double getRotation()
```

Gets or sets rotation angle in degrees.

**Returns:**
double value

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

Gets subsequent lines indent value.

**Returns:**
float value

### getTextRectangle {#getTextRectangle--}
```
public Rectangle getTextRectangle()
```

Gets rectangle of the text placed to the paragraph.

**Returns:**
Rectangle object

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

<p> Gets vertical alignment for the text inside paragrph's {@code Rectangle}. </p>

**Returns:**
VerticalAlignment value @see VerticalAlignment <hr> <p> VerticalAlignment.None is equal to VerticalAlignment.Bottom. </p>

### isJustify {#isJustify--}
```
public boolean isJustify()
```

Gets value whether text is justified.

**Returns:**
boolean value

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Sets background color for the text paragraph.

### setBackgroundMode {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```

Set background mode for the text paragraph

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value @see TextBackgroundMode |

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

Gets or sets subsequent lines indent value. If set to a non-zero value, it has an advantage over the FormattingOptions.SubsequentLinesIndent value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
Sets formatting options.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Sets horizontal alignment for the text inside paragrph's Rectangle. HorizontalAlignment.None is equal to HorizontalAlignment.Left.

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
Sets hyphen symbol that is used in hyphenation process. The hyphenation symbol is "-" by default. To eliminate hyphen drawing (with wrapping procedure still in place) please set empty string string.Empty for HyphenSymbol.

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

Sets value whether text is justified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Sets the padding.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Sets Rotation of the paragraph.

### setOldCodeCompatibilityMode {#setOldCodeCompatibilityMode-boolean-}
```
public void setOldCodeCompatibilityMode(boolean value)
```

Set old code compatibility mode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setPosition {#setPosition-com.aspose.pdf.Position-}
Sets position of the paragraph.

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Sets rectangle of the paragraph.

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Gets or sets rotation angle in degrees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

Sets subsequent lines indent value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Sets vertical alignment for the text inside paragrph's {@code Rectangle}. VerticalAlignment.None is equal to VerticalAlignment.Bottom.
