---
title: "TextBuilder"
linktitle: "TextBuilder"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Menambahkan objek teks ke halaman Pdf."
type: docs
weight: 4940
url: /id/java/com.aspose.pdf/textbuilder/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextBuilder

```
public final class TextBuilder extends Object
```

Menambahkan objek teks ke halaman Pdf.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextBuilder](#TextBuilder-com.aspose.pdf.Page-) | <p> Menginisialisasi instance baru dari kelas {@code TextBuilder} untuk halaman Pdf. </p> |
| [TextBuilder](#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-) | Menginisialisasi instance baru dari kelas {@code TextBuilder} untuk halaman Pdf. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [appendParagraph](#appendParagraph-com.aspose.pdf.TextParagraph-) | <p> Menambahkan paragraf teks ke halaman Pdf. </p> <hr> <pre> Contoh ini menunjukkan cara membuat objek paragraf teks dan menambahkannya ke halaman Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre> |
| [appendParagraph](#appendParagraph-com.aspose.pdf.TextParagraph-int-) | Menambahkan paragraf dengan rotasi |
| [appendText](#appendText-java.util.List-) | Menambahkan daftar fragmen teks ke halaman Pdf. |
| [appendText](#appendText-com.aspose.pdf.TextFragment-) | <p> Menambahkan fragmen teks ke halaman Pdf </p> <hr> <pre> Contoh ini menunjukkan cara membuat objek fragmen teks, menyesuaikan segmen teksnya, dan menambahkannya ke halaman Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.Position = new Position(100, 600); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GREY); tf.getTextState().setForegroundColor ( Color.Red); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments.add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |
| [getSegmenter](#getSegmenter--) | Mendapatkan objek TextSegmenter |

### TextBuilder {#TextBuilder-com.aspose.pdf.Page-}
<p> Menginisialisasi instance baru dari kelas {@code TextBuilder} untuk halaman Pdf. </p>

### TextBuilder {#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-}
Menginisialisasi instance baru dari kelas {@code TextBuilder} untuk halaman Pdf.

### appendParagraph {#appendParagraph-com.aspose.pdf.TextParagraph-}
<p> Menambahkan paragraf teks ke halaman Pdf. </p> <hr> <pre> Contoh ini menunjukkan cara membuat objek paragraf teks dan menambahkannya ke halaman Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre>

### appendParagraph {#appendParagraph-com.aspose.pdf.TextParagraph-int-}
Menambahkan paragraf dengan rotasi

### appendText {#appendText-java.util.List-}
Menambahkan daftar fragmen teks ke halaman Pdf.

### appendText {#appendText-com.aspose.pdf.TextFragment-}
<p> Menambahkan fragmen teks ke halaman Pdf </p> <hr> <pre> Contoh ini menunjukkan cara membuat objek fragmen teks, menyesuaikan segmen teksnya, dan menambahkannya ke halaman Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.Position = new Position(100, 600); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GREY); tf.getTextState().setForegroundColor ( Color.Red); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments.add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### getSegmenter {#getSegmenter--}
```
public com.aspose.pdf.engine.commondata.text.segmenting.TextSegmenter getSegmenter()
```

Mendapatkan objek TextSegmenter

**Returns:**
Objek TextSegmenter
