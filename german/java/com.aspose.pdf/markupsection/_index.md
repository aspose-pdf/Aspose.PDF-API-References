---
title: "MarkupSection"
linktitle: "MarkupSection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt einen Markup-Abschnitt dar – den rechteckigen Bereich einer Seite, der Text enthält und visuell von anderen Textblöcken getrennt werden kann."
type: docs
weight: 2890
url: /de/java/com.aspose.pdf/markupsection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupSection

```
public final class MarkupSection extends Object
```

Stellt einen Markup-Abschnitt dar – den rechteckigen Bereich einer Seite, der Text enthält und visuell von anderen Textblöcken getrennt werden kann.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFragments](#getFragments--) | <p> Sammlung von nicht leeren {@code TextFragment}-Objekten, die sich innerhalb des Abschnitts befinden. </p><hr> Das {@code TextFragment}-Objekt bietet Zugriff auf den gefundenen Text, die Texteigenschaften und ermöglicht das Bearbeiten des Textes sowie das Ändern des Textzustands (Schriftart, Schriftgröße, Farbe usw.). |
| [getParagraphs](#getParagraphs--) | Sammlung von {@code MarkupParagraph}-Objekten, die sich innerhalb des Abschnitts befinden. |
| [getRectangle](#getRectangle--) | Abschnittsrechteck |

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> Sammlung von nicht leeren {@code TextFragment}-Objekten, die sich innerhalb des Abschnitts befinden. </p><hr> Das {@code TextFragment}-Objekt bietet Zugriff auf den gefundenen Text, die Texteigenschaften und ermöglicht das Bearbeiten des Textes sowie das Ändern des Textzustands (Schriftart, Schriftgröße, Farbe usw.).

**Returns:**
Liste von TextFragment-Instanzen

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

Sammlung von {@code MarkupParagraph}-Objekten, die sich innerhalb des Abschnitts befinden.

**Returns:**
Liste von MarkupParagraph-Instanzen

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Abschnittsrechteck

**Returns:**
Rechteck-Instanz
