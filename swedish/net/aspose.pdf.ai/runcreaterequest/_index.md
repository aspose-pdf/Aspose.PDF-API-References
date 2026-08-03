---
title: "Klass RunCreateRequest"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.RunCreateRequest klass. Representerar en begäran om att skapa en körning."
type: docs
weight: 1060
url: /sv/net/aspose.pdf.ai/runcreaterequest/
---
## RunCreateRequest class

Representerar en begäran om att skapa en körning.

```csharp
public class RunCreateRequest
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [RunCreateRequest](runcreaterequest/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AdditionalInstructions](../../aspose.pdf.ai/runcreaterequest/additionalinstructions/) { get; set; } | Hämtar eller anger de extra instruktionerna. Lägger till extra instruktioner i slutet av instruktionerna för körningen. Detta är användbart för att modifiera beteendet per körning utan att åsidosätta andra instruktioner. |
| [AdditionalMessages](../../aspose.pdf.ai/runcreaterequest/additionalmessages/) { get; set; } | Hämtar eller anger de extra meddelandena till tråden innan körningen skapas. |
| [AssistantId](../../aspose.pdf.ai/runcreaterequest/assistantid/) { get; set; } | Hämtar eller anger ID‑t för assistenten som ska användas för att utföra denna körning. |
| [Instructions](../../aspose.pdf.ai/runcreaterequest/instructions/) { get; set; } | Hämtar eller anger instruktionerna som åsidosätter assistentens instruktioner. Detta är användbart för att modifiera beteendet per körning. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runcreaterequest/maxcompletiontokens/) { get; set; } | Hämtar eller anger det maximala antalet completions‑token som kan användas under körningens gång. Körningen kommer att göra sitt bästa för att endast använda det angivna antalet completions‑token, över flera varv av körningen. Om körningen överskrider det angivna antalet completions‑token, avslutas körningen med status incomplete. Se incomplete_details för mer information. |
| [MaxPromptTokens](../../aspose.pdf.ai/runcreaterequest/maxprompttokens/) { get; set; } | Hämtar eller anger det maximala antalet prompt‑token som kan användas under körningens gång. Körningen kommer att göra sitt bästa för att endast använda det angivna antalet prompt‑token, över flera varv av körningen. Om körningen överskrider det angivna antalet prompt‑token, avslutas körningen med status incomplete. Se incomplete_details för mer information. |
| [Metadata](../../aspose.pdf.ai/runcreaterequest/metadata/) { get; set; } | Hämtar eller anger en uppsättning av 16 nyckel‑värdepar som kan bifogas ett objekt. Detta kan vara användbart för att lagra ytterligare information om objektet i ett strukturerat format. Nycklar kan vara högst 64 tecken långa och värden kan vara högst 512 tecken långa. |
| [Model](../../aspose.pdf.ai/runcreaterequest/model/) { get; set; } | Hämtar eller anger ID‑t för modellen som ska användas för att köra detta körning. Om ett värde anges här kommer det att åsidosätta modellen som är kopplad till assistenten. Om inget anges används modellen som är kopplad till assistenten. |
| [ResponseFormat](../../aspose.pdf.ai/runcreaterequest/responseformat/) { get; set; } | Hämtar eller anger svarformatet. Anger det format som modellen måste returnera. Kompatibel med GPT‑4o, GPT‑4 Turbo och alla GPT‑3.5 Turbo‑modeller sedan gpt-3.5-turbo-1106. Att sätta till { \"type\": \"json_object\" } aktiverar JSON‑läge, vilket garanterar att meddelandet som modellen genererar är giltig JSON. Viktigt: när du använder JSON‑läge måste du också instruera modellen att producera JSON själv via ett system‑ eller användarmeddelande. Utan detta kan modellen generera ett oändligt flöde av blanksteg tills genereringen når token‑gränsen, vilket resulterar i en långvarig och till synes \"stuck\"‑förfrågan. Observera också att meddelandeinnehållet kan bli delvis avklippt om finish_reason=\"length\", vilket indikerar att genereringen överskred max_tokens eller att konversationen överskred den maximala kontextlängden. |
| [Stream](../../aspose.pdf.ai/runcreaterequest/stream/) { get; set; } | Hämtar eller anger om streaming ska användas. Om true returneras en ström av händelser som inträffar under körningen som server‑sent‑events, och avslutas när körningen går in i ett terminalt tillstånd med ett data: [DONE]-meddelande. |
| [Temperature](../../aspose.pdf.ai/runcreaterequest/temperature/) { get; set; } | Hämtar eller anger vilken samplingstemperatur som ska användas, mellan 0 och 2. Högre värden som 0,8 gör utsignalet mer slumpmässigt, medan lägre värden som 0,2 gör det mer fokuserat och deterministiskt. |
| [ToolChoice](../../aspose.pdf.ai/runcreaterequest/toolchoice/) { get; set; } | Hämtar eller anger vilket (om något) verktyg som modellen anropar. none betyder att modellen inte kommer att anropa några verktyg utan istället genererar ett meddelande. auto är standardvärdet och betyder att modellen kan välja mellan att generera ett meddelande eller anropa ett eller flera verktyg. required betyder att modellen måste anropa ett eller flera verktyg innan den svarar användaren. Att specificera ett särskilt verktyg som {"type": "file_search"} eller {"type": "function", "function": {"name": "my_function"}} tvingar modellen att anropa det verktyget. |
| [Tools](../../aspose.pdf.ai/runcreaterequest/tools/) { get; set; } | Hämtar eller anger verktygen som åsidosätter de verktyg som assistenten kan använda för denna körning. Detta är användbart för att ändra beteendet per körning. |
| [TopP](../../aspose.pdf.ai/runcreaterequest/topp/) { get; set; } | Hämtar eller anger ett alternativ till provtagning med temperatur, kallat nucleus‑sampling, där modellen beaktar tokenresultaten med top_p‑sannolikhetsmassa. Så betyder 0.1 att endast de token som utgör de översta 10 % av sannolikhetsmassan beaktas. Vi rekommenderar generellt att justera detta eller temperatur, men inte båda. |
| [TruncationStrategy](../../aspose.pdf.ai/runcreaterequest/truncationstrategy/) { get; set; } | Hämtar eller anger avkortningsstrategin. Styr hur en tråd kommer att avkortas före körningen. Använd detta för att kontrollera det initiala kontextfönstret för körningen. |

### Se även

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


