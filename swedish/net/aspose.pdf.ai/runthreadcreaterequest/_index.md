---
title: Class RunThreadCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunThreadCreateRequest klass. Representerar en begäran om att skapa en tråd och köra den i en begäran
type: docs
weight: 1070
url: /sv/net/aspose.pdf.ai/runthreadcreaterequest/
---
## RunThreadCreateRequest klass

Representerar en begäran om att skapa en tråd och köra den i en begäran.

```csharp
public class RunThreadCreateRequest
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [RunThreadCreateRequest](runthreadcreaterequest/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runthreadcreaterequest/assistantid/) { get; set; } | Hämtar eller sätter ID för assistenten som ska användas för att utföra denna körning. |
| [Instructions](../../aspose.pdf.ai/runthreadcreaterequest/instructions/) { get; set; } | Hämtar eller sätter instruktionerna som åsidosätter instruktionerna för assistenten. Detta är användbart för att modifiera beteendet per körning. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxcompletiontokens/) { get; set; } | Hämtar eller sätter det maximala antalet fullföljande tokens som kan användas under körningen. Körningen kommer att göra sitt bästa för att endast använda det antal fullföljande tokens som anges, över flera omgångar av körningen. Om körningen överskrider det angivna antalet fullföljande tokens, kommer körningen att avslutas med status ofullständig. Se incomplete_details för mer information. |
| [MaxPromptTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxprompttokens/) { get; set; } | Hämtar eller sätter det maximala antalet prompt tokens som kan användas under körningen. Körningen kommer att göra sitt bästa för att endast använda det antal prompt tokens som anges, över flera omgångar av körningen. Om körningen överskrider det angivna antalet prompt tokens, kommer körningen att avslutas med status ofullständig. Se incomplete_details för mer information. |
| [Metadata](../../aspose.pdf.ai/runthreadcreaterequest/metadata/) { get; set; } | Hämtar eller sätter en uppsättning av 16 nyckel-värde-par som kan kopplas till ett objekt. Detta kan vara användbart för att lagra ytterligare information om objektet i ett strukturerat format. Nycklar kan vara maximalt 64 tecken långa och värden kan vara maximalt 512 tecken långa. |
| [Model](../../aspose.pdf.ai/runthreadcreaterequest/model/) { get; set; } | Hämtar eller sätter ID för modellen som ska användas för att utföra denna körning. Om ett värde anges här, kommer det att åsidosätta modellen som är kopplad till assistenten. Om inte, kommer modellen som är kopplad till assistenten att användas. |
| [ResponseFormat](../../aspose.pdf.ai/runthreadcreaterequest/responseformat/) { get; set; } | Hämtar eller sätter formatet som modellen måste producera. Kompatibel med GPT-4o, GPT-4 Turbo och alla GPT-3.5 Turbo-modeller sedan gpt-3.5-turbo-1106. Att ställa in { "type": "json_object" } aktiverar JSON-läge, vilket garanterar att meddelandet som modellen genererar är giltig JSON. Viktigt: när du använder JSON-läge måste du också instruera modellen att producera JSON själv via ett system- eller användarmeddelande. Utan detta kan modellen generera en oändlig ström av vita tecken tills generationen når token-gränsen, vilket resulterar i en långvarig och till synes "fast" begäran. Observera också att meddelandets innehåll kan bli delvis avskuret om finish_reason="length", vilket indikerar att generationen överskred max_tokens eller att konversationen överskred den maximala kontextlängden. |
| [Stream](../../aspose.pdf.ai/runthreadcreaterequest/stream/) { get; set; } | Hämtar eller sätter om streaming ska användas. Om sant, returnerar en ström av händelser som inträffar under körningen som server-sända händelser, som avslutas när körningen går in i ett terminalt tillstånd med ett data: [DONE] meddelande. |
| [Temperature](../../aspose.pdf.ai/runthreadcreaterequest/temperature/) { get; set; } | Hämtar eller sätter vilken samplingstemperatur som ska användas, mellan 0 och 2. Högre värden som 0.8 gör utdata mer slumpmässiga, medan lägre värden som 0.2 gör dem mer fokuserade och deterministiska. |
| [Thread](../../aspose.pdf.ai/runthreadcreaterequest/thread/) { get; set; } | Hämtar eller sätter en begäran om att skapa en tråd. |
| [ToolChoice](../../aspose.pdf.ai/runthreadcreaterequest/toolchoice/) { get; set; } | Hämtar eller sätter vilken (om någon) verktyg som anropas av modellen. none betyder att modellen inte kommer att anropa några verktyg och istället genererar ett meddelande. auto är standardvärdet och betyder att modellen kan välja mellan att generera ett meddelande eller anropa ett eller flera verktyg. required betyder att modellen måste anropa ett eller flera verktyg innan den svarar användaren. Att specificera ett särskilt verktyg som {"type": "file_search"} eller {"type": "function", "function": {"name": "my_function"}} tvingar modellen att anropa det verktyget. |
| [ToolResources](../../aspose.pdf.ai/runthreadcreaterequest/toolresources/) { get; set; } | Hämtar eller sätter en uppsättning resurser som används av assistentens verktyg. |
| [Tools](../../aspose.pdf.ai/runthreadcreaterequest/tools/) { get; set; } | Hämtar eller sätter de verktyg som åsidosätter de verktyg som assistenten kan använda för denna körning. Detta är användbart för att modifiera beteendet per körning. |
| [TopP](../../aspose.pdf.ai/runthreadcreaterequest/topp/) { get; set; } | Hämtar eller sätter ett värde som alternativ till sampling med temperatur, kallad nucleus sampling, där modellen överväger resultaten av tokens med top_p sannolikhetsmassa. Så 0.1 betyder att endast de tokens som utgör den översta 10% sannolikhetsmassan beaktas. Vi rekommenderar generellt att ändra detta eller temperaturen men inte båda. |
| [TruncationStrategy](../../aspose.pdf.ai/runthreadcreaterequest/truncationstrategy/) { get; set; } | Hämtar eller sätter avkortningsstrategin som kontrollerar hur en tråd kommer att avkortas före körningen. Använd detta för att kontrollera det initiala kontextfönstret för körningen. |

### Se Även

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)