---
title: "ParagraphAbsorber"
linktitle: "ParagraphAbsorber"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Representerar ett absorberingsobjekt för sidstrukturobjekt såsom sektioner och stycken. Utför sökning efter sektioner och stycken i text och tillhandahåller åtkomst till."
type: docs
weight: 3470
url: /sv/java/com.aspose.pdf/paragraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ParagraphAbsorber

```
public class ParagraphAbsorber extends Object
```

<p> Representerar ett absorberande objekt för sidstrukturobjekt såsom sektioner och stycken. Utför sökning efter sektioner och stycken i text och tillhandahåller åtkomst till rektanglar och polygoner som beskriver dem i textkoordinatrymden. Utför också sökning av textsegment och ger åtkomst till sökresultat via {@code TextFragments}‑samlingar grupperade efter strukturelement. </p> Exemplet demonstrerar hur man hittar det första textsegmentet i varje stycke på den första PDF‑dokumentets sida och markerar det. <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> När sökningen är klar kommer {@code ParagraphAbsorber.PageMarkups}-samlingen att innehålla {@code PageMarkup}-objekt som representerar sidstruktur genom samlingar av {@code MarkupSection} och {@code MarkupParagraph}. {@code TextFragment}-objektet ger åtkomst till den hittade texten, textegenskaper och möjliggör redigering av text samt ändring av texttillståndet (teckensnitt, teckenstorlek, färg osv).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ParagraphAbsorber](#ParagraphAbsorber--) | Initierar en ny instans av {@code ParagraphAbsorber} som utför sökning efter sektioner/stycken i dokumentet eller på sidan. |
| [ParagraphAbsorber](#ParagraphAbsorber-int-) | <p> Initierar en ny instans av {@code ParagraphAbsorber} som utför sökning efter sektioner/stycken i dokumentet eller på sidan. </p> |
| [ParagraphAbsorber](#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-) | Initierar en ny instans av {@code ParagraphAbsorber} som utför sökning efter sektioner/stycken i dokumentet eller på sidan. |
| [ParagraphAbsorber](#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-) | Initierar en ny instans av {@code ParagraphAbsorber} som utför sökning efter sektioner/stycken i dokumentet eller på sidan. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPageMarkups](#getPageMarkups--) | Hämtar samling av {@code PageMarkup} som absorberades. |
| [getParagraphAbsorberOptions](#getParagraphAbsorberOptions--) | Hämtar ParagraphAbsorberOptions. |
| [getSectionsSearchDepth](#getSectionsSearchDepth--) | <p> Hämtar eller anger värde som instruerar hur många gånger sekventiella sökningar efter finare strukturelement ska utföras. Standard sökdjup är 3. Det innebär tre sökningar för horisontellt delade sektioner (rubriker, stycken etc) och tre sökningar för vertikalt delade (kolumner). </p><hr> Ökning av detta värde kan leda till en liten prestandaförsämring utan synliga förändringar i sökresultatet. Minskning av detta värde kan leda till felaktig bestämning av stycken i sektioner. Vi rekommenderar inte att sätta värdet lägre än standard om du inte önskar endast 'grova' element av sidstrukturen. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Hämtar eller anger TextReplaceOptions. |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | Hämtar eller anger värde som indikerar om startande textrader i nästa avsnitt kan behandlas som en fortsättning på det sista stycket i föregående avsnitt. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | Hämtar eller anger värde som indikerar om startande textrader i nästa avsnitt kan behandlas som en fortsättning på det sista stycket i föregående avsnitt. |
| [setParagraphAbsorberOptions](#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-) | Anger ParagraphAbsorberOptions. |
| [setSectionsSearchDepth](#setSectionsSearchDepth-int-) | <p> Hämtar eller anger värde som instruerar hur många gånger sekventiella sökningar efter finare strukturelement ska utföras. Standard sökdjup är 3. Det innebär tre sökningar för horisontellt delade sektioner (rubriker, stycken etc) och tre sökningar för vertikalt delade (kolumner). </p><hr> Ökning av detta värde kan leda till en liten prestandaförsämring utan synliga förändringar i sökresultatet. Minskning av detta värde kan leda till felaktig bestämning av stycken i sektioner. Vi rekommenderar inte att sätta värdet lägre än standard om du inte önskar endast 'grova' element av sidstrukturen. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Hämtar eller anger TextReplaceOptions. |
| [visit](#visit-com.aspose.pdf.Document-) | Utför sökning efter sektioner och stycken i det angivna {@link Document}. |
| [visit](#visit-com.aspose.pdf.Page-) | Utför sökning på den angivna {@code Page}. |

### ParagraphAbsorber {#ParagraphAbsorber--}
```
public ParagraphAbsorber()
```

Initierar en ny instans av {@code ParagraphAbsorber} som utför sökning efter sektioner/stycken i dokumentet eller på sidan.

### ParagraphAbsorber {#ParagraphAbsorber-int-}
```
public ParagraphAbsorber(int sectionsSearchDepth)
```

<p> Initierar en ny instans av {@code ParagraphAbsorber} som utför sökning efter sektioner/stycken i dokumentet eller på sidan. </p>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sectionsSearchDepth |  | Antal sekventiella sökningar efter finare strukturelement som kommer att utföras. <hr> Se {@code ParagraphAbsorber.SectionsSearchDepth}-egenskapen för fler ledtrådar om parametern. <hr> |

### ParagraphAbsorber {#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-}
Initierar en ny instans av {@code ParagraphAbsorber} som utför sökning efter sektioner/stycken i dokumentet eller på sidan.

### ParagraphAbsorber {#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-}
Initierar en ny instans av {@code ParagraphAbsorber} som utför sökning efter sektioner/stycken i dokumentet eller på sidan.

### getPageMarkups {#getPageMarkups--}
```
public List < PageMarkup > getPageMarkups()
```

Hämtar samling av {@code PageMarkup} som absorberades.

**Returns:**
Lista över PageMarkup-instansers

### getParagraphAbsorberOptions {#getParagraphAbsorberOptions--}
```
public final ParagraphAbsorberOptions getParagraphAbsorberOptions()
```

Hämtar ParagraphAbsorberOptions.

**Returns:**
ParagraphAbsorberOptions-instans

### getSectionsSearchDepth {#getSectionsSearchDepth--}
```
public int getSectionsSearchDepth()
```

<p> Hämtar eller anger värde som instruerar hur många gånger sekventiella sökningar efter finare strukturelement ska utföras. Standard sökdjup är 3. Det innebär tre sökningar för horisontellt delade sektioner (rubriker, stycken etc) och tre sökningar för vertikalt delade (kolumner). </p><hr> Ökning av detta värde kan leda till en liten prestandaförsämring utan synliga förändringar i sökresultatet. Minskning av detta värde kan leda till felaktig bestämning av stycken i sektioner. Vi rekommenderar inte att sätta värdet lägre än standard om du inte önskar endast 'grova' element av sidstrukturen.

**Returns:**
int‑värde

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public final TextReplaceOptions getTextReplaceOptions()
```

Hämtar eller anger TextReplaceOptions.

**Returns:**
TextReplaceOptions‑instans

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

### setParagraphAbsorberOptions {#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-}
Anger ParagraphAbsorberOptions.

### setSectionsSearchDepth {#setSectionsSearchDepth-int-}
```
public void setSectionsSearchDepth(int value)
```

<p> Hämtar eller anger värde som instruerar hur många gånger sekventiella sökningar efter finare strukturelement ska utföras. Standard sökdjup är 3. Det innebär tre sökningar för horisontellt delade sektioner (rubriker, stycken etc) och tre sökningar för vertikalt delade (kolumner). </p><hr> Ökning av detta värde kan leda till en liten prestandaförsämring utan synliga förändringar i sökresultatet. Minskning av detta värde kan leda till felaktig bestämning av stycken i sektioner. Vi rekommenderar inte att sätta värdet lägre än standard om du inte önskar endast 'grova' element av sidstrukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Hämtar eller anger TextReplaceOptions.

### visit {#visit-com.aspose.pdf.Document-}
Utför sökning efter sektioner och stycken i det angivna {@link Document}.

### visit {#visit-com.aspose.pdf.Page-}
Utför sökning på den angivna {@code Page}.
