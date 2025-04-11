---
title: Class TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragmentAbsorber klass. Representerar ett absorberobjekt för textfragment. Utför textsökning och ger åtkomst till sökresultat via TextFragments-samlingen
type: docs
weight: 10950
url: /sv/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber klass

Representerar ett absorberobjekt för textfragment. Utför textsökning och ger åtkomst till sökresultat via [`TextFragments`](./textfragments/) samlingen.

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | Initierar en ny instans av `TextFragmentAbsorber` som utför sökning av alla textsegment i dokumentet eller sidan. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | Initierar en ny instans av `TextFragmentAbsorber`-klassen för det angivna System.Text.RegularExpressions.Regex-klassobjektet. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | Initierar en ny instans av `TextFragmentAbsorber`-klassen för den angivna textfrasen. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | Initierar en ny instans av `TextFragmentAbsorber` med textredigeringsalternativ, som utför sökning av alla textsegment i dokumentet eller sidan. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | Initierar en ny instans av `TextFragmentAbsorber`-klassen för den angivna textfrasen och textredigeringsalternativen. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | Initierar en ny instans av `TextFragmentAbsorber`-klassen för den angivna textfrasen och textsökalternativen. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | Initierar en ny instans av `TextFragmentAbsorber`-klassen för den angivna textfrasen och textsökalternativen. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | Initierar en ny instans av `TextFragmentAbsorber`-klassen för den angivna textfrasen och textredigeringsalternativen. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | Initierar en ny instans av `TextFragmentAbsorber`-klassen för den angivna textfrasen och textsökalternativen. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | Initierar en ny instans av `TextFragmentAbsorber`-klassen för den angivna textfrasen, textsökalternativen och textredigeringsalternativen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | Lista över [`TextExtractionError`](../textextractionerror/) objekt. Den innehåller information om fel som hittades under textutvinning. Sökning efter fel kommer endast att utföras om TextSearchOptions.LogTextExtractionErrors = true; och det kan minska prestanda. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | Hämtar eller ställer in textutvinningsalternativ. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | Värdet indikerar om fel hittades under textutvinning. Sökning efter fel kommer endast att utföras om TextSearchOptions.LogTextExtractionErrors = true; och det kan minska prestanda. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | Hämtar eller ställer in frasen som `TextFragmentAbsorber` söker på PDF-dokumentet eller sidan. |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | Hämtar en ordbok över sökförekomster som presenteras med System.Text.RegularExpressions.Regex-klass som nyckel och [`TextFragment`](../textfragment/) som värde. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | Hämtar den extraherade text som [`TextAbsorber`](../textabsorber/) extraherar på PDF-dokumentet eller sidan. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | Hämtar eller ställer in textredigeringsalternativ. Alternativen definierar speciellt beteende när den begärda symbolen inte kan skrivas med typsnitt. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | Hämtar samlingen av sökförekomster som presenteras med [`TextFragment`](../textfragment/) objekt. |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | Hämtar eller ställer in textutbytesalternativ. Alternativen definierar beteende när fragmenttext ersätts med kortare/längre. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | Hämtar eller ställer in sökalternativ. Alternativen möjliggör sökning med hjälp av reguljära uttryck. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | Tillämpa teckenstorlek för alla textfragment som har absorberats. Det fungerar snabbare än att loopa genom fragmenten om alla fragment på sidan/erna har absorberats. Annars fungerar det liknande med loopning. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | Tillämpa typsnitt för alla textfragment som har absorberats. Det fungerar snabbare än att loopa genom fragmenten om alla fragment på sidan/erna har absorberats. Annars fungerar det liknande med loopning. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | Tillämpa typsnitt och storlek för alla textfragment som har absorberats. Det fungerar snabbare än att loopa genom fragmenten om alla fragment på sidan/erna har absorberats. Annars fungerar det liknande med loopning. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | Tar bort all text från dokumentet. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | Tar bort all text från den angivna sidan. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | Tar bort text inuti den angivna rektangeln från den angivna sidan. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | Rensar TextFragments-samlingen av detta `TextFragmentAbsorber`-objekt. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | Utför sökning på det angivna dokumentet. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | Utför sökning på den angivna sidan. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | Utför sökning på det angivna formulärobjektet. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | Extraherar text på den angivna XForm. |

## Kommentarer

`TextFragmentAbsorber`-objektet används i grund och botten i textsökningsscenarier. När sökningen är slutförd representeras förekomsterna med [`TextFragment`](../textfragment/) objekt som [`TextFragments`](./textfragments/) samlingen innehåller. [`TextFragment`](../textfragment/) objektet ger åtkomst till den sökta förekomstens text, textens egenskaper och möjliggör redigering av text och ändring av textens tillstånd (typsnitt, teckenstorlek, färg etc).

## Exempel

Exemplet visar hur man hittar text på den första sidan av PDF-dokumentet och ersätter texten och dess typsnitt.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Se Även

* klass [TextAbsorber](../textabsorber/)
* namnrymd [Aspose.Pdf.Text](../../aspose.pdf.text/)
* sammansättning [Aspose.PDF](../../)