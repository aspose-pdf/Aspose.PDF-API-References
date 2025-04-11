---
title: Class LlamaChatCompletionResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.LlamaChatCompletionResponse klass. Representerar ett chattkompletteringssvar som returneras av modellen baserat på den angivna inmatningen
type: docs
weight: 690
url: /sv/net/aspose.pdf.ai/llamachatcompletionresponse/
---
## LlamaChatCompletionResponse klass

Representerar ett chattkompletteringssvar som returneras av modellen, baserat på den angivna inmatningen.

```csharp
public class LlamaChatCompletionResponse : BaseResponse
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [LlamaChatCompletionResponse](llamachatcompletionresponse/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Choices](../../aspose.pdf.ai/llamachatcompletionresponse/choices/) { get; set; } | Hämtar eller ställer in en lista över chattkompletteringsalternativ. Kan vara mer än en om n är större än 1. |
| [Created](../../aspose.pdf.ai/llamachatcompletionresponse/created/) { get; set; } | Hämtar eller ställer in Unix-tidsstämpeln (i sekunder) för när chattkompletteringen skapades. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Hämtar eller ställer in svardetaljer. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Hämtar eller ställer in HTTP-svarsfel. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hämtar eller ställer in felinformation. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Hämtar eller ställer in HTTP-svarshuvuden. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Hämtar eller ställer in HTTP-statuskod. |
| [Id](../../aspose.pdf.ai/llamachatcompletionresponse/id/) { get; set; } | Hämtar eller ställer in ett unikt identifierare för chattkompletteringen. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indikerar om svaret var framgångsrikt. |
| [Model](../../aspose.pdf.ai/llamachatcompletionresponse/model/) { get; set; } | Hämtar eller ställer in modellen som används för chattkompletteringen. |
| [Object](../../aspose.pdf.ai/llamachatcompletionresponse/object/) { get; set; } | Hämtar eller ställer in objekttypen, som alltid är chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hämtar felorsaksfrasen. |
| [SystemFingerprint](../../aspose.pdf.ai/llamachatcompletionresponse/systemfingerprint/) { get; set; } | Hämtar eller ställer in fingeravtrycket som representerar backendkonfigurationen som modellen kör med. |
| [Usage](../../aspose.pdf.ai/llamachatcompletionresponse/usage/) { get; set; } | Hämtar eller ställer in användningsstatistik för kompletteringsförfrågan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/llamachatcompletionresponse/tostring/)() | Returnerar en strängrepresentation av det första alternativet. |

### Se Även

* klass [BaseResponse](../baseresponse/)
* namnrymd [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../)