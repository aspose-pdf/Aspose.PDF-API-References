---
title: "Klass CompletionResponse"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.CompletionResponse-klass. Representerar ett chattkompletteringssvar som returneras av modellen baserat på den angivna inmatningen."
type: docs
weight: 250
url: /sv/net/aspose.pdf.ai/completionresponse/
---
## CompletionResponse class

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
| [Choices](../../aspose.pdf.ai/completionresponse/choices/) { get; set; } | Hämtar eller anger en lista med chattslutförandeval. Kan vara fler än ett om n är större än 1. |
| [Created](../../aspose.pdf.ai/completionresponse/created/) { get; set; } | Hämtar eller anger Unix‑tidsstämpeln (i sekunder) för när chattslutförandet skapades. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Hämtar eller anger svarsdetaljen. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Hämtar eller anger HTTP‑svarsfelet. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hämtar eller anger felinformationen. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Hämtar eller anger HTTP‑svarsrubriker. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Hämtar eller anger HTTP‑statuskoden. |
| [Id](../../aspose.pdf.ai/completionresponse/id/) { get; set; } | Hämtar eller anger en unik identifierare för chattkompletteringen. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indikerar om svaret var framgångsrikt. |
| [Model](../../aspose.pdf.ai/completionresponse/model/) { get; set; } | Hämtar eller anger modellen som används för chattkompletteringen. |
| [Object](../../aspose.pdf.ai/completionresponse/object/) { get; set; } | Hämtar eller anger objekttypen, som alltid är chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hämtar felorsakens fras. |
| [SystemFingerprint](../../aspose.pdf.ai/completionresponse/systemfingerprint/) { get; set; } | Hämtar eller anger fingeravtrycket som representerar backend‑konfigurationen som modellen körs med. Kan användas i kombination med seed‑begäransparametern för att förstå när backend‑ändringar har gjorts som kan påverka determinism. |
| [Usage](../../aspose.pdf.ai/completionresponse/usage/) { get; set; } | Hämtar eller anger användningsstatistik för kompletteringsbegäran. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/completionresponse/tostring/)() | Returnerar innehållet i det första valet som en sträng. |

### Se även

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


