---
title: "Klass ParagraphAbsorber"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.ParagraphAbsorber-klass. Representerar ett absorberande objekt för sidstrukturobjekt såsom sektioner och stycken. Utför sökning efter sektioner och stycken i text och ger åtkomst till rektanglar och polygoner som beskriver det i textkoordinatrymden. Utför också sökning efter textsegment och ger åtkomst till sökresultat via TextFragments-samlingar grupperade efter strukturelement."
type: docs
weight: 10850
url: /sv/net/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber class

Representerar ett absorberingsobjekt för sidstrukturobjekt såsom sektioner och stycken. Utför sökning efter sektioner och stycken i text och ger åtkomst till rektanglar och polygoner som beskriver det i textkoordinatrymden. Utför också sökning efter textsegment och ger åtkomst till sökresultat via !:TextFragments-samlingar grupperade efter strukturelement.

```csharp
public class ParagraphAbsorber
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | Initierar en ny instans av `ParagraphAbsorber` som utför sökning efter sektioner/stycken i dokumentet eller sidan. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | Initierar en ny instans av `ParagraphAbsorber` som utför sökning efter sektioner/stycken i dokumentet eller sidan. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | Initierar en ny instans av `ParagraphAbsorber` som utför sökning efter sektioner/stycken i dokumentet eller sidan med de angivna parametrarna. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | Initierar en ny instans av `ParagraphAbsorber` som utför sökning efter sektioner/stycken i dokumentet eller sidan med de angivna parametrarna. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | Hämtar eller anger värde som indikerar om startlinjerna i nästa avsnitt kan behandlas som fortsättning på det sista stycket i föregående avsnitt. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | Hämtar samling av [`PageMarkup`](../pagemarkup/) som absorberades. |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | Hämtar eller anger ParagraphAbsorberOptions. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | Hämtar eller anger värdet som bestämmer hur många gånger sekventiella sökningar efter finare strukturelement ska utföras. Standard sökdjup är 3. Det innebär tre sökningar för horisontellt delade sektioner (rubriker, stycken osv) och tre sökningar för vertikalt delade (kolumner). |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | Hämtar eller anger TextReplaceOptions. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | Utför sökning efter sektioner och stycken i det angivna [`Document`](../../aspose.pdf/document/). |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | Utför sökning på den angivna [`Page`](../../aspose.pdf/page/). |

## Anmärkningar

När sökningen är klar kommer samlingen [`PageMarkups`](./pagemarkups/) att innehålla [`PageMarkup`](../pagemarkup/)‑objekt som representerar sidstrukturen genom samlingar av [`MarkupSection`](../markupsection/) och [`MarkupParagraph`](../markupparagraph/). [`TextFragment`](../textfragment/)-objektet ger åtkomst till den hittade texten, textegenskaper och möjliggör redigering av text samt ändring av textens tillstånd (teckensnitt, teckenstorlek, färg osv).

## Exempel

Exemplet visar hur man hittar det första textsegmentet i varje stycke på den första PDF-dokumentets sida och markerar det.

```csharp
// Öppna dokument
Document doc = new Document("input.pdf");

// Skapa ParagraphAbsorber-objekt
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Acceptera absorberaren för första sidan
absorber.Visit(doc.Pages[1]);

// Hämta markup‑objekt för första sidan
PageMarkup markup = absorber.PageMarkups[0];

// Loopa igenom strukturelementen i sidans text för att hitta det första textfragmentet i varje stycke
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

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


