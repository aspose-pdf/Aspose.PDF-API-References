---
title: "PageMarkup"
linktitle: "PageMarkup"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt einen Seitenzahlstempel dar und wird zum Nummerieren von Seiten verwendet."
type: docs
weight: 3420
url: /de/java/com.aspose.pdf/pagemarkup/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageMarkup

```
public final class PageMarkup extends Object
```

Stellt einen Seitenzahlstempel dar und wird zum Nummerieren von Seiten verwendet.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getNumber](#getNumber--) | Liefert die verarbeitete Seitennummer. |
| [getParagraphs](#getParagraphs--) | Liefert die Sammlung von {@code MarkupParagraph}, die auf der Seite gefunden wurde. |
| [getRectangle](#getRectangle--) | Liefert das verarbeitete Seitenrechteck. |
| [getSections](#getSections--) | Liefert die Sammlung von {@code MarkupSection}, die auf der Seite gefunden wurde. |
| [getTextFragments](#getTextFragments--) | <p> Liefert die Sammlung von {@code TextFragment}, die auf der Seite gefunden wurde. </p><hr> Das {@code TextFragment}-Objekt bietet Zugriff auf den gefundenen Text, Texteigenschaften und ermöglicht das Bearbeiten des Textes sowie das Ändern des Textzustands (Schriftart, Schriftgröße, Farbe usw.). |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | Liefert oder setzt den Wert, der angibt, ob die Anfangszeilen des nächsten Abschnitts als Fortsetzung des letzten Absatzes des vorherigen Abschnitts behandelt werden dürfen. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | Liefert oder setzt den Wert, der angibt, ob die Anfangszeilen des nächsten Abschnitts als Fortsetzung des letzten Absatzes des vorherigen Abschnitts behandelt werden dürfen. |

### getNumber {#getNumber--}
```
public int getNumber()
```

Liefert die verarbeitete Seitennummer.

**Returns:**
int-Wert

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

Liefert die Sammlung von {@code MarkupParagraph}, die auf der Seite gefunden wurde.

**Returns:**
Liste von MarkupParagraph-Instanzen

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Liefert das verarbeitete Seitenrechteck.

**Returns:**
Rectangle-Objekt

### getSections {#getSections--}
```
public List < MarkupSection > getSections()
```

Liefert die Sammlung von {@code MarkupSection}, die auf der Seite gefunden wurde.

**Returns:**
Liste von MarkupSection-Instanzen

### getTextFragments {#getTextFragments--}
```
public List < TextFragment > getTextFragments()
```

<p> Liefert die Sammlung von {@code TextFragment}, die auf der Seite gefunden wurde. </p><hr> Das {@code TextFragment}-Objekt bietet Zugriff auf den gefundenen Text, Texteigenschaften und ermöglicht das Bearbeiten des Textes sowie das Ändern des Textzustands (Schriftart, Schriftgröße, Farbe usw.).

**Returns:**
Liste von TextFragment-Instanzen

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
