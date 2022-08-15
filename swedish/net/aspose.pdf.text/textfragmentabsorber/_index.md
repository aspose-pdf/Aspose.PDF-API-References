---
title: TextFragmentAbsorber
second_title: Aspose.PDF för .NET API Referens
description: Representerar ett absorberande objekt av textfragment. Utför textsökning och ger tillgång till sökresultat viaTextFragments./textfragmentabsorber/textfragments samling.
type: docs
weight: 7110
url: /sv/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class

Representerar ett absorberande objekt av textfragment. Utför textsökning och ger tillgång till sökresultat via[`TextFragments`](./textfragments) samling.

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber#constructor)() | Initierar en ny instans av[`TextFragmentAbsorber`](../textfragmentabsorber) som utför sökning av alla textsegment i dokumentet eller sidan. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_6)(Regex) | Initierar en ny instans av[`TextFragmentAbsorber`](../textfragmentabsorber) klass för det angivna System.Text.RegularExpressions.Regex klassobjektet. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_2)(string) | Initierar en ny instans av[`TextFragmentAbsorber`](../textfragmentabsorber) klass för den angivna textfrasen. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_1)(TextEditOptions) | Initierar en ny instans av[`TextFragmentAbsorber`](../textfragmentabsorber)med textredigeringsalternativ, som utför sökning av alla textsegment i dokumentet eller sidan. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_7)(Regex, TextEditOptions) | Initierar en ny instans av[`TextFragmentAbsorber`](../textfragmentabsorber) klass för den angivna textfrasen och textredigeringsalternativ. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_8)(Regex, TextSearchOptions) | Initierar en ny instans av[`TextFragmentAbsorber`](../textfragmentabsorber) klass för den angivna textfrasen och textsökningsalternativ. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_3)(string, TextEditOptions) | Initierar en ny instans av[`TextFragmentAbsorber`](../textfragmentabsorber) klass för den angivna textfrasen och textredigeringsalternativ. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_4)(string, TextSearchOptions) | Initierar en ny instans av[`TextFragmentAbsorber`](../textfragmentabsorber)klass för den angivna textfrasen och textsökningsalternativ. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_5)(string, TextSearchOptions, TextEditOptions) | Initierar en ny instans av[`TextFragmentAbsorber`](../textfragmentabsorber) klass för den angivna textfrasen, textsökningsalternativ och textredigeringsalternativ. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors) { get; } | Lista över[`TextExtractionError`](../textextractionerror) objekt. Den innehåller information om fel som hittades under textextraktion. Sökning efter fel utförs endast om TextSearchOptions.LogTextExtractionErrors = true; Och det kan minska prestandan. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions) { get; set; } | Hämtar eller ställer in alternativ för textextraktion. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors) { get; } | Värde anger om fel hittades under textextrahering. Sökning efter fel utförs endast om TextSearchOptions.LogTextExtractionErrors = true; Och det kan minska prestandan. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase) { get; set; } | Hämtar eller ställer in en fras som[`TextFragmentAbsorber`](../textfragmentabsorber) sökningar på PDF-dokumentet eller sidan. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text) { get; } | Får extraherad text som[`TextAbsorber`](../textabsorber) utdrag på PDF-dokumentet eller sidan. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions) { get; set; } | Hämtar eller ställer in textredigeringsalternativ. Alternativen definierar speciellt beteende när den begärda symbolen inte kan skrivas med font. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments) { get; set; } | Hämtar samling av sökförekomster som presenteras med[`TextFragment`](../textfragment) objekt. |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions) { get; set; } | Hämtar eller ställer in alternativ för textersättning. Alternativen definierar beteende när fragmenterad text ersätts till mer kort/lång. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions) { get; set; } | Hämtar eller ställer in sökalternativ. Alternativen möjliggör sökning med reguljära uttryck. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments_2)(float) | Tillämpar teckenstorlek för alla textfragment som har absorberats. Det fungerar snabbare än att gå igenom fragmenten om alla fragment på sidan/sidorna absorberades. Annars fungerar det liknande med looping. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments)(Font) | Tillämpar teckensnitt för alla textfragment som har absorberats. Det fungerar snabbare än att gå igenom fragmenten om alla fragment på sidan/sidorna absorberades. Annars fungerar det liknande med looping. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments_1)(Font, float) | Tillämpar teckensnitt och storlek för alla textfragment som absorberades. Det fungerar snabbare än att gå igenom fragmenten om alla fragment på sidan/sidorna absorberades. Annars fungerar det liknande med looping. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext)(Document) | Tar bort all text från dokumentet. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext_1)(Page) | Tar bort all text från den angivna sidan. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext_2)(Page, Rectangle) | Tar bort text inuti den angivna rektangeln från den angivna sidan. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset)() | Rensar TextFragments-samlingen av detta[`TextFragmentAbsorber`](../textfragmentabsorber) objekt. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit)(Document) | Utför sökning på det angivna dokumentet. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit_1)(Page) | Utför sökning på den angivna sidan. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit_2)(XForm) | Utför sökning på det angivna formulärobjektet. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit)(XForm) | Extraherar text på den angivna XForm. |

### Anmärkningar

Den[`TextFragmentAbsorber`](../textfragmentabsorber) objekt används i princip i textsökningsscenario. När sökningen är klar representeras förekomsterna med[`TextFragment`](../textfragment) objekt som[`TextFragments`](./textfragments) samlingen innehåller. Den[`TextFragment`](../textfragment) objekt ger tillgång till sökhändelsens text, textegenskaper och gör det möjligt att redigera text och ändra texttillståndet (typsnitt, teckenstorlek, färg etc).

### Exempel

Exemplet visar hur man hittar text på den första PDF-dokumentsidan och ersätter texten och dess teckensnitt.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Hitta teckensnitt som kommer att användas för att ändra teckensnitt för dokumenttext
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Skapa TextFragmentAbsorber-objekt för att hitta alla "hej världen" textförekomster
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorbenten för första sidan
doc.Pages[1].Accept(absorber);

// Ändra text och teckensnitt för den första textförekomsten
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [TextAbsorber](../textabsorber)
* namnutrymme [Aspose.Pdf.Text](../../aspose.pdf.text)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
