---
title: "TextBuilder"
linktitle: "TextBuilder"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Fügt ein Textobjekt zu einer PDF-Seite hinzu."
type: docs
weight: 4940
url: /de/java/com.aspose.pdf/textbuilder/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextBuilder

```
public final class TextBuilder extends Object
```

Fügt ein Textobjekt zu einer PDF-Seite hinzu.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextBuilder](#TextBuilder-com.aspose.pdf.Page-) | <p> Initialisiert eine neue Instanz der {@code TextBuilder}-Klasse für die Pdf-Seite. </p> |
| [TextBuilder](#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-) | Initialisiert eine neue Instanz der {@code TextBuilder}-Klasse für die Pdf-Seite. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [appendParagraph](#appendParagraph-com.aspose.pdf.TextParagraph-) | <p> Fügt Textabsatz zur Pdf-Seite hinzu. </p> <hr> <pre> Das Beispiel zeigt, wie man ein Textabsatz-Objekt erstellt und es zur Pdf-Seite hinzufügt. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // Textabsatz erstellen TextParagraph paragraph = new TextParagraph(); // das Rechteck des Absatzes festlegen paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // Optionen für den Zeilenumbruch festlegen paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // Zeichenkettenzeilen anhängen paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // den Absatz mit dem TextBuilder zur Pdf-Seite hinzufügen TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // PDF-Dokument speichern doc.save(outFile); </pre> |
| [appendParagraph](#appendParagraph-com.aspose.pdf.TextParagraph-int-) | Fügt Absatz mit Drehung hinzu |
| [appendText](#appendText-java.util.List-) | Fügt Liste von Textfragmenten zur Pdf-Seite hinzu. |
| [appendText](#appendText-com.aspose.pdf.TextFragment-) | <p> Fügt Textfragment zur Pdf-Seite hinzu </p> <hr> <pre> Das Beispiel zeigt, wie man ein Textfragment-Objekt erstellt, seine Textsegmente anpasst und es zur Pdf-Seite hinzufügt. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // Textfragment erstellen TextFragment tf = new TextFragment("main text"); tf.Position = new Position(100, 600); // seine Texteigenschaften festlegen tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GREY); tf.getTextState().setForegroundColor ( Color.Red); // ein weiteres Segment zur Segments-Sammlung des Textfragments hinzufügen TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments.add(segment2); // TextBuilder-Objekt erstellen TextBuilder builder = new TextBuilder(page); // das Textfragment zur Pdf-Seite hinzufügen builder.appendText(tf); // Dokument speichern doc.save(outFile); </pre> |
| [getSegmenter](#getSegmenter--) | Liefert TextSegmenter-Objekt |

### TextBuilder {#TextBuilder-com.aspose.pdf.Page-}
<p> Initialisiert eine neue Instanz der {@code TextBuilder}-Klasse für die Pdf-Seite. </p>

### TextBuilder {#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-}
Initialisiert eine neue Instanz der {@code TextBuilder}-Klasse für die Pdf-Seite.

### appendParagraph {#appendParagraph-com.aspose.pdf.TextParagraph-}
<p> Fügt Textabsatz zur Pdf-Seite hinzu. </p> <hr> <pre> Das Beispiel zeigt, wie man ein Textabsatz-Objekt erstellt und es zur Pdf-Seite hinzufügt. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // Textabsatz erstellen TextParagraph paragraph = new TextParagraph(); // das Rechteck des Absatzes festlegen paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // Optionen für den Zeilenumbruch festlegen paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // Zeichenkettenzeilen anhängen paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // den Absatz mit dem TextBuilder zur Pdf-Seite hinzufügen TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // PDF-Dokument speichern doc.save(outFile); </pre>

### appendParagraph {#appendParagraph-com.aspose.pdf.TextParagraph-int-}
Fügt Absatz mit Drehung hinzu

### appendText {#appendText-java.util.List-}
Fügt Liste von Textfragmenten zur Pdf-Seite hinzu.

### appendText {#appendText-com.aspose.pdf.TextFragment-}
<p> Fügt Textfragment zur Pdf-Seite hinzu </p> <hr> <pre> Das Beispiel zeigt, wie man ein Textfragment-Objekt erstellt, seine Textsegmente anpasst und es zur Pdf-Seite hinzufügt. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // Textfragment erstellen TextFragment tf = new TextFragment("main text"); tf.Position = new Position(100, 600); // seine Texteigenschaften festlegen tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GREY); tf.getTextState().setForegroundColor ( Color.Red); // ein weiteres Segment zur Segments-Sammlung des Textfragments hinzufügen TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments.add(segment2); // TextBuilder-Objekt erstellen TextBuilder builder = new TextBuilder(page); // das Textfragment zur Pdf-Seite hinzufügen builder.appendText(tf); // Dokument speichern doc.save(outFile); </pre>

### getSegmenter {#getSegmenter--}
```
public com.aspose.pdf.engine.commondata.text.segmenting.TextSegmenter getSegmenter()
```

Liefert TextSegmenter-Objekt

**Returns:**
TextSegmenter-Objekt
