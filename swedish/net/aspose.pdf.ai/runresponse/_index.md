---
title: "Klass RunResponse"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.RunResponse-klass. Representerar ett exekveringskörning på en tråd"
type: docs
weight: 1100
url: /sv/net/aspose.pdf.ai/runresponse/
---
## RunResponse class

Representerar en exekveringskörning på en tråd.

```csharp
public class RunResponse : BaseResponse, IStatus
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [RunResponse](runresponse/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | Hämtar eller anger ID för assistenten som används för exekveringen av detta kör. |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | Hämtar eller anger Unix-tidsstämpeln (i sekunder) för när körningen avbröts. |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | Hämtar eller anger Unix-tidsstämpeln (i sekunder) för när körningen slutfördes. |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | Hämtar eller anger Unix-tidsstämpeln (i sekunder) för när körningen skapades. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Hämtar eller anger svarsdetaljen. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Hämtar eller anger HTTP‑svarsfelet. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hämtar eller anger felinformationen. |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | Hämtar eller anger Unix-tidsstämpeln (i sekunder) för när körningen går ut. |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | Hämtar eller anger Unix-tidsstämpeln (i sekunder) för när körningen misslyckades. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Hämtar eller anger HTTP‑svarsrubriker. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Hämtar eller anger HTTP‑statuskoden. |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | Hämtar eller anger identifieraren, som kan refereras i API‑slutpunkter. |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | Hämtar eller anger detaljerna om varför körningen är ofullständig. Kommer att vara null om körningen inte är ofullständig. |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | Hämtar eller anger instruktionerna som assistenten använde för denna körning. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indikerar om svaret var framgångsrikt. |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | Hämtar eller anger det senaste felet som är associerat med denna körning. Kommer att vara null om det inte finns några fel. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | Hämtar eller anger det maximala antalet kompletteringstoken som specificerats att ha använts under körningens gång. |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | Hämtar eller anger det maximala antalet prompt-token som specificerats att ha använts under körningens gång. |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | Hämtar eller anger en uppsättning av 16 nyckel‑värdepar som kan bifogas ett objekt. Detta kan vara användbart för att lagra ytterligare information om objektet i ett strukturerat format. Nycklar kan vara högst 64 tecken långa och värden kan vara högst 512 tecken långa. |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | Hämtar eller anger modellen som assistenten använde för denna körning. |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | Hämtar eller anger objekttypen, som alltid är thread.run. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hämtar felorsakens fras. |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | Hämtar eller anger detaljerna om den åtgärd som krävs för att fortsätta körningen. Kommer att vara null om ingen åtgärd krävs. |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | Hämtar eller anger det format som modellen måste returnera. Kompatibel med GPT-4o, GPT-4 Turbo och alla GPT-3.5 Turbo-modeller sedan gpt-3.5-turbo-1106. Att sätta till { "type": "json_object" } aktiverar JSON-läge, vilket garanterar att meddelandet som modellen genererar är giltig JSON. Viktigt: när du använder JSON-läge måste du också instruera modellen att själv producera JSON via ett system‑ eller användarmeddelande. Utan detta kan modellen generera en oändlig ström av blanksteg tills genereringen når token‑gränsen, vilket resulterar i en långvarig och till synes "fast" begäran. Observera också att meddelandeinnehållet kan bli delvis avklippt om finish_reason="length", vilket indikerar att genereringen överskred max_tokens eller att konversationen överskred den maximala kontextlängden. |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | Hämtar eller anger Unix‑tidsstämpeln (i sekunder) för när körningen startade. |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | Hämtar eller anger status för körningen, som kan vara queued, in_progress, requires_action, cancelling, cancelled, failed, completed, incomplete eller expired. |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | Hämtar eller anger samplings‑temperaturen som används för denna körning. Om den inte anges, är standardvärdet 1. |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | Hämtar eller anger ID‑t för tråden som kördes som en del av denna körning. |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | Hämtar eller anger vilket (om något) verktyg som modellen anropar. none betyder att modellen inte kommer att anropa några verktyg utan istället genererar ett meddelande. auto är standardvärdet och betyder att modellen kan välja mellan att generera ett meddelande eller anropa ett eller flera verktyg. required betyder att modellen måste anropa ett eller flera verktyg innan den svarar användaren. Att specificera ett särskilt verktyg som {"type": "file_search"} eller {"type": "function", "function": {"name": "my_function"}} tvingar modellen att anropa det verktyget. |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | Hämtar eller anger listan över verktyg som assistenten använde för denna körning. |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | Hämtar eller anger nucleus‑samplingsvärdet som används för denna körning. Om det inte anges, är standardvärdet 1. |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | Hämtar eller anger trunkeringsstrategin som styr hur en tråd trunkeras före körningen. Använd detta för att kontrollera det initiala kontextfönstret för körningen. |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | Hämtar eller anger användningsstatistiken relaterad till körningen. Detta värde blir null om körningen inte är i ett slutligt tillstånd (t.ex. in_progress, queued osv.). |

### Se även

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


