---
title: "MarkupSection"
linktitle: "MarkupSection"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en markup-sektion – det rektangulära området på en sida som innehåller text och kan visuellt separeras från andra textblock."
type: docs
weight: 2890
url: /sv/java/com.aspose.pdf/markupsection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupSection

```
public final class MarkupSection extends Object
```

Representerar en markup-sektion – det rektangulära området på en sida som innehåller text och kan visuellt separeras från andra textblock.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFragments](#getFragments--) | <p> Samling av icke tomma {@code TextFragment}-objekt som finns i avsnittet. </p><hr> {@code TextFragment}-objektet ger åtkomst till sökförekomstens text, textegenskaper, och tillåter att redigera text och ändra texttillståndet (teckensnitt, teckenstorlek, färg etc). |
| [getParagraphs](#getParagraphs--) | Samling av {@code MarkupParagraph}-objekt som finns i avsnittet. |
| [getRectangle](#getRectangle--) | Avsnittets rektangel |

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> Samling av icke tomma {@code TextFragment}-objekt som finns i avsnittet. </p><hr> {@code TextFragment}-objektet ger åtkomst till sökförekomstens text, textegenskaper, och tillåter att redigera text och ändra texttillståndet (teckensnitt, teckenstorlek, färg etc).

**Returns:**
lista med TextFragment-instansier

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

Samling av {@code MarkupParagraph}-objekt som finns i avsnittet.

**Returns:**
lista med MarkupParagraph-instansier

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Avsnittets rektangel

**Returns:**
Rektangelinstans
