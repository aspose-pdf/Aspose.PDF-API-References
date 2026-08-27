---
title: "Klass CreateChatCompletionChunkResponse"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.CreateChatCompletionChunkResponse-klass. Representerar en strömmad del av ett chattkompletteringssvar som returneras av modellen baserat på den angivna inmatningen."
type: docs
weight: 260
url: /sv/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## CreateChatCompletionChunkResponse class

Representerar en strömad del av ett chattkompletteringssvar som returneras av modellen, baserat på den angivna inmatningen.

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
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | Hämtar eller anger en lista med chattkompletteringsval. Kan innehålla fler än ett element om n är större än 1. Kan också vara tom för den sista delen om du sätter stream_options: {\"include_usage\": true}. |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | Hämtar eller anger Unix-tidsstämpeln (i sekunder) för när chattkompletteringen skapades. Varje del har samma tidsstämpel. |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | Hämtar eller anger en unik identifierare för chattkompletteringen. Varje del har samma ID. |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | Hämtar eller anger modellen för att generera kompletteringen. |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | Hämtar eller anger objekttypen, som alltid är chat.completion.chunk. |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | Hämtar eller anger fingeravtrycket som representerar backend‑konfigurationen som modellen körs med. Kan användas i kombination med seed‑begäransparametern för att förstå när backend‑ändringar har gjorts som kan påverka determinism. |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | Hämtar eller anger ett valfritt fält som endast kommer att finnas när du sätter stream_options: {\"include_usage\": true} i din begäran. När det finns, innehåller det ett null‑värde förutom för den sista delen som innehåller tokenanvändningsstatistiken för hela begäran. |

### Se även

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


