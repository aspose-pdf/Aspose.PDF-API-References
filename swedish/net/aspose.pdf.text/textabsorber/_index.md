---
title: "Klass TextAbsorber"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.TextAbsorber-klass. Representerar ett absorberande objekt för text. Utför textutdragning och ger åtkomst till resultatet via Text-objekt"
type: docs
weight: 10980
url: /sv/net/aspose.pdf.text/textabsorber/
---
## TextAbsorber class

Representerar ett absorberande objekt för text. Utför textutdragning och ger åtkomst till resultatet via [`Text`](./text/) objekt.

```csharp
public class TextAbsorber
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextAbsorber](textabsorber/#constructor)() | Initierar en ny instans av `TextAbsorber`. |
| [TextAbsorber](textabsorber/#constructor_1)(TextExtractionOptions) | Initierar en ny instans av `TextAbsorber` med extraheringsalternativ. |
| [TextAbsorber](textabsorber/#constructor_3)(TextSearchOptions) | Initierar en ny instans av `TextAbsorber` med text­sökalternativ. |
| [TextAbsorber](textabsorber/#constructor_2)(TextExtractionOptions, TextSearchOptions) | Initierar en ny instans av `TextAbsorber` med extraherings- och text­sökalternativ. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | Lista över [`TextExtractionError`](../textextractionerror/)-objekt. Den innehåller information om fel som hittades under textutdragning. Sökning efter fel utförs endast om TextSearchOptions.LogTextExtractionErrors = true; och det kan minska prestanda. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | Hämtar eller anger alternativ för textutdragning. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | Värdet indikerar om fel hittades under textutdragning. Sökning efter fel utförs endast om TextSearchOptions.LogTextExtractionErrors = true; och det kan minska prestanda. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | Hämtar extraherad text som `TextAbsorber` extraherar i PDF-dokumentet eller på sidan. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | Hämtar eller anger alternativ för textsökning. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | Extraherar text i det angivna dokumentet |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | Extraherar text på den angivna sidan |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | Extraherar text i den angivna XForm. |

## Anmärkningar

Objektet `TextAbsorber` används för att extrahera text från ett PDF-dokument eller dokumentets sida.

## Exempel

Exemplet visar hur man extraherar text på den första PDF-dokumentets sida.

```csharp
// öppna dokument
Document doc = new Document(inFile);

// skapa TextAbsorber-objekt för att extrahera text
TextAbsorber absorber = new TextAbsorber();

// acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// hämta den extraherade texten
string extractedText = absorber.Text;

```

### Se även

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


