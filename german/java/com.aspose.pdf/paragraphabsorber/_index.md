---
title: "ParagraphAbsorber"
linktitle: "ParagraphAbsorber"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt ein Absorberobjekt für Seitenstrukturobjekte wie Abschnitte und Absätze dar. Führt die Suche nach Abschnitten und Absätzen im Text durch und bietet Zugriff darauf."
type: docs
weight: 3470
url: /de/java/com.aspose.pdf/paragraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ParagraphAbsorber

```
public class ParagraphAbsorber extends Object
```

<p> Stellt ein Absorber-Objekt der Seitenstruktur-Objekte wie Abschnitte und Absätze dar. Führt die Suche nach Abschnitten und Absätzen im Text durch und bietet Zugriff auf Rechtecke und Polygone, die es im Textkoordinatenraum beschreiben. Führt außerdem die Suche nach Textsegmenten durch und bietet Zugriff auf die Suchergebnisse über {@code TextFragments}-Sammlungen, gruppiert nach Strukturelementen. </p> Das Beispiel zeigt, wie man das erste Textsegment jedes Absatzes auf der ersten PDF-Dokumentseite findet und hervorhebt. <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> Wenn die Suche abgeschlossen ist, enthält die {@code ParagraphAbsorber.PageMarkups}-Sammlung {@code PageMarkup}-Objekte, die die Seitenstruktur durch Sammlungen von {@code MarkupSection} und {@code MarkupParagraph} darstellen. Das {@code TextFragment}-Objekt bietet Zugriff auf den gefundenen Text, Texteigenschaften und ermöglicht das Bearbeiten des Textes sowie das Ändern des Textzustands (Schrift, Schriftgröße, Farbe usw.).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ParagraphAbsorber](#ParagraphAbsorber--) | Initialisiert eine neue Instanz des {@code ParagraphAbsorber}, die die Suche nach Abschnitten/Absätzen des Dokuments oder der Seite durchführt. |
| [ParagraphAbsorber](#ParagraphAbsorber-int-) | <p> Initialisiert eine neue Instanz des {@code ParagraphAbsorber}, die die Suche nach Abschnitten/Absätzen des Dokuments oder der Seite durchführt. </p> |
| [ParagraphAbsorber](#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-) | Initialisiert eine neue Instanz des {@code ParagraphAbsorber}, die die Suche nach Abschnitten/Absätzen des Dokuments oder der Seite durchführt. |
| [ParagraphAbsorber](#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-) | Initialisiert eine neue Instanz des {@code ParagraphAbsorber}, die die Suche nach Abschnitten/Absätzen des Dokuments oder der Seite durchführt. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPageMarkups](#getPageMarkups--) | Ruft die Sammlung von {@code PageMarkup} ab, die absorbiert wurden. |
| [getParagraphAbsorberOptions](#getParagraphAbsorberOptions--) | Ruft die ParagraphAbsorberOptions ab. |
| [getSectionsSearchDepth](#getSectionsSearchDepth--) | <p> Gibt den Wert zurück oder setzt ihn, der festlegt, wie oft sequentielle Suchen nach feineren Strukturelementen durchgeführt werden. Die standardmäßige Suchtiefe beträgt 3. Das bedeutet drei Durchläufe für horizontal geteilte Abschnitte (Überschriften, Absätze usw.) und drei Durchläufe für vertikal geteilte (Spalten). </p><hr> Eine Erhöhung dieses Wertes kann zu einer leichten Leistungsverschlechterung führen, ohne sichtbare Änderungen im Suchergebnis. Eine Verringerung dieses Wertes kann zu einer falschen Bestimmung von Absätzen in Abschnitten führen. Wir empfehlen nicht, den Wert unter den Standard zu setzen, wenn Sie nicht ausschließlich „grobe“ Elemente der Seitenstruktur erhalten möchten. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Ruft die TextReplaceOptions ab oder setzt sie. |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | Liefert oder setzt den Wert, der angibt, ob die Anfangszeilen des nächsten Abschnitts als Fortsetzung des letzten Absatzes des vorherigen Abschnitts behandelt werden dürfen. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | Liefert oder setzt den Wert, der angibt, ob die Anfangszeilen des nächsten Abschnitts als Fortsetzung des letzten Absatzes des vorherigen Abschnitts behandelt werden dürfen. |
| [setParagraphAbsorberOptions](#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-) | Setzt die ParagraphAbsorberOptions. |
| [setSectionsSearchDepth](#setSectionsSearchDepth-int-) | <p> Gibt den Wert zurück oder setzt ihn, der festlegt, wie oft sequentielle Suchen nach feineren Strukturelementen durchgeführt werden. Die standardmäßige Suchtiefe beträgt 3. Das bedeutet drei Durchläufe für horizontal geteilte Abschnitte (Überschriften, Absätze usw.) und drei Durchläufe für vertikal geteilte (Spalten). </p><hr> Eine Erhöhung dieses Wertes kann zu einer leichten Leistungsverschlechterung führen, ohne sichtbare Änderungen im Suchergebnis. Eine Verringerung dieses Wertes kann zu einer falschen Bestimmung von Absätzen in Abschnitten führen. Wir empfehlen nicht, den Wert unter den Standard zu setzen, wenn Sie nicht ausschließlich „grobe“ Elemente der Seitenstruktur erhalten möchten. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Ruft die TextReplaceOptions ab oder setzt sie. |
| [visit](#visit-com.aspose.pdf.Document-) | Führt die Suche nach Abschnitten und Absätzen im angegebenen {@link Document} durch. |
| [visit](#visit-com.aspose.pdf.Page-) | Führt die Suche auf der angegebenen {@code Page} durch. |

### ParagraphAbsorber {#ParagraphAbsorber--}
```
public ParagraphAbsorber()
```

Initialisiert eine neue Instanz des {@code ParagraphAbsorber}, die die Suche nach Abschnitten/Absätzen des Dokuments oder der Seite durchführt.

### ParagraphAbsorber {#ParagraphAbsorber-int-}
```
public ParagraphAbsorber(int sectionsSearchDepth)
```

<p> Initialisiert eine neue Instanz des {@code ParagraphAbsorber}, die die Suche nach Abschnitten/Absätzen des Dokuments oder der Seite durchführt. </p>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sectionsSearchDepth |  | Anzahl der sequentiellen Suchvorgänge für feinere Strukturelemente, die durchgeführt werden. <hr> Siehe {@code ParagraphAbsorber.SectionsSearchDepth} Eigenschaft für weitere Hinweise zum Parameter. <hr> |

### ParagraphAbsorber {#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-}
Initialisiert eine neue Instanz des {@code ParagraphAbsorber}, die die Suche nach Abschnitten/Absätzen des Dokuments oder der Seite durchführt.

### ParagraphAbsorber {#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-}
Initialisiert eine neue Instanz des {@code ParagraphAbsorber}, die die Suche nach Abschnitten/Absätzen des Dokuments oder der Seite durchführt.

### getPageMarkups {#getPageMarkups--}
```
public List < PageMarkup > getPageMarkups()
```

Ruft die Sammlung von {@code PageMarkup} ab, die absorbiert wurden.

**Returns:**
Liste von PageMarkup-Instanzen

### getParagraphAbsorberOptions {#getParagraphAbsorberOptions--}
```
public final ParagraphAbsorberOptions getParagraphAbsorberOptions()
```

Ruft die ParagraphAbsorberOptions ab.

**Returns:**
ParagraphAbsorberOptions-Instanz

### getSectionsSearchDepth {#getSectionsSearchDepth--}
```
public int getSectionsSearchDepth()
```

<p> Gibt den Wert zurück oder setzt ihn, der festlegt, wie oft sequentielle Suchen nach feineren Strukturelementen durchgeführt werden. Die standardmäßige Suchtiefe beträgt 3. Das bedeutet drei Durchläufe für horizontal geteilte Abschnitte (Überschriften, Absätze usw.) und drei Durchläufe für vertikal geteilte (Spalten). </p><hr> Eine Erhöhung dieses Wertes kann zu einer leichten Leistungsverschlechterung führen, ohne sichtbare Änderungen im Suchergebnis. Eine Verringerung dieses Wertes kann zu einer falschen Bestimmung von Absätzen in Abschnitten führen. Wir empfehlen nicht, den Wert unter den Standard zu setzen, wenn Sie nicht ausschließlich „grobe“ Elemente der Seitenstruktur erhalten möchten.

**Returns:**
int-Wert

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public final TextReplaceOptions getTextReplaceOptions()
```

Ruft die TextReplaceOptions ab oder setzt sie.

**Returns:**
TextReplaceOptions-Instanz

### isMulticolumnParagraphsAllowed {#isMulticolumnParagraphsAllowed--}
```
public final boolean isMulticolumnParagraphsAllowed()
```

Liefert oder setzt den Wert, der angibt, ob die Anfangszeilen des nächsten Abschnitts als Fortsetzung des letzten Absatzes des vorherigen Abschnitts behandelt werden dürfen.

**Returns:**
boolescher Wert

### setMulticolumnParagraphsAllowed {#setMulticolumnParagraphsAllowed-boolean-}
```
public final void setMulticolumnParagraphsAllowed(boolean value)
```

Liefert oder setzt den Wert, der angibt, ob die Anfangszeilen des nächsten Abschnitts als Fortsetzung des letzten Absatzes des vorherigen Abschnitts behandelt werden dürfen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setParagraphAbsorberOptions {#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-}
Setzt die ParagraphAbsorberOptions.

### setSectionsSearchDepth {#setSectionsSearchDepth-int-}
```
public void setSectionsSearchDepth(int value)
```

<p> Gibt den Wert zurück oder setzt ihn, der festlegt, wie oft sequentielle Suchen nach feineren Strukturelementen durchgeführt werden. Die standardmäßige Suchtiefe beträgt 3. Das bedeutet drei Durchläufe für horizontal geteilte Abschnitte (Überschriften, Absätze usw.) und drei Durchläufe für vertikal geteilte (Spalten). </p><hr> Eine Erhöhung dieses Wertes kann zu einer leichten Leistungsverschlechterung führen, ohne sichtbare Änderungen im Suchergebnis. Eine Verringerung dieses Wertes kann zu einer falschen Bestimmung von Absätzen in Abschnitten führen. Wir empfehlen nicht, den Wert unter den Standard zu setzen, wenn Sie nicht ausschließlich „grobe“ Elemente der Seitenstruktur erhalten möchten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Ruft die TextReplaceOptions ab oder setzt sie.

### visit {#visit-com.aspose.pdf.Document-}
Führt die Suche nach Abschnitten und Absätzen im angegebenen {@link Document} durch.

### visit {#visit-com.aspose.pdf.Page-}
Führt die Suche auf der angegebenen {@code Page} durch.
