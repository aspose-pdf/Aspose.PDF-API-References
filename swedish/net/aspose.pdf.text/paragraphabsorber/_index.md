---
title: Class ParagraphAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.ParagraphAbsorber klass. Representerar ett absorberande objekt av sidstrukturobjekt som sektioner och stycken. Utför sökningar efter sektioner och stycken av text och ger åtkomst till rektanglar och polygoner som beskriver det i textkoordinatsystemet. Utför också sökningar efter textsegment och ger åtkomst till sökresultat via TextFragments-samlingar grupperade efter strukturelement.
type: docs
weight: 10670
url: /sv/net/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber klass

Representerar ett absorberande objekt av sidstrukturobjekt som sektioner och stycken. Utför sökningar efter sektioner och stycken av text och ger åtkomst till rektanglar och polygoner som beskriver det i textkoordinatsystemet. Utför också sökningar efter textsegment och ger åtkomst till sökresultat via !:TextFragments-samlingar grupperade efter strukturelement.

```csharp
public class ParagraphAbsorber
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | Initierar en ny instans av `ParagraphAbsorber` som utför sökningar efter sektioner/stycken i dokumentet eller sidan. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | Initierar en ny instans av `ParagraphAbsorber` som utför sökningar efter sektioner/stycken i dokumentet eller sidan. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | Initierar en ny instans av `ParagraphAbsorber` som utför sökningar efter sektioner/stycken i dokumentet eller sidan med angivna parametrar. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | Initierar en ny instans av `ParagraphAbsorber` som utför sökningar efter sektioner/stycken i dokumentet eller sidan med angivna parametrar. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | Hämtar eller ställer in värdet som anger om startande textlinjer i en nästa sektion kan behandlas som en fortsättning av det sista stycket i en tidigare sektion. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | Hämtar samlingen av [`PageMarkup`](../pagemarkup/) som har absorberats. |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | Hämtar eller ställer in ParagraphAbsorberOptions. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | Hämtar eller ställer in värdet som instruerar hur många gånger sekventiella sökningar efter mer detaljerade strukturelement kommer att utföras. Standard sökdjup är 3. Det betyder tre sökningar efter horisontellt delade sektioner (huvuden, stycken etc.) och tre sökningar efter vertikalt delade (kolumner). |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | Hämtar eller ställer in TextReplaceOptions. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | Utför sökningar efter sektioner och stycken på den angivna [`Document`](../../aspose.pdf/document/). |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | Utför sökningar på den angivna [`Page`](../../aspose.pdf/page/). |

## Kommentarer

När sökningen är slutförd kommer [`PageMarkups`](./pagemarkups/) samlingen att innehålla [`PageMarkup`](../pagemarkup/) objekt som representerar sidstruktur genom samlingar av [`MarkupSection`](../markupsection/) och [`MarkupParagraph`](../markupparagraph/). Objektet [`TextFragment`](../textfragment/) ger åtkomst till den sökta textens förekomst, textens egenskaper och möjliggör redigering av text och ändring av textens tillstånd (teckensnitt, teckensnittsstorlek, färg etc.).

## Exempel

Exemplet visar hur man hittar det första textsegmentet av varje stycke på den första PDF-dokumentets sida och markerar det.

```csharp
// Open document
Document doc = new Document("input.pdf");

// Create ParagraphAbsorber object
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Get markup object of first page
PageMarkup markup = absorber.PageMarkups[0];

// Loop through structure elements of the page text to find first text fragment of each paragraph
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Update text properties
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Save document
doc.Save(GetOutputPath("output.pdf"));
```

### Se Även

* namnrymd [Aspose.Pdf.Text](../../aspose.pdf.text/)
* sammansättning [Aspose.PDF](../../)