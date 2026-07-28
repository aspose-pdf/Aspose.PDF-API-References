---
title: "TextParagraphAbsorber"
linktitle: "TextParagraphAbsorber"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar ett absorberingsobjekt för textparagrafer. Utför textsökning och ger åtkomst till sökresultat via {@code TextParagraphAbsorber.TextParagraphs} samling."
type: docs
weight: 5220
url: /sv/java/com.aspose.pdf/textparagraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextParagraphAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextParagraphAbsorber

```
public final class TextParagraphAbsorber extends TextAbsorber
```

Representerar ett absorberingsobjekt för textparagrafer. Utför textsökning och ger åtkomst till sökresultat via {@code TextParagraphAbsorber.TextParagraphs} samling.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextParagraphAbsorber](#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-) | <p> Initierar en ny instans av {@code TextParagraphAbsorber} med rektangelkollektion. </p> |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRectangles](#getRectangles--) | Hämtar rektanglar som {@code TextParagraphAbsorber} använder för att söka efter textparagrafer i PDF-dokumentet eller på sidan. |
| [getTextParagraphs](#getTextParagraphs--) | Hämtar samling av sökförekomster som presenteras med {@code TextParagraph}-objekt. |
| [setRectangles](#setRectangles-com.aspose.pdf.Rectangle:A-) | Ställer in rektanglar som {@code TextParagraphAbsorber} använder för att söka efter textparagrafer i PDF-dokumentet eller på sidan. |
| [setTextParagraphs](#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-) | Ställer in samling av sökförekomster som presenteras med {@code TextParagraph}-objekt. |
| [visit](#visit-com.aspose.pdf.Page-) | Utför sökning på den angivna sidan. |

### TextParagraphAbsorber {#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-}
<p> Initierar en ny instans av {@code TextParagraphAbsorber} med rektangelkollektion. </p>

### getRectangles {#getRectangles--}
```
public Rectangle [] getRectangles()
```

Hämtar rektanglar som {@code TextParagraphAbsorber} använder för att söka efter textparagrafer i PDF-dokumentet eller på sidan.

**Returns:**
rektangelarray

### getTextParagraphs {#getTextParagraphs--}
```
public TextParagraphCollection getTextParagraphs()
```

Hämtar samling av sökförekomster som presenteras med {@code TextParagraph}-objekt.

**Returns:**
TextParagraphCollection värde

### setRectangles {#setRectangles-com.aspose.pdf.Rectangle:A-}
Ställer in rektanglar som {@code TextParagraphAbsorber} använder för att söka efter textparagrafer i PDF-dokumentet eller på sidan.

### setTextParagraphs {#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-}
Ställer in samling av sökförekomster som presenteras med {@code TextParagraph}-objekt.

### visit {#visit-com.aspose.pdf.Page-}
Utför sökning på den angivna sidan.
