---
title: "TextBuilder"
linktitle: "TextBuilder"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Añade un objeto de texto a la página Pdf."
type: docs
weight: 4940
url: /es/java/com.aspose.pdf/textbuilder/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextBuilder

```
public final class TextBuilder extends Object
```

Añade un objeto de texto a la página Pdf.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextBuilder](#TextBuilder-com.aspose.pdf.Page-) | <p> Inicializa una nueva instancia de la clase {@code TextBuilder} para la página Pdf. </p> |
| [TextBuilder](#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-) | Inicializa una nueva instancia de la clase {@code TextBuilder} para la página Pdf. |

## Métodos

| Método | Descripción |
| --- | --- |
| [appendParagraph](#appendParagraph-com.aspose.pdf.TextParagraph-) | <p> Añade un párrafo de texto a la página Pdf. </p> <hr> <pre> El ejemplo muestra cómo crear un objeto de párrafo de texto y añadirlo a la página Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre> |
| [appendParagraph](#appendParagraph-com.aspose.pdf.TextParagraph-int-) | Añade párrafo con rotación |
| [appendText](#appendText-java.util.List-) | Añade una lista de fragmentos de texto a la página Pdf. |
| [appendText](#appendText-com.aspose.pdf.TextFragment-) | <p> Añade un fragmento de texto a la página Pdf </p> <hr> <pre> El ejemplo muestra cómo crear un objeto de fragmento de texto, personalizar sus segmentos de texto y añadirlo a la página Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.Position = new Position(100, 600); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GREY); tf.getTextState().setForegroundColor ( Color.Red); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments.add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |
| [getSegmenter](#getSegmenter--) | Obtiene el objeto TextSegmenter |

### TextBuilder {#TextBuilder-com.aspose.pdf.Page-}
<p> Inicializa una nueva instancia de la clase {@code TextBuilder} para la página Pdf. </p>

### TextBuilder {#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-}
Inicializa una nueva instancia de la clase {@code TextBuilder} para la página Pdf.

### appendParagraph {#appendParagraph-com.aspose.pdf.TextParagraph-}
<p> Añade un párrafo de texto a la página Pdf. </p> <hr> <pre> El ejemplo muestra cómo crear un objeto de párrafo de texto y añadirlo a la página Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre>

### appendParagraph {#appendParagraph-com.aspose.pdf.TextParagraph-int-}
Añade párrafo con rotación

### appendText {#appendText-java.util.List-}
Añade una lista de fragmentos de texto a la página Pdf.

### appendText {#appendText-com.aspose.pdf.TextFragment-}
<p> Añade un fragmento de texto a la página Pdf </p> <hr> <pre> El ejemplo muestra cómo crear un objeto de fragmento de texto, personalizar sus segmentos de texto y añadirlo a la página Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.Position = new Position(100, 600); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GREY); tf.getTextState().setForegroundColor ( Color.Red); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments.add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### getSegmenter {#getSegmenter--}
```
public com.aspose.pdf.engine.commondata.text.segmenting.TextSegmenter getSegmenter()
```

Obtiene el objeto TextSegmenter

**Returns:**
Objeto TextSegmenter
