---
title: "MarkupParagraph"
linktitle: "MarkupParagraph"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt einen Absatz dar."
type: docs
weight: 2880
url: /de/java/com.aspose.pdf/markupparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupParagraph

```
public final class MarkupParagraph extends Object
```

Stellt einen Absatz dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getContinuationPageNumbers](#getContinuationPageNumbers--) | Liste von Seitenzahlen, auf denen der Absatz fortgesetzt wird. Sie stimmt mit der Seite überein, auf der der Absatz begonnen hat, falls er in der nächsten Spalte auf derselben Seite weiterläuft. |
| [getFragments](#getFragments--) | <p> Sammlung von nicht leeren {@code TextFragment}-Objekten des Absatzes. </p><hr> Das {@code TextFragment}-Objekt bietet Zugriff auf den gefundenen Text, Texteigenschaften und ermöglicht das Bearbeiten des Textes sowie das Ändern des Textzustands (Schriftart, Schriftgröße, Farbe usw.). |
| [getFragmentsInternal](#getFragmentsInternal--) |  |
| [getLines](#getLines--) | <p> Zeilen des Absatzes. Jede Zeile wird durch eine Liste von Textfragmenten dargestellt. </p><hr> Das {@code TextFragment}-Objekt bietet Zugriff auf den Text des Suchvorkommens, Texteigenschaften und ermöglicht das Bearbeiten des Textes sowie das Ändern des Textzustands (Schriftart, Schriftgröße, Farbe usw.). |
| [getLinesInternal](#getLinesInternal--) |  |
| [getPoints](#getPoints--) | Punkte des Polygons, das den Absatz beschreibt. Der Startpunkt ist die linke untere Ecke des Absatzes. Und die nächsten Punkte folgen in gegen den Uhrzeigersinn. |
| [getSecondaryPoints](#getSecondaryPoints--) | Punkte des sekundären Polygons beschreiben die Fortsetzung des Absatzes. Es wird nicht null sein, wenn der Absatz in der nächsten Spalte oder Seite fortgesetzt wird. Der Startpunkt ist die linke untere Ecke des Absatzes. Und die nächsten Punkte folgen in gegen den Uhrzeigersinn. |
| [getText](#getText--) | Liefert das {@code string}-Textobjekt, das das {@code MarkupParagraph}-Objekt darstellt. |
| [setText](#setText-java.lang.String-) | Liest oder setzt den Absatztext. |

### getContinuationPageNumbers {#getContinuationPageNumbers--}
```
public final List < Integer > getContinuationPageNumbers()
```

Liste von Seitenzahlen, auf denen der Absatz fortgesetzt wird. Sie stimmt mit der Seite überein, auf der der Absatz begonnen hat, falls er in der nächsten Spalte auf derselben Seite weiterläuft.

**Returns:**
Liste von Integer

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> Sammlung von nicht leeren {@code TextFragment}-Objekten des Absatzes. </p><hr> Das {@code TextFragment}-Objekt bietet Zugriff auf den gefundenen Text, Texteigenschaften und ermöglicht das Bearbeiten des Textes sowie das Ändern des Textzustands (Schriftart, Schriftgröße, Farbe usw.).

**Returns:**
Liste von TextFragment-Instanzen

### getFragmentsInternal {#getFragmentsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< TextFragment > getFragmentsInternal()
```



### getLines {#getLines--}
```
public List <com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLines()
```

<p> Zeilen des Absatzes. Jede Zeile wird durch eine Liste von Textfragmenten dargestellt. </p><hr> Das {@code TextFragment}-Objekt bietet Zugriff auf den Text des Suchvorkommens, Texteigenschaften und ermöglicht das Bearbeiten des Textes sowie das Ändern des Textzustands (Schriftart, Schriftgröße, Farbe usw.).

**Returns:**
Liste von TextFragment-Instanzen

### getLinesInternal {#getLinesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLinesInternal()
```



### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Punkte des Polygons, das den Absatz beschreibt. Der Startpunkt ist die linke untere Ecke des Absatzes. Und die nächsten Punkte folgen in gegen den Uhrzeigersinn.

**Returns:**
Array von Point-Instanzen

### getSecondaryPoints {#getSecondaryPoints--}
```
public final List < Point []> getSecondaryPoints()
```

Punkte des sekundären Polygons beschreiben die Fortsetzung des Absatzes. Es wird nicht null sein, wenn der Absatz in der nächsten Spalte oder Seite fortgesetzt wird. Der Startpunkt ist die linke untere Ecke des Absatzes. Und die nächsten Punkte folgen in gegen den Uhrzeigersinn.

**Returns:**
Liste von Point[]

### getText {#getText--}
```
public String getText()
```

Liefert das {@code string}-Textobjekt, das das {@code MarkupParagraph}-Objekt darstellt.

**Returns:**
String Wert

### setText {#setText-java.lang.String-}
Liest oder setzt den Absatztext.
