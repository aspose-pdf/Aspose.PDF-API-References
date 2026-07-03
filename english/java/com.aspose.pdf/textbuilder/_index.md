---
title: TextBuilder
second_title: Aspose.PDF for Java API Reference
description: Appends text object to Pdf page.
type: docs
weight: 4940
url: /java/com.aspose.pdf/textbuilder/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextBuilder

```
public final class TextBuilder extends Object
```

Appends text object to Pdf page.

## Constructors

| Constructor | Description |
| --- | --- |
| [TextBuilder](#TextBuilder-com.aspose.pdf.Page-) | <p> Initializes a new instance of {@code TextBuilder} class for the Pdf page. </p> |
| [TextBuilder](#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-) | Initializes a new instance of {@code TextBuilder} class for the Pdf page. |

## Methods

| Method | Description |
| --- | --- |
| [appendParagraph](#appendParagraph-com.aspose.pdf.TextParagraph-) | <p> Appends text paragraph to Pdf page. </p> <hr> <pre> The example demonstrates how to create text paragraph object and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre> |
| [appendParagraph](#appendParagraph-com.aspose.pdf.TextParagraph-int-) | Appends paragraph with rotation |
| [appendText](#appendText-java.util.List-) | Appends list of text fragments to Pdf page. |
| [appendText](#appendText-com.aspose.pdf.TextFragment-) | <p> Appends text fragment to Pdf page </p> <hr> <pre> The example demonstrates how to create text fragment object, customize it's text segments and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.Position = new Position(100, 600); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GREY); tf.getTextState().setForegroundColor ( Color.Red); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments.add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |
| [getSegmenter](#getSegmenter--) | Gets TextSegmenter object |

### TextBuilder {#TextBuilder-com.aspose.pdf.Page-}
<p> Initializes a new instance of {@code TextBuilder} class for the Pdf page. </p>

### TextBuilder {#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-}
Initializes a new instance of {@code TextBuilder} class for the Pdf page.

### appendParagraph {#appendParagraph-com.aspose.pdf.TextParagraph-}
<p> Appends text paragraph to Pdf page. </p> <hr> <pre> The example demonstrates how to create text paragraph object and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre>

### appendParagraph {#appendParagraph-com.aspose.pdf.TextParagraph-int-}
Appends paragraph with rotation

### appendText {#appendText-java.util.List-}
Appends list of text fragments to Pdf page.

### appendText {#appendText-com.aspose.pdf.TextFragment-}
<p> Appends text fragment to Pdf page </p> <hr> <pre> The example demonstrates how to create text fragment object, customize it's text segments and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.Position = new Position(100, 600); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GREY); tf.getTextState().setForegroundColor ( Color.Red); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments.add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### getSegmenter {#getSegmenter--}
```
public com.aspose.pdf.engine.commondata.text.segmenting.TextSegmenter getSegmenter()
```

Gets TextSegmenter object

**Returns:**
TextSegmenter object
