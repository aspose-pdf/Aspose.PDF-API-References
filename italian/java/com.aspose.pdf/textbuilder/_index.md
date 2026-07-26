---
title: "TextBuilder"
linktitle: "TextBuilder"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Aggiunge l'oggetto testo alla pagina Pdf."
type: docs
weight: 4940
url: /it/java/com.aspose.pdf/textbuilder/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextBuilder

```
public final class TextBuilder extends Object
```

Aggiunge l'oggetto testo alla pagina Pdf.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextBuilder](#TextBuilder-com.aspose.pdf.Page-) | <p> Inizializza una nuova istanza della classe {@code TextBuilder} per la pagina Pdf. </p> |
| [TextBuilder](#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-) | Inizializza una nuova istanza della classe {@code TextBuilder} per la pagina Pdf. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [appendParagraph](#appendParagraph-com.aspose.pdf.TextParagraph-) | <p> Aggiunge un paragrafo di testo alla pagina Pdf. </p> <hr> <pre> L'esempio dimostra come creare un oggetto paragrafo di testo e aggiungerlo alla pagina Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre> |
| [appendParagraph](#appendParagraph-com.aspose.pdf.TextParagraph-int-) | Aggiunge un paragrafo con rotazione |
| [appendText](#appendText-java.util.List-) | Aggiunge un elenco di frammenti di testo alla pagina Pdf. |
| [appendText](#appendText-com.aspose.pdf.TextFragment-) | <p> Aggiunge un frammento di testo alla pagina Pdf </p> <hr> <pre> L'esempio dimostra come creare un oggetto frammento di testo, personalizzare i suoi segmenti di testo e aggiungerlo alla pagina Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.Position = new Position(100, 600); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GREY); tf.getTextState().setForegroundColor ( Color.Red); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments.add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |
| [getSegmenter](#getSegmenter--) | Ottiene l'oggetto TextSegmenter |

### TextBuilder {#TextBuilder-com.aspose.pdf.Page-}
<p> Inizializza una nuova istanza della classe {@code TextBuilder} per la pagina Pdf. </p>

### TextBuilder {#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-}
Inizializza una nuova istanza della classe {@code TextBuilder} per la pagina Pdf.

### appendParagraph {#appendParagraph-com.aspose.pdf.TextParagraph-}
<p> Aggiunge un paragrafo di testo alla pagina Pdf. </p> <hr> <pre> L'esempio dimostra come creare un oggetto paragrafo di testo e aggiungerlo alla pagina Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre>

### appendParagraph {#appendParagraph-com.aspose.pdf.TextParagraph-int-}
Aggiunge un paragrafo con rotazione

### appendText {#appendText-java.util.List-}
Aggiunge un elenco di frammenti di testo alla pagina Pdf.

### appendText {#appendText-com.aspose.pdf.TextFragment-}
<p> Aggiunge un frammento di testo alla pagina Pdf </p> <hr> <pre> L'esempio dimostra come creare un oggetto frammento di testo, personalizzare i suoi segmenti di testo e aggiungerlo alla pagina Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.Position = new Position(100, 600); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GREY); tf.getTextState().setForegroundColor ( Color.Red); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments.add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### getSegmenter {#getSegmenter--}
```
public com.aspose.pdf.engine.commondata.text.segmenting.TextSegmenter getSegmenter()
```

Ottiene l'oggetto TextSegmenter

**Returns:**
Oggetto TextSegmenter
