---
title: "PageMarkup"
linktitle: "PageMarkup"
second_title: "Aspose.PDF för Java API-referens"
description: "Sidmarkup representerad av samlingar av {@code MarkupSection} och {@code MarkupParagraph}."
type: docs
weight: 3420
url: /sv/java/com.aspose.pdf/pagemarkup/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageMarkup

```
public final class PageMarkup extends Object
```

Sidmarkup representerad av samlingar av {@code MarkupSection} och {@code MarkupParagraph}.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getNumber](#getNumber--) | Hämtar bearbetat sidnummer. |
| [getParagraphs](#getParagraphs--) | Hämtar samling av {@code MarkupParagraph} som hittades på sidan. |
| [getRectangle](#getRectangle--) | Hämtar bearbetad sidrektangel. |
| [getSections](#getSections--) | Hämtar samling av {@code MarkupSection} som hittades på sidan. |
| [getTextFragments](#getTextFragments--) | <p> Hämtar samling av {@code TextFragment} som hittades på sidan. </p><hr> {@code TextFragment}-objektet ger åtkomst till sökförekomstens text, textegenskaper och möjliggör att redigera text och ändra texttillståndet (typsnitt, teckenstorlek, färg etc). |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | Hämtar eller anger värde som indikerar om startande textrader i nästa avsnitt kan behandlas som en fortsättning på det sista stycket i föregående avsnitt. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | Hämtar eller anger värde som indikerar om startande textrader i nästa avsnitt kan behandlas som en fortsättning på det sista stycket i föregående avsnitt. |

### getNumber {#getNumber--}
```
public int getNumber()
```

Hämtar bearbetat sidnummer.

**Returns:**
int‑värde

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

Hämtar samling av {@code MarkupParagraph} som hittades på sidan.

**Returns:**
Lista över MarkupParagraph‑instanser

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Hämtar bearbetad sidrektangel.

**Returns:**
Rectangle‑objekt

### getSections {#getSections--}
```
public List < MarkupSection > getSections()
```

Hämtar samling av {@code MarkupSection} som hittades på sidan.

**Returns:**
Lista över MarkupSection‑instanser

### getTextFragments {#getTextFragments--}
```
public List < TextFragment > getTextFragments()
```

<p> Hämtar samling av {@code TextFragment} som hittades på sidan. </p><hr> {@code TextFragment}-objektet ger åtkomst till sökförekomstens text, textegenskaper och möjliggör att redigera text och ändra texttillståndet (typsnitt, teckenstorlek, färg etc).

**Returns:**
Lista över TextFragment‑instanser

### isMulticolumnParagraphsAllowed {#isMulticolumnParagraphsAllowed--}
```
public final boolean isMulticolumnParagraphsAllowed()
```

Hämtar eller anger värde som indikerar om startande textrader i nästa avsnitt kan behandlas som en fortsättning på det sista stycket i föregående avsnitt.

**Returns:**
booleskt värde

### setMulticolumnParagraphsAllowed {#setMulticolumnParagraphsAllowed-boolean-}
```
public final void setMulticolumnParagraphsAllowed(boolean value)
```

Hämtar eller anger värde som indikerar om startande textrader i nästa avsnitt kan behandlas som en fortsättning på det sista stycket i föregående avsnitt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
