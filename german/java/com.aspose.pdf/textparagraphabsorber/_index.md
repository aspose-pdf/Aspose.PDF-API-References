---
title: "TextParagraphAbsorber"
linktitle: "TextParagraphAbsorber"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein Absorber-Objekt für Textabsätze dar. Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die {@code TextParagraphAbsorber.TextParagraphs}-Sammlung."
type: docs
weight: 5220
url: /de/java/com.aspose.pdf/textparagraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextParagraphAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextParagraphAbsorber

```
public final class TextParagraphAbsorber extends TextAbsorber
```

Stellt ein Absorber-Objekt für Textabsätze dar. Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die {@code TextParagraphAbsorber.TextParagraphs}-Sammlung.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextParagraphAbsorber](#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-) | <p> Initialisiert eine neue Instanz von {@code TextParagraphAbsorber} mit einer Rechtecksammlung. </p> |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRectangles](#getRectangles--) | Ermittelt die Rechtecke, die der {@code TextParagraphAbsorber} zum Suchen von Textabsätzen im PDF-Dokument oder auf der Seite verwendet. |
| [getTextParagraphs](#getTextParagraphs--) | Ermittelt die Sammlung von Suchvorkommen, die mit {@code TextParagraph}-Objekten dargestellt werden. |
| [setRectangles](#setRectangles-com.aspose.pdf.Rectangle:A-) | Setzt die Rechtecke, die der {@code TextParagraphAbsorber} zum Suchen von Textabsätzen im PDF-Dokument oder auf der Seite verwendet. |
| [setTextParagraphs](#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-) | Setzt die Sammlung von Suchvorkommen, die mit {@code TextParagraph}-Objekten dargestellt werden. |
| [visit](#visit-com.aspose.pdf.Page-) | Führt die Suche auf der angegebenen Seite aus. |

### TextParagraphAbsorber {#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-}
<p> Initialisiert eine neue Instanz von {@code TextParagraphAbsorber} mit einer Rechtecksammlung. </p>

### getRectangles {#getRectangles--}
```
public Rectangle [] getRectangles()
```

Ermittelt die Rechtecke, die der {@code TextParagraphAbsorber} zum Suchen von Textabsätzen im PDF-Dokument oder auf der Seite verwendet.

**Returns:**
Rechteck-Array

### getTextParagraphs {#getTextParagraphs--}
```
public TextParagraphCollection getTextParagraphs()
```

Ermittelt die Sammlung von Suchvorkommen, die mit {@code TextParagraph}-Objekten dargestellt werden.

**Returns:**
TextParagraphCollection-Wert

### setRectangles {#setRectangles-com.aspose.pdf.Rectangle:A-}
Setzt die Rechtecke, die der {@code TextParagraphAbsorber} zum Suchen von Textabsätzen im PDF-Dokument oder auf der Seite verwendet.

### setTextParagraphs {#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-}
Setzt die Sammlung von Suchvorkommen, die mit {@code TextParagraph}-Objekten dargestellt werden.

### visit {#visit-com.aspose.pdf.Page-}
Führt die Suche auf der angegebenen Seite aus.
