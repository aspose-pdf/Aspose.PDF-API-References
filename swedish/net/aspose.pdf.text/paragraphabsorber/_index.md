---
title: ParagraphAbsorber
second_title: Aspose.PDF för .NET API Referens
description: Representerar ett absorberande objekt för sidstrukturobjekt som sektioner och stycken. Söker efter avsnitt och stycken av text och ger åtkomst till rektanglar och polydoner som beskriver det i textkoordinatutrymme. Utför även textsegmentsökning och ger tillgång till sökresultat viaTextFragments samlingar grupperade efter strukturelement.
type: docs
weight: 6850
url: /sv/net/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber class

Representerar ett absorberande objekt för sidstrukturobjekt som sektioner och stycken. Söker efter avsnitt och stycken av text och ger åtkomst till rektanglar och polydoner som beskriver det i textkoordinatutrymme. Utför även textsegmentsökning och ger tillgång till sökresultat via!:TextFragments samlingar grupperade efter strukturelement.

```csharp
public class ParagraphAbsorber
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber#constructor)() | Initierar en ny instans av[`ParagraphAbsorber`](../paragraphabsorber) som söker efter avsnitt/stycken i dokumentet eller sidan. |
| [ParagraphAbsorber](paragraphabsorber#constructor_1)(int) | Initierar en ny instans av[`ParagraphAbsorber`](../paragraphabsorber) som söker efter avsnitt/stycken i dokumentet eller sidan. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed) { get; set; } | Hämtar eller ställer in värde som indikerar om starttextrader i ett nästa avsnitt kan behandlas som en fortsättning på det sista stycket i ett tidigare avsnitt. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups) { get; } | Får samling av[`PageMarkup`](../pagemarkup) som absorberades. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth) { get; set; } | Hämtar eller ställer in värde som anger hur många gånger sekventiella sökningar efter mer fina strukturelement kommer att utföras. Standardsökdjupet är 3. Det betyder tre sökningar efter horisontellt delade avsnitt (rubriker, stycken etc) och tre sökningar efter vertikalt delade ettor (kolumner). |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit#visit)(Document) | Söker efter avsnitt och stycken på det angivna[`Document`](../../aspose.pdf/document) . |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit#visit_1)(Page) | Utför sökning på den angivna[`Page`](../../aspose.pdf/page) . |

### Anmärkningar

När sökningen är klar visas[`PageMarkups`](./pagemarkups) samling kommer innehåller[`PageMarkup`](../pagemarkup) objekt som representerar sidstruktur genom samlingar av[`MarkupSection`](../markupsection) och[`MarkupParagraph`](../markupparagraph) . Den[`TextFragment`](../textfragment) objekt ger tillgång till sökhändelsens text, textegenskaper och gör det möjligt att redigera text och ändra texttillståndet (typsnitt, teckenstorlek, färg etc).

### Exempel

Exemplet visar hur man hittar det första textsegmentet i varje stycke på den första PDF-dokumentsidan och markerar den.

```csharp
// Öppna dokument
Document doc = new Document("input.pdf");

// Skapa ParagraphAbsorber-objekt
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Acceptera absorbenten för första sidan
absorber.Visit(doc.Pages[1]);

// Hämta uppmärkningsobjekt för första sidan
PageMarkup markup = absorber.PageMarkups[0];

// Gå igenom strukturelementen i sidtexten för att hitta det första textfragmentet i varje stycke
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Uppdatera textegenskaper
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Spara dokument
doc.Save(GetOutputPath("output.pdf"));
```

### Se även

* namnutrymme [Aspose.Pdf.Text](../../aspose.pdf.text)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
