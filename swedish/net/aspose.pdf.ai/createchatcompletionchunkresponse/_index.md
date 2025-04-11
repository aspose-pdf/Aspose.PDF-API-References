---
title: Class CreateChatCompletionChunkResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CreateChatCompletionChunkResponse klass. Representerar en strömmad del av ett chattkompletteringssvar som returneras av modellen baserat på den angivna inmatningen
type: docs
weight: 250
url: /sv/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## CreateChatCompletionChunkResponse klass

Representerar en strömmad del av ett chattkompletteringssvar som returneras av modellen, baserat på den angivna inmatningen.

```csharp
public class CreateChatCompletionChunkResponse
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [CreateChatCompletionChunkResponse](createchatcompletionchunkresponse/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | Hämtar eller ställer in en lista över chattkompletteringsval. Kan innehålla mer än ett element om n är större än 1. Kan också vara tom för den sista delen om du ställer in stream_options: {"include_usage": true}. |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | Hämtar eller ställer in Unix-tidsstämpeln (i sekunder) för när chattkompletteringen skapades. Varje del har samma tidsstämpel. |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | Hämtar eller ställer in ett unikt identifierare för chattkompletteringen. Varje del har samma ID. |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | Hämtar eller ställer in modellen för att generera kompletteringen. |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | Hämtar eller ställer in objekttypen, som alltid är chat.completion.chunk. |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | Hämtar eller ställer in fingeravtrycket som representerar backendkonfigurationen som modellen körs med. Kan användas tillsammans med seed-förfrågningsparametern för att förstå när backendändringar har gjorts som kan påverka determinism. |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | Hämtar eller ställer in ett valfritt fält som endast kommer att vara närvarande när du ställer in stream_options: {"include_usage": true} i din förfrågan. När det är närvarande innehåller det ett nullvärde förutom för den sista delen som innehåller tokenanvändningsstatistik för hela förfrågan. |

### Se Även

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)