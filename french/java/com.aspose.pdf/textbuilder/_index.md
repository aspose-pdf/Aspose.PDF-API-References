---
title: "TextBuilder"
linktitle: "TextBuilder"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Ajoute un objet texte à la page Pdf."
type: docs
weight: 4940
url: /fr/java/com.aspose.pdf/textbuilder/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextBuilder

```
public final class TextBuilder extends Object
```

Ajoute un objet texte à la page Pdf.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextBuilder](#TextBuilder-com.aspose.pdf.Page-) | <p> Initialise une nouvelle instance de la classe {@code TextBuilder} pour la page Pdf. </p> |
| [TextBuilder](#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-) | Initialise une nouvelle instance de la classe {@code TextBuilder} pour la page Pdf. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [appendParagraph](#appendParagraph-com.aspose.pdf.TextParagraph-) | <p> Ajoute un paragraphe de texte à la page Pdf. </p> <hr> <pre> The example demonstrates how to create text paragraph object and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre> |
| [appendParagraph](#appendParagraph-com.aspose.pdf.TextParagraph-int-) | Ajoute un paragraphe avec rotation |
| [appendText](#appendText-java.util.List-) | Ajoute une liste de fragments de texte à la page Pdf. |
| [appendText](#appendText-com.aspose.pdf.TextFragment-) | <p> Ajoute un fragment de texte à la page Pdf </p> <hr> <pre> The example demonstrates how to create text fragment object, customize it's text segments and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.Position = new Position(100, 600); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GREY); tf.getTextState().setForegroundColor ( Color.Red); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments.add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |
| [getSegmenter](#getSegmenter--) | Obtient l'objet TextSegmenter |

### TextBuilder {#TextBuilder-com.aspose.pdf.Page-}
<p> Initialise une nouvelle instance de la classe {@code TextBuilder} pour la page Pdf. </p>

### TextBuilder {#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-}
Initialise une nouvelle instance de la classe {@code TextBuilder} pour la page Pdf.

### appendParagraph {#appendParagraph-com.aspose.pdf.TextParagraph-}
<p> Ajoute un paragraphe de texte à la page Pdf. </p> <hr> <pre> The example demonstrates how to create text paragraph object and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre>

### appendParagraph {#appendParagraph-com.aspose.pdf.TextParagraph-int-}
Ajoute un paragraphe avec rotation

### appendText {#appendText-java.util.List-}
Ajoute une liste de fragments de texte à la page Pdf.

### appendText {#appendText-com.aspose.pdf.TextFragment-}
<p> Ajoute un fragment de texte à la page Pdf </p> <hr> <pre> The example demonstrates how to create text fragment object, customize it's text segments and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.Position = new Position(100, 600); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GREY); tf.getTextState().setForegroundColor ( Color.Red); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments.add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### getSegmenter {#getSegmenter--}
```
public com.aspose.pdf.engine.commondata.text.segmenting.TextSegmenter getSegmenter()
```

Obtient l'objet TextSegmenter

**Returns:**
Objet TextSegmenter
