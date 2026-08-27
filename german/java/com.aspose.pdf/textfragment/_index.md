---
title: "TextFragment"
linktitle: "TextFragment"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt ein Fragment von PDF-Text dar. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text sowie dessen Schriftart ersetzt. // Open document."
type: docs
weight: 5110
url: /de/java/com.aspose.pdf/textfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class TextFragment extends BaseParagraph
```

<p> Stellt ein Fragment von PDF-Text dar. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite eines PDF-Dokuments findet und den Text sowie seine Schriftart ersetzt. // Dokument öffnen Document doc = new Document(\"input.pdf\"); // Schriftart finden, die zum Ändern der Textschriftart des Dokuments verwendet wird Font font = FontRepository.findFont(\"Arial\"); // TextFragmentAbsorber-Objekt erstellen, um alle Vorkommen des Textes \"hello world\" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Absorber für die erste Seite akzeptieren doc.getPages().get(1).accept(absorber); // Text und Schriftart des ersten Textvorkommens ändern absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Dokument speichern doc.save(\"output.pdf\"); </pre> <hr> <pre> In wenigen Worten enthält das {@code TextFragment}-Objekt eine Liste von {@code TextSegment}-Objekten. Im Detail: Der Text eines PDF-Dokuments in {@code com.aspose.pdf} wird durch zwei Grundobjekte dargestellt: {@code TextFragment} und {@code TextSegment} Die Unterschiede zwischen ihnen sind größtenteils kontextabhängig. Betrachten wir das folgende Szenario. Der Benutzer sucht nach dem Text \"hello world\", um damit zu arbeiten, seine Eigenschaften zu ändern, ihn anzusehen usw. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); doc.getPages().get(1).accept(absorber); </pre> Die physische Darstellung von PDF-Text ist sehr komplex. Der Text \"hello world\" kann aus mehreren physisch unabhängigen Textsegmenten bestehen. Das Aspose.Pdf-Textmodell legt im Wesentlichen fest, dass das {@code TextFragment}-Objekt einen einzelnen logischen Operationssatz über einer Menge physischer {@code TextSegment}-Objekte bereitstellt, die die Benutzeranfrage repräsentieren. Im Textsuchszenario ist {@code TextFragment} die logische Darstellung des Textes \"hello world\", und die {@code TextSegment}-Objektsammlungen repräsentieren alle physischen Segmente, die das \"hello world\"-Textobjekt bilden. Damit ist {@code TextFragment} nahe an der logischen Textdarstellung. Und {@code TextSegment} ist nahe an der physischen Textdarstellung. Offensichtlich kann jedes {@code TextSegment}-Objekt seine eigene Schriftart, Farbgebung und Positionierungseigenschaften besitzen. {@code TextFragment} bietet eine einfache Möglichkeit, Text mit seinen Eigenschaften zu ändern: Schriftart festlegen, Schriftgröße festlegen, Schriftfarbe festlegen usw. Gleichzeitig sind {@code TextSegment}-Objekte zugänglich und Benutzer können mit {@code TextSegment}-Objekten unabhängig arbeiten. <p> Hinweis darauf, dass das Ändern von TextFragment-Eigenschaften die innere {@code Segments}-Sammlung verändern kann, weil TextFragment ein Aggregatobjekt ist und interne Segmente neu anordnen oder zu einem einzelnen Segment zusammenführen kann. Wenn Ihre Anforderung darin besteht, die {@code Segments}-Sammlung unverändert zu lassen, ändern Sie bitte die internen Segmente einzeln. </p>

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextFragment](#TextFragment--) | Initialisiert eine neue Instanz des {@code TextFragment}-Objekts. |
| [TextFragment](#TextFragment-java.lang.String-) | Initialisiert eine neue Instanz des {@code TextFragment}-Objekts. |
| [TextFragment](#TextFragment-java.lang.String-com.aspose.pdf.TabStops-) | Initialisiert eine neue Instanz des {@code TextFragment}-Objekts. |
| [TextFragment](#TextFragment-com.aspose.pdf.TabStops-) | Initialisiert eine neue Instanz des {@code TextFragment}-Objekts. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | Klonen Sie das Fragment mit allen Segmenten. |
| [deepClone](#deepClone--) | Kopiere das Fragment. |
| [getBaselinePosition](#getBaselinePosition--) | Ermittelt die Textposition für den Text, dargestellt mit {@code TextFragment}-Objekt. Der YIndent der Position-Struktur stellt die Grundlinienkoordinate des Textfragments dar. |
| [getEndNote](#getEndNote--) | Ermittelt die Absatz-Endnotiz.(nur für PDF-Erstellung) |
| [getFootNote](#getFootNote--) | Ermittelt die Absatz-Fußnotiz.(nur für PDF-Erstellung) |
| [getForm](#getForm--) | Ermittelt das Formularobjekt, das das TextFragment enthält. Der Wert kann null sein, falls das TextFragment-Objekt nicht zu einem Formular gehört. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Ermittelt die horizontale Ausrichtung des Textfragments. |
| [getPage](#getPage--) | Ermittelt die Seite, die das TextFragment enthält. Der Wert kann null sein, falls das TextFragment-Objekt zu keiner Seite gehört. |
| [getPosition](#getPosition--) | <p> Ermittelt die Textposition für den Text, dargestellt mit {@code TextFragment}-Objekt. </p> |
| [getRectangle](#getRectangle--) | Ermittelt das Rechteck des TextFragments |
| [getReplaceOptions](#getReplaceOptions--) | Ermittelt die Optionen zum Ersetzen von Text. Die Optionen definieren das Verhalten, wenn der Fragmenttext durch einen kürzeren/längeren Text ersetzt wird. |
| [getSegments](#getSegments--) | <p> Ermittelt Textsegmente für das aktuelle {@code TextFragment}. </p> |
| [getText](#getText--) | <p> Ermittelt das {@code string}-Textobjekt, das das {@code TextFragment}-Objekt darstellt. </p> |
| [getTextEditOptions](#getTextEditOptions--) | Ermittelt oder legt Textbearbeitungsoptionen fest. Die Optionen definieren ein spezielles Verhalten, wenn das angeforderte Symbol nicht mit der Schriftart geschrieben werden kann. |
| [getTextState](#getTextState--) | <p> Ermittelt oder legt den Textzustand für den Text fest, den das {@code TextFragment}-Objekt darstellt. </p> |
| [getVerticalAlignment](#getVerticalAlignment--) | Ermittelt die vertikale Ausrichtung des Textfragments. |
| [getWrapLinesCount](#getWrapLinesCount--) | Ermittelt die Anzahl der Umbruchzeilen für diesen Absatz.(nur für PDF-Erstellung) |
| [isolateTextSegments](#isolateTextSegments-int-int-) | Ermittelt {@code TextSegment}(e), die den angegebenen Teil des {@code TextFragment}-Texts darstellen. |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | Legt die Textposition für den Text fest, dargestellt mit {@code TextFragment}-Objekt. Der YIndent der Position-Struktur stellt die Grundlinienkoordinate des Textfragments dar. |
| [setEndNote](#setEndNote-com.aspose.pdf.Note-) | Legt die Absatz-Endnotiz fest.(nur für PDF-Erstellung) |
| [setFootNote](#setFootNote-com.aspose.pdf.Note-) | Legt die Absatz-Fußnotiz fest.(nur für PDF-Erstellung) |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Legt die horizontale Ausrichtung des Textfragments fest. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Legt den Hyperlink des Fragments fest |
| [setMarkedContentProperties](#setMarkedContentProperties-java.lang.String-int-) |  |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | <p> Legt die Textposition für den Text fest, dargestellt mit {@code TextFragment}-Objekt. </p> |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Ermittelt das Rechteck des TextFragments |
| [setSegments](#setSegments-com.aspose.pdf.TextSegmentCollection-) | Stellt die setSegments-Methode dar |
| [setText](#setText-java.lang.String-) | <p> Legt das {@code string}-Textobjekt fest, das das {@code TextFragment}-Objekt darstellt. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Ermittelt oder legt Textbearbeitungsoptionen fest. Die Optionen definieren ein spezielles Verhalten, wenn das angeforderte Symbol nicht mit der Schriftart geschrieben werden kann. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Legt eine vertikale Ausrichtung des Textfragmentes fest. |
| [setWrapLinesCount](#setWrapLinesCount-int-) | Legt die Anzahl der Zeilenumbrüche für diesen Absatz fest (nur für PDF-Erstellung) |

### TextFragment {#TextFragment--}
```
public TextFragment()
```

Initialisiert eine neue Instanz des {@code TextFragment}-Objekts.

### TextFragment {#TextFragment-java.lang.String-}
Initialisiert eine neue Instanz des {@code TextFragment}-Objekts.

### TextFragment {#TextFragment-java.lang.String-com.aspose.pdf.TabStops-}
Initialisiert eine neue Instanz des {@code TextFragment}-Objekts.

### TextFragment {#TextFragment-com.aspose.pdf.TabStops-}
Initialisiert eine neue Instanz des {@code TextFragment}-Objekts.

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

Klonen Sie das Fragment mit allen Segmenten.

**Returns:**
Das geklonte Objekt

### deepClone {#deepClone--}
```
public Object deepClone()
```

Kopiere das Fragment.

**Returns:**
Das geklonte Objekt

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

Ermittelt die Textposition für den Text, dargestellt mit {@code TextFragment}-Objekt. Der YIndent der Position-Struktur stellt die Grundlinienkoordinate des Textfragments dar.

**Returns:**
Positionswert

### getEndNote {#getEndNote--}
```
public Note getEndNote()
```

Ermittelt die Absatz-Endnotiz.(nur für PDF-Erstellung)

**Returns:**
Hinweiswert

### getFootNote {#getFootNote--}
```
public Note getFootNote()
```

Ermittelt die Absatz-Fußnotiz.(nur für PDF-Erstellung)

**Returns:**
Hinweiswert

### getForm {#getForm--}
```
public XForm getForm()
```

Ermittelt das Formularobjekt, das das TextFragment enthält. Der Wert kann null sein, falls das TextFragment-Objekt nicht zu einem Formular gehört.

**Returns:**
XForm-Wert

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Ermittelt die horizontale Ausrichtung des Textfragments.

**Returns:**
HorizontalAlignment-Wert @see HorizontalAlignment

### getPage {#getPage--}
```
public Page getPage()
```

Ermittelt die Seite, die das TextFragment enthält. Der Wert kann null sein, falls das TextFragment-Objekt zu keiner Seite gehört.

**Returns:**
Page-Objekt

### getPosition {#getPosition--}
```
public Position getPosition()
```

<p> Ermittelt die Textposition für den Text, dargestellt mit {@code TextFragment}-Objekt. </p>

**Returns:**
Positionswert <hr> <pre> Das Beispiel zeigt, wie die Platzierung eines Textes, dargestellt durch das {@code TextFragment}-Objekt, angezeigt wird. // Öffne Dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Erstelle TextFragmentAbsorber-Objekt, um alle Vorkommen des Textes "hello world" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Akzeptiere den Absorber für die erste Seite doc.getPages().get(1).accept(absorber); // Zeige Text- und Platzierungsinformationen des ersten Textvorkommens an TextFragment firstOccurrence = absorber.getTextFragments().get_Item(1); System.out.println("fragment text: " + firstOccurrence.getText())); System.out.println("fragment X indent: "+ firstOccurrence.getPosition().getXIndent())); System.out.println("fragment Y indent: "+ firstOccurrence.getPosition().getYIndent())); </pre> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Ermittelt das Rechteck des TextFragments

**Returns:**
Rectangle-Objekt

### getReplaceOptions {#getReplaceOptions--}
```
public final TextReplaceOptions getReplaceOptions()
```

Ermittelt die Optionen zum Ersetzen von Text. Die Optionen definieren das Verhalten, wenn der Fragmenttext durch einen kürzeren/längeren Text ersetzt wird.

**Returns:**
TextReplaceOptions-Instanz

### getSegments {#getSegments--}
```
public TextSegmentCollection getSegments()
```

<p> Ermittelt Textsegmente für das aktuelle {@code TextFragment}. </p>

**Returns:**
TextSegmentCollection-Wert <hr> <pre> Das Beispiel zeigt, wie man alle {@code TextSegment}-Objekte innerhalb des {@code TextFragment} navigiert. // Öffne Dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Erstelle TextFragmentAbsorber-Objekt, um alle Vorkommen des Textes "hello world" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Akzeptiere den Absorber für die erste Seite doc.getPages().get(1).accept(absorber); // Navigiere durch alle Textsegmente und gib deren Text- und Platzierungsinformationen aus for (TextSegment segment : ({@code Iterable<TextSegment>})absorber.getTextFragments().get_Item(1).getSegments()) { System.out.println("segment text: "+ segment.getText())); System.out.println("segment X indent: "+ segment.getPosition().getXIndent())); System.out.println("segment Y indent: "+ segment.getPosition().getYIndent())); } </pre> <hr> <p> Kurz gesagt, {@code TextSegment}-Objekte sind Kinder des {@code TextFragment}-Objekts. Fortgeschrittene Benutzer können direkt auf Segmente zugreifen, um komplexere Textbearbeitungsszenarien durchzuführen. Weitere Details finden Sie in der Beschreibung des {@code TextFragment}-Objekts. </p> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getText {#getText--}
```
public String getText()
```

<p> Ermittelt das {@code string}-Textobjekt, das das {@code TextFragment}-Objekt darstellt. </p>

**Returns:**
String-Wert <hr> <pre> Das Beispiel zeigt, wie man einen Text sucht und das erste Vorkommen, das durch ein {@code TextFragment}-Objekt dargestellt wird, ersetzt. // Öffne Dokument Document doc = new Document("D:\\Tests\\input.pdf"); // Erstelle TextFragmentAbsorber-Objekt, um alle Vorkommen des Textes "hello world" zu finden TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Akzeptiere den Absorber für die erste Seite doc.getPages().get(1).accept(absorber); // Ändere die Schrift des ersten Textvorkommens absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Speichere das Dokument doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

### getTextEditOptions {#getTextEditOptions--}
```
public final TextEditOptions getTextEditOptions()
```

Ermittelt oder legt Textbearbeitungsoptionen fest. Die Optionen definieren ein spezielles Verhalten, wenn das angeforderte Symbol nicht mit der Schriftart geschrieben werden kann.

**Returns:**
TextEditOptions-Instanz

### getTextState {#getTextState--}
```
public TextFragmentState getTextState()
```

<p> Ermittelt oder legt den Textzustand für den Text fest, den das {@code TextFragment}-Objekt darstellt. </p>

**Returns:**
TextFragmentState-Objekt <hr> <pre> Das Beispiel zeigt, wie man die Textfarbe und Schriftgröße des Textes mit dem {@code TextState}-Objekt ändert. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setForegroundColor(Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Bietet eine Möglichkeit, die folgenden Eigenschaften des Textes zu ändern: Font FontSize FontStyle ForegroundColor BackgroundColor </p> @see TextFragmentAbsorber @see IDocument

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Ermittelt die vertikale Ausrichtung des Textfragments.

**Returns:**
int-Wert @see VerticalAlignment

### getWrapLinesCount {#getWrapLinesCount--}
```
public int getWrapLinesCount()
```

Ermittelt die Anzahl der Umbruchzeilen für diesen Absatz.(nur für PDF-Erstellung)

**Returns:**
int-Wert

### isolateTextSegments {#isolateTextSegments-int-int-}
```
public TextSegmentCollection isolateTextSegments(int startIndex, int length)
```

Ermittelt {@code TextSegment}(e), die den angegebenen Teil des {@code TextFragment}-Texts darstellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex |  | Position im Text, ab der neue {@code TextSegment}(s) beginnen. |
| Länge |  | Länge des Textes, der in {@code TextSegment}(s) isoliert wird. |

**Returns:**
{@code TextSegmentCollection} enthält Textsegmente, die ein Text-Teilstück darstellen, das an einer angegebenen Position beginnt und eine bestimmte Länge hat.

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
Legt die Textposition für den Text fest, dargestellt mit {@code TextFragment}-Objekt. Der YIndent der Position-Struktur stellt die Grundlinienkoordinate des Textfragments dar.

### setEndNote {#setEndNote-com.aspose.pdf.Note-}
Legt die Absatz-Endnotiz fest.(nur für PDF-Erstellung)

### setFootNote {#setFootNote-com.aspose.pdf.Note-}
Legt die Absatz-Fußnotiz fest.(nur für PDF-Erstellung)

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Legt die horizontale Ausrichtung des Textfragments fest.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Legt den Hyperlink des Fragments fest

### setMarkedContentProperties {#setMarkedContentProperties-java.lang.String-int-}


### setPosition {#setPosition-com.aspose.pdf.Position-}
<p> Legt die Textposition für den Text fest, dargestellt mit {@code TextFragment}-Objekt. </p>

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Ermittelt das Rechteck des TextFragments

### setSegments {#setSegments-com.aspose.pdf.TextSegmentCollection-}
Stellt die setSegments-Methode dar

### setText {#setText-java.lang.String-}
<p> Legt das {@code string}-Textobjekt fest, das das {@code TextFragment}-Objekt darstellt. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Ermittelt oder legt Textbearbeitungsoptionen fest. Die Optionen definieren ein spezielles Verhalten, wenn das angeforderte Symbol nicht mit der Schriftart geschrieben werden kann.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Legt eine vertikale Ausrichtung des Textfragmentes fest.

### setWrapLinesCount {#setWrapLinesCount-int-}
```
public void setWrapLinesCount(int value)
```

Legt die Anzahl der Zeilenumbrüche für diesen Absatz fest (nur für PDF-Erstellung)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |
