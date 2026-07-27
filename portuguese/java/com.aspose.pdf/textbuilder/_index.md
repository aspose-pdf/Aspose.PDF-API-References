---
title: "TextBuilder"
linktitle: "TextBuilder"
second_title: "Referência da API Aspose.PDF para Java"
description: "Anexa objeto de texto à página Pdf."
type: docs
weight: 4940
url: /pt/java/com.aspose.pdf/textbuilder/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextBuilder

```
public final class TextBuilder extends Object
```

Anexa objeto de texto à página Pdf.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextBuilder](#TextBuilder-com.aspose.pdf.Page-) | <p> Inicializa uma nova instância da classe {@code TextBuilder} para a página Pdf. </p> |
| [TextBuilder](#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-) | Inicializa uma nova instância da classe {@code TextBuilder} para a página Pdf. |

## Métodos

| Método | Descrição |
| --- | --- |
| [appendParagraph](#appendParagraph-com.aspose.pdf.TextParagraph-) | <p> Anexa um parágrafo de texto à página Pdf. </p> <hr> <pre> The example demonstrates how to create text paragraph object and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre> |
| [appendParagraph](#appendParagraph-com.aspose.pdf.TextParagraph-int-) | Anexa parágrafo com rotação |
| [appendText](#appendText-java.util.List-) | Anexa lista de fragmentos de texto à página Pdf. |
| [appendText](#appendText-com.aspose.pdf.TextFragment-) | <p> Anexa fragmento de texto à página Pdf </p> <hr> <pre> The example demonstrates how to create text fragment object, customize it's text segments and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.Position = new Position(100, 600); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GREY); tf.getTextState().setForegroundColor ( Color.Red); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments.add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |
| [getSegmenter](#getSegmenter--) | Obtém o objeto TextSegmenter |

### TextBuilder {#TextBuilder-com.aspose.pdf.Page-}
<p> Inicializa uma nova instância da classe {@code TextBuilder} para a página Pdf. </p>

### TextBuilder {#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-}
Inicializa uma nova instância da classe {@code TextBuilder} para a página Pdf.

### appendParagraph {#appendParagraph-com.aspose.pdf.TextParagraph-}
<p> Anexa um parágrafo de texto à página Pdf. </p> <hr> <pre> The example demonstrates how to create text paragraph object and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre>

### appendParagraph {#appendParagraph-com.aspose.pdf.TextParagraph-int-}
Anexa parágrafo com rotação

### appendText {#appendText-java.util.List-}
Anexa lista de fragmentos de texto à página Pdf.

### appendText {#appendText-com.aspose.pdf.TextFragment-}
<p> Anexa fragmento de texto à página Pdf </p> <hr> <pre> The example demonstrates how to create text fragment object, customize it's text segments and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.Position = new Position(100, 600); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GREY); tf.getTextState().setForegroundColor ( Color.Red); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments.add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### getSegmenter {#getSegmenter--}
```
public com.aspose.pdf.engine.commondata.text.segmenting.TextSegmenter getSegmenter()
```

Obtém o objeto TextSegmenter

**Returns:**
Objeto TextSegmenter
