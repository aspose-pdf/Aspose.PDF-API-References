---
title: "TextBuilder"
linktitle: "TextBuilder"
second_title: "Aspose.PDF för Java API-referens"
description: "Lägger till textobjekt på PDF-sida."
type: docs
weight: 4940
url: /sv/java/com.aspose.pdf/textbuilder/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextBuilder

```
public final class TextBuilder extends Object
```

Lägger till textobjekt på PDF-sida.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextBuilder](#TextBuilder-com.aspose.pdf.Page-) | <p> Initierar en ny instans av {@code TextBuilder}-klassen för PDF-sidan. </p> |
| [TextBuilder](#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-) | Initierar en ny instans av {@code TextBuilder}-klassen för PDF-sidan. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [appendParagraph](#appendParagraph-com.aspose.pdf.TextParagraph-) | <p> Lägger till ett textstycke på Pdf-sidan. </p> <hr> <pre> The example demonstrates how to create text paragraph object and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre> |
| [appendParagraph](#appendParagraph-com.aspose.pdf.TextParagraph-int-) | Lägger till stycke med rotation |
| [appendText](#appendText-java.util.List-) | Lägger till en lista med textfragment på Pdf-sidan. |
| [appendText](#appendText-com.aspose.pdf.TextFragment-) | <p> Lägger till textfragment på Pdf-sida </p> <hr> <pre> Exemplet visar hur man skapar ett textfragment‑objekt, anpassar dess textsegment och lägger till det på Pdf-sidan. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // skapa textfragment TextFragment tf = new TextFragment("main text"); tf.Position = new Position(100, 600); // ange dess textegenskaper tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GREY); tf.getTextState().setForegroundColor ( Color.Red); // lägg till ett ytterligare segment till textfragmentets Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments.add(segment2); // skapa TextBuilder‑objekt TextBuilder builder = new TextBuilder(page); // lägg till textfragmentet på Pdf-sidan builder.appendText(tf); // spara dokument doc.save(outFile); </pre> |
| [getSegmenter](#getSegmenter--) | Hämtar TextSegmenter-objekt |

### TextBuilder {#TextBuilder-com.aspose.pdf.Page-}
<p> Initierar en ny instans av {@code TextBuilder}-klassen för PDF-sidan. </p>

### TextBuilder {#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-}
Initierar en ny instans av {@code TextBuilder}-klassen för PDF-sidan.

### appendParagraph {#appendParagraph-com.aspose.pdf.TextParagraph-}
<p> Lägger till ett textstycke på Pdf-sidan. </p> <hr> <pre> The example demonstrates how to create text paragraph object and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre>

### appendParagraph {#appendParagraph-com.aspose.pdf.TextParagraph-int-}
Lägger till stycke med rotation

### appendText {#appendText-java.util.List-}
Lägger till en lista med textfragment på Pdf-sidan.

### appendText {#appendText-com.aspose.pdf.TextFragment-}
<p> Lägger till textfragment på Pdf-sida </p> <hr> <pre> Exemplet visar hur man skapar ett textfragment‑objekt, anpassar dess textsegment och lägger till det på Pdf-sidan. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // skapa textfragment TextFragment tf = new TextFragment("main text"); tf.Position = new Position(100, 600); // ange dess textegenskaper tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GREY); tf.getTextState().setForegroundColor ( Color.Red); // lägg till ett ytterligare segment till textfragmentets Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments.add(segment2); // skapa TextBuilder‑objekt TextBuilder builder = new TextBuilder(page); // lägg till textfragmentet på Pdf-sidan builder.appendText(tf); // spara dokument doc.save(outFile); </pre>

### getSegmenter {#getSegmenter--}
```
public com.aspose.pdf.engine.commondata.text.segmenting.TextSegmenter getSegmenter()
```

Hämtar TextSegmenter-objekt

**Returns:**
TextSegmenter-objekt
