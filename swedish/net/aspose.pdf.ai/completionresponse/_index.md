---
title: Class CompletionResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CompletionResponse klass. Representerar ett chattkompletteringssvar som returneras av modellen baserat på den angivna inmatningen
type: docs
weight: 240
url: /sv/net/aspose.pdf.ai/completionresponse/
---
## CompletionResponse klass

Representerar ett chattkompletteringssvar som returneras av modellen, baserat på den angivna inmatningen.

```csharp
public class CompletionResponse : BaseResponse
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [CompletionResponse](completionresponse/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Choices](../../aspose.pdf.ai/completionresponse/choices/) { get; set; } | Hämtar eller ställer in en lista med chattkompletteringsval. Kan vara mer än en om n är större än 1. |
| [Created](../../aspose.pdf.ai/completionresponse/created/) { get; set; } | Hämtar eller ställer in Unix-tidsstämpeln (i sekunder) för när chattkompletteringen skapades. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Hämtar eller ställer in svardetaljerna. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Hämtar eller ställer in HTTP-svarsfel. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hämtar eller ställer in felinformation. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Hämtar eller ställer in HTTP-svarshuvuden. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Hämtar eller ställer in HTTP-statuskod. |
| [Id](../../aspose.pdf.ai/completionresponse/id/) { get; set; } | Hämtar eller ställer in ett unikt identifierare för chattkompletteringen. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indikerar om svaret var framgångsrikt. |
| [Model](../../aspose.pdf.ai/completionresponse/model/) { get; set; } | Hämtar eller ställer in modellen som används för chattkompletteringen. |
| [Object](../../aspose.pdf.ai/completionresponse/object/) { get; set; } | Hämtar eller ställer in objekttypen, som alltid är chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hämtar felorsaksfrasen. |
| [SystemFingerprint](../../aspose.pdf.ai/completionresponse/systemfingerprint/) { get; set; } | Hämtar eller ställer in fingeravtrycket som representerar backendkonfigurationen som modellen kör med. Kan användas tillsammans med seed-förfrågningsparametern för att förstå när backendändringar har gjorts som kan påverka determinism. |
| [Usage](../../aspose.pdf.ai/completionresponse/usage/) { get; set; } | Hämtar eller ställer in användningsstatistik för kompletteringsförfrågan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/completionresponse/tostring/)() | Returnerar innehållet i det första valet som en sträng. |

### Se Även

* klass [BaseResponse](../baseresponse/)
* namnrymd [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../)