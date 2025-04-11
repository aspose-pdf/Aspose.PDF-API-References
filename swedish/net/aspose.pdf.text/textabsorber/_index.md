---
title: Class TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextAbsorber klass. Representerar ett absorberobjekt av text. Utför textutvinning och ger åtkomst till resultatet via Text-objektet
type: docs
weight: 10800
url: /sv/net/aspose.pdf.text/textabsorber/
---
## TextAbsorber klass

Representerar ett absorberobjekt av text. Utför textutvinning och ger åtkomst till resultatet via [`Text`](./text/) objekt.

```csharp
public class TextAbsorber
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextAbsorber](textabsorber/#constructor)() | Initierar en ny instans av `TextAbsorber`. |
| [TextAbsorber](textabsorber/#constructor_1)(TextExtractionOptions) | Initierar en ny instans av `TextAbsorber` med utvinningsalternativ. |
| [TextAbsorber](textabsorber/#constructor_3)(TextSearchOptions) | Initierar en ny instans av `TextAbsorber` med text sökalternativ. |
| [TextAbsorber](textabsorber/#constructor_2)(TextExtractionOptions, TextSearchOptions) | Initierar en ny instans av `TextAbsorber` med utvinnings- och text sökalternativ. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | Lista över [`TextExtractionError`](../textextractionerror/) objekt. Den innehåller information om fel som hittades under textutvinning. Sökning efter fel kommer endast att utföras om TextSearchOptions.LogTextExtractionErrors = true; och det kan minska prestanda. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | Hämtar eller ställer in textutvinningsalternativ. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | Värdet indikerar om fel hittades under textutvinning. Sökning efter fel kommer endast att utföras om TextSearchOptions.LogTextExtractionErrors = true; och det kan minska prestanda. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | Hämtar den utvunna text som `TextAbsorber` extraherar från PDF-dokumentet eller sidan. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | Hämtar eller ställer in text sökalternativ. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | Extraherar text på det angivna dokumentet |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | Extraherar text på den angivna sidan |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | Extraherar text på den angivna XForm. |

## Kommentarer

`TextAbsorber` objektet används för att extrahera text från ett Pdf-dokument eller dokumentets sida.

## Exempel

Exemplet visar hur man extraherar text på den första sidan av PDF-dokumentet.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### Se Även

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)