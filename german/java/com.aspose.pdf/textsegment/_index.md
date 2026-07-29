---
title: "TextSegment"
linktitle: "TextSegment"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt ein Segment von Pdf-Text dar. </p> <hr> <pre> Das Beispiel demonstriert, wie man die Textfarbe und Schriftgröße des Textes mit dem {@code TextState}-Objekt von {@code ändert."
type: docs
weight: 5300
url: /de/java/com.aspose.pdf/textsegment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextSegment

```
public final class TextSegment extends Object
```

<p> Stellt ein Segment von Pdf-Text dar. </p> <hr> <pre> Das Beispiel demonstriert, wie man die Textfarbe und Schriftgröße des Textes mit dem {@code TextState}-Objekt des {@code TextSegment}-Objekts ändert. // Dokument öffnen Document doc = new Document("D:\\Tests\\input.pdf"); // Erstelle TextFragmentAbsorber-Objekt, um alle Vorkommen des Textes "hello world" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Akzeptiere den Absorber für die erste Seite doc.getPages().get(1).accept(absorber); // Ändere die Vordergrundfarbe des ersten Textsegments des ersten Textvorkommens absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Ändere die Schriftgröße des ersten Textsegments des ersten Textvorkommens absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Dokument speichern doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <pre> Kurz gesagt, {@code TextSegment}-Objekte sind Kindobjekte des {@code TextFragment}-Objekts. Im Detail: Der Text eines PDF-Dokuments in {@code Aspose.Pdf} wird durch zwei Grundobjekte dargestellt: {@code TextFragment} und {@code TextSegment}. Die Unterschiede zwischen ihnen sind größtenteils kontextabhängig. Betrachten wir das folgende Szenario. Der Benutzer sucht den Text "hello world", um damit zu arbeiten, seine Eigenschaften zu ändern, ihn anzusehen usw. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> Die physische Darstellung von PDF-Text ist sehr komplex. Der Text "hello world" kann aus mehreren physisch unabhängigen Textsegmenten bestehen. Das Aspose.PDF-Textmodell legt im Wesentlichen fest, dass das {@code TextFragment}-Objekt einen einzigen logischen Vorgangssatz über dem physischen {@code TextSegment}-Objekt-Set bereitstellt, das die Benutzerabfrage repräsentiert. Im Textsuch‑Szenario ist {@code TextFragment} die logische "hello world"-Textdarstellung, und die {@code TextSegment}-Objektsammlungen repräsentieren alle physischen Segmente, die das "hello world"-Textobjekt bilden. Daher ist {@code TextFragment} der logischen Textdarstellung nahe, und {@code TextSegment} ist der physischen Textdarstellung nahe. Offensichtlich kann jedes {@code TextSegment}-Objekt seine eigene Schriftart, Färbung und Positionierungseigenschaften besitzen. {@code TextFragment} bietet eine einfache Möglichkeit, den Text mit seinen Eigenschaften zu ändern: Schriftart setzen, Schriftgröße setzen, Schriftfarbe setzen usw. Gleichzeitig sind {@code TextSegment}-Objekte zugänglich und Benutzer können mit {@code TextSegment}-Objekten unabhängig arbeiten. </p>

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextSegment](#TextSegment--) | <p> Erstellt ein TextSegment-Objekt. </p> <hr> <pre> Das Beispiel zeigt, wie man ein TextFragment-Objekt erstellt, ein TextSegment zur TextFragment‑Sammlung hinzufügt und es an die PDF‑Seite anhängt. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // Textfragment erstellen TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // seine Texteigenschaften festlegen tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // ein weiteres Segment zur Segments‑Sammlung des TextFragments hinzufügen TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // TextBuilder-Objekt erstellen TextBuilder builder = new TextBuilder(page); // das TextFragment an die PDF‑Seite anhängen builder.appendText(tf); // Dokument speichern doc.save(outFile); </pre> |
| [TextSegment](#TextSegment-java.lang.String-) | <p> Erstellt ein TextSegment-Objekt. </p> <hr> <pre> Das Beispiel zeigt, wie man ein TextFragment-Objekt erstellt, ein TextSegment zur TextFragment‑Sammlung hinzufügt und es an die PDF‑Seite anhängt. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // Textfragment erstellen TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // seine Texteigenschaften festlegen tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // ein weiteres Segment zur Segments‑Sammlung des TextFragments hinzufügen TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // TextBuilder-Objekt erstellen TextBuilder builder = new TextBuilder(page); // das TextFragment an die PDF‑Seite anhängen builder.appendText(tf); // Dokument speichern doc.save(outFile); </pre> |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBaselinePosition](#getBaselinePosition--) | Ermittelt die Textposition für Text, dargestellt durch ein {@code TextSegment}-Objekt. Der YIndent der Position‑Struktur stellt die Grundlinienkoordinate des Textsegments dar. |
| [getCharacters](#getCharacters--) | Ermittelt die Sammlung von CharInfo-Objekten, die Informationen zu den Zeichen im Textsegment enthalten. |
| [getEndCharIndex](#getEndCharIndex--) | Ermittelt den Endzeichenindex des aktuellen Segments im Show‑Text‑Operator (Tj, TJ)-Segment. |
| [getHyperlink](#getHyperlink--) | Liest oder setzt den Segment‑Hyperlink (für PDF‑Generator). |
| [getPosition](#getPosition--) | Ermittelt die Textposition für Text, dargestellt durch ein {@code TextSegment}-Objekt. |
| [getRectangle](#getRectangle--) | Ermittelt das Rechteck des TextSegment. |
| [getStartCharIndex](#getStartCharIndex--) | Ermittelt den Startzeichenindex des aktuellen Segments im Show‑Text‑Operator (Tj, TJ)-Segment. |
| [getText](#getText--) | Ermittelt das {@code string}-Textobjekt, das das {@code TextSegment}-Objekt darstellt. |
| [getTextEditOptions](#getTextEditOptions--) | Liefert die Textbearbeitungsoptionen. Die Optionen definieren ein spezielles Verhalten, wenn das gewünschte Symbol nicht mit der Schriftart geschrieben werden kann. |
| [getTextState](#getTextState--) | <p> Liest oder setzt den Textzustand für den Text, den das {@code TextSegment}-Objekt darstellt. </p> <hr> <p> Bietet eine Möglichkeit, die folgenden Eigenschaften des Textes zu ändern: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | Setzt die Textposition für Text, dargestellt durch ein {@code TextSegment}-Objekt. Der YIndent der Position‑Struktur stellt die Grundlinienkoordinate des Textsegments dar. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Liest oder setzt den Segment‑Hyperlink (für PDF‑Generator). |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | Setzt die Textposition für Text, dargestellt durch ein {@code TextSegment}-Objekt. |
| [setText](#setText-java.lang.String-) | Setzt das {@code string}-Textobjekt, das das {@code TextSegment}-Objekt darstellt. |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Setzt die Textbearbeitungsoptionen. Die Optionen definieren ein spezielles Verhalten, wenn das gewünschte Symbol nicht mit der Schriftart geschrieben werden kann. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | <p> Setzt den Textzustand für den Text, den das {@code TextSegment}-Objekt darstellt. </p> <hr> <p> Bietet eine Möglichkeit, die folgenden Eigenschaften des Textes zu ändern: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setTextSuppressedUpdate](#setTextSuppressedUpdate-java.lang.String-) | Setzt das {@code string}-Textobjekt, das das {@code TextSegment}-Objekt darstellt, mit unterdrücktem Update. |

### TextSegment {#TextSegment--}
```
public TextSegment()
```

<p> Erstellt ein TextSegment-Objekt. </p> <hr> <pre> Das Beispiel zeigt, wie man ein TextFragment-Objekt erstellt, ein TextSegment zur TextFragment‑Sammlung hinzufügt und es an die PDF‑Seite anhängt. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // Textfragment erstellen TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // seine Texteigenschaften festlegen tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // ein weiteres Segment zur Segments‑Sammlung des TextFragments hinzufügen TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // TextBuilder-Objekt erstellen TextBuilder builder = new TextBuilder(page); // das TextFragment an die PDF‑Seite anhängen builder.appendText(tf); // Dokument speichern doc.save(outFile); </pre>

### TextSegment {#TextSegment-java.lang.String-}
<p> Erstellt ein TextSegment-Objekt. </p> <hr> <pre> Das Beispiel zeigt, wie man ein TextFragment-Objekt erstellt, ein TextSegment zur TextFragment‑Sammlung hinzufügt und es an die PDF‑Seite anhängt. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // Textfragment erstellen TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // seine Texteigenschaften festlegen tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // ein weiteres Segment zur Segments‑Sammlung des TextFragments hinzufügen TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // TextBuilder-Objekt erstellen TextBuilder builder = new TextBuilder(page); // das TextFragment an die PDF‑Seite anhängen builder.appendText(tf); // Dokument speichern doc.save(outFile); </pre>

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

Ermittelt die Textposition für Text, dargestellt durch ein {@code TextSegment}-Objekt. Der YIndent der Position‑Struktur stellt die Grundlinienkoordinate des Textsegments dar.

**Returns:**
Positionswert

### getCharacters {#getCharacters--}
```
public CharInfoCollection getCharacters()
```

Ermittelt die Sammlung von CharInfo-Objekten, die Informationen zu den Zeichen im Textsegment enthalten.

**Returns:**
CharInfoCollection-Objekt

### getEndCharIndex {#getEndCharIndex--}
```
public int getEndCharIndex()
```

Ermittelt den Endzeichenindex des aktuellen Segments im Show‑Text‑Operator (Tj, TJ)-Segment.

**Returns:**
int-Wert

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

Liest oder setzt den Segment‑Hyperlink (für PDF‑Generator).

**Returns:**
Hyperlink-Objekt

### getPosition {#getPosition--}
```
public Position getPosition()
```

Ermittelt die Textposition für Text, dargestellt durch ein {@code TextSegment}-Objekt.

**Returns:**
Positionswert

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Ermittelt das Rechteck des TextSegment.

**Returns:**
Rectangle-Objekt

### getStartCharIndex {#getStartCharIndex--}
```
public int getStartCharIndex()
```

Ermittelt den Startzeichenindex des aktuellen Segments im Show‑Text‑Operator (Tj, TJ)-Segment.

**Returns:**
int-Wert

### getText {#getText--}
```
public String getText()
```

Ermittelt das {@code string}-Textobjekt, das das {@code TextSegment}-Objekt darstellt.

**Returns:**
String Wert

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Liefert die Textbearbeitungsoptionen. Die Optionen definieren ein spezielles Verhalten, wenn das gewünschte Symbol nicht mit der Schriftart geschrieben werden kann.

**Returns:**
TextEditOptions-Wert

### getTextState {#getTextState--}
```
public TextState getTextState()
```

<p> Liest oder setzt den Textzustand für den Text, den das {@code TextSegment}-Objekt darstellt. </p> <hr> <p> Bietet eine Möglichkeit, die folgenden Eigenschaften des Textes zu ändern: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

**Returns:**
TextState-Wert

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
Setzt die Textposition für Text, dargestellt durch ein {@code TextSegment}-Objekt. Der YIndent der Position‑Struktur stellt die Grundlinienkoordinate des Textsegments dar.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Liest oder setzt den Segment‑Hyperlink (für PDF‑Generator).

### setPosition {#setPosition-com.aspose.pdf.Position-}
Setzt die Textposition für Text, dargestellt durch ein {@code TextSegment}-Objekt.

### setText {#setText-java.lang.String-}
Setzt das {@code string}-Textobjekt, das das {@code TextSegment}-Objekt darstellt.

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Setzt die Textbearbeitungsoptionen. Die Optionen definieren ein spezielles Verhalten, wenn das gewünschte Symbol nicht mit der Schriftart geschrieben werden kann.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
<p> Setzt den Textzustand für den Text, den das {@code TextSegment}-Objekt darstellt. </p> <hr> <p> Bietet eine Möglichkeit, die folgenden Eigenschaften des Textes zu ändern: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

### setTextSuppressedUpdate {#setTextSuppressedUpdate-java.lang.String-}
Setzt das {@code string}-Textobjekt, das das {@code TextSegment}-Objekt darstellt, mit unterdrücktem Update.
