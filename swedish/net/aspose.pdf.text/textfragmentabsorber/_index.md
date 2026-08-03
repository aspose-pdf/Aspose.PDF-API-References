---
title: "Klass TextFragmentAbsorber"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.TextFragmentAbsorber-klass. Representerar ett absorberingsobjekt för textfragment. Utför textsökning och ger åtkomst till sökresultat via TextFragments-samling."
type: docs
weight: 11130
url: /sv/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class

Representerar ett absorberingsobjekt för textfragment. Utför textsökning och ger åtkomst till sökresultat via [`TextFragments`](./textfragments/) samling.

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | Initierar en ny instans av `TextFragmentAbsorber` som utför sökning av alla textsegment i Document eller Page. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | Initierar en ny instans av `TextFragmentAbsorber`-klassen för det angivna System.Text.RegularExpressions.Regex-klassobjektet. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | Initierar en ny instans av `TextFragmentAbsorber`-klassen för den angivna textfrasen. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | Initierar en ny instans av `TextFragmentAbsorber` med alternativ för textredigering, som utför sökning av alla textsegment i Document eller Page. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | Initierar en ny instans av `TextFragmentAbsorber`-klassen för den angivna textfrasen och alternativ för textredigering. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | Initierar en ny instans av `TextFragmentAbsorber`-klassen för den angivna textfrasen och alternativ för textsökning. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | Initierar en ny instans av `TextFragmentAbsorber`-klassen för den angivna textfrasen och alternativ för textsökning. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | Initierar en ny instans av `TextFragmentAbsorber`-klassen för den angivna textfrasen och alternativ för textredigering. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | Initierar en ny instans av `TextFragmentAbsorber`-klassen för den angivna textfrasen och alternativ för textsökning. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | Initierar en ny instans av `TextFragmentAbsorber`-klassen för den angivna textfrasen, alternativ för textsökning och alternativ för textredigering. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | Lista över [`TextExtractionError`](../textextractionerror/)-objekt. Den innehåller information om fel som hittades under textutdragning. Sökning efter fel utförs endast om TextSearchOptions.LogTextExtractionErrors = true; och det kan minska prestanda. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | Hämtar eller anger alternativ för textutdragning. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | Värdet indikerar om fel hittades under textutdragning. Sökning efter fel utförs endast om TextSearchOptions.LogTextExtractionErrors = true; och det kan minska prestanda. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | Hämtar eller anger frasen som `TextFragmentAbsorber` söker i PDF Document eller Page. |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | Hämtar en ordbok med sökförekomster som presenteras med System.Text.RegularExpressions.Regex-klass som nyckel och [`TextFragment`](../textfragment/) som värde. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | Hämtar extraherad text som [`TextAbsorber`](../textabsorber/) extraherar i PDF Document eller Page. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | Hämtar eller anger alternativ för textredigering. Alternativen definierar särskilt beteende när begärt tecken inte kan skrivas med teckensnittet. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | Hämtar en samling av sökförekomster som presenteras med [`TextFragment`](../textfragment/)-objekt. |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | Hämtar eller anger alternativ för textersättning. Alternativen definierar beteendet när fragmenttext ersätts med kortare eller längre text. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | Hämtar eller anger sökalternativ. Alternativen möjliggör sökning med reguljära uttryck. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | Tillämpar teckenstorlek för alla textfragment som absorberats. Det fungerar snabbare än att loopa genom fragmenten om alla fragment på sidan/sidorna absorberats. Annars fungerar det liknande som loopning. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | Tillämpar teckensnitt för alla textfragment som absorberats. Det fungerar snabbare än att loopa genom fragmenten om alla fragment på sidan/sidorna absorberats. Annars fungerar det liknande som loopning. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | Tillämpar teckensnitt och storlek för alla textfragment som absorberats. Det fungerar snabbare än att loopa genom fragmenten om alla fragment på sidan/sidorna absorberats. Annars fungerar det liknande som loopning. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | Tar bort all text från Document. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | Tar bort all text från den angivna Page. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | Tar bort text inom den angivna Rectangle från den angivna Page. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | Rensar TextFragments-samlingen för detta `TextFragmentAbsorber`-objekt. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | Utför sökning i det angivna dokumentet. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | Utför sökning på den angivna sidan. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | Utför sökning på det angivna formulärobjektet. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | Extraherar text i den angivna XForm. |

## Anmärkningar

Objektet `TextFragmentAbsorber` används i huvudsak i textsökningsscenario. När sökningen är klar representeras förekomsterna av [`TextFragment`](../textfragment/)-objekt som finns i samlingen [`TextFragments`](./textfragments/). [`TextFragment`](../textfragment/)-objektet ger åtkomst till sökförekomstens text, textegenskaper och möjliggör redigering av text samt ändring av textens tillstånd (teckensnitt, teckenstorlek, färg osv).

## Exempel

Exemplet visar hur man hittar text på den första PDF‑dokumentets sida och ersätter texten samt dess teckensnitt.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Skapa ett TextFragmentAbsorber‑objekt för att hitta alla förekomster av texten \"hello world\"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Ändra text och teckensnitt för den första textförekomsten
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [TextAbsorber](../textabsorber/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


