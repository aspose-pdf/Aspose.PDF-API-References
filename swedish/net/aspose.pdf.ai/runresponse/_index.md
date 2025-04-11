---
title: Class RunResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunResponse klass. Representerar en exekveringskörning på en tråd
type: docs
weight: 1020
url: /sv/net/aspose.pdf.ai/runresponse/
---
## RunResponse klass

Representerar en exekveringskörning på en tråd.

```csharp
public class RunResponse : BaseResponse, IStatus
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [RunResponse](runresponse/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | Hämtar eller sätter ID:t för assistenten som användes för exekveringen av denna körning. |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | Hämtar eller sätter Unix-tidsstämpeln (i sekunder) för när körningen avbröts. |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | Hämtar eller sätter Unix-tidsstämpeln (i sekunder) för när körningen slutfördes. |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | Hämtar eller sätter Unix-tidsstämpeln (i sekunder) för när körningen skapades. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Hämtar eller sätter svaret detaljer. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Hämtar eller sätter HTTP-svarsfel. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hämtar eller sätter felinformationen. |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | Hämtar eller sätter Unix-tidsstämpeln (i sekunder) för när körningen kommer att gå ut. |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | Hämtar eller sätter Unix-tidsstämpeln (i sekunder) för när körningen misslyckades. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Hämtar eller sätter HTTP-svarshuvuden. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Hämtar eller sätter HTTP-statuskoden. |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | Hämtar eller sätter identifieraren, som kan refereras i API-slutpunkter. |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | Hämtar eller sätter detaljer om varför körningen är ofullständig. Kommer att vara null om körningen inte är ofullständig. |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | Hämtar eller sätter instruktionerna som assistenten använde för denna körning. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indikerar om svaret var framgångsrikt. |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | Hämtar eller sätter det senaste felet kopplat till denna körning. Kommer att vara null om det inte finns några fel. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | Hämtar eller sätter det maximala antalet fullföljningstokens som specificerats att ha använts under körningens gång. |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | Hämtar eller sätter det maximala antalet prompttokens som specificerats att ha använts under körningens gång. |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | Hämtar eller sätter en uppsättning av 16 nyckel-värde-par som kan kopplas till ett objekt. Detta kan vara användbart för att lagra ytterligare information om objektet i ett strukturerat format. Nycklar kan vara maximalt 64 tecken långa och värden kan vara maximalt 512 tecken långa. |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | Hämtar eller sätter modellen som assistenten använde för denna körning. |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | Hämtar eller sätter objekttypen, som alltid är thread.run. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hämtar felorsaksfrasen. |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | Hämtar eller sätter detaljer om åtgärden som krävs för att fortsätta körningen. Kommer att vara null om ingen åtgärd krävs. |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | Hämtar eller sätter formatet som modellen måste producera. Kompatibel med GPT-4o, GPT-4 Turbo och alla GPT-3.5 Turbo-modeller sedan gpt-3.5-turbo-1106. Att ställa in till { "type": "json_object" } aktiverar JSON-läget, vilket garanterar att meddelandet som modellen genererar är giltig JSON. Viktigt: när du använder JSON-läget måste du också instruera modellen att producera JSON själv via ett system- eller användarmeddelande. Utan detta kan modellen generera en oändlig ström av vita tecken tills generationen når token-gränsen, vilket resulterar i en långvarig och till synes "fast" begäran. Observera också att meddelandets innehåll kan bli delvis avskuret om finish_reason="length", vilket indikerar att generationen överskred max_tokens eller konversationen överskred max kontextlängd. |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | Hämtar eller sätter Unix-tidsstämpeln (i sekunder) för när körningen startades. |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | Hämtar eller sätter statusen för körningen, som kan vara antingen queued, in_progress, requires_action, cancelling, cancelled, failed, completed, incomplete eller expired. |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | Hämtar eller sätter den samplingstemperatur som användes för denna körning. Om den inte är inställd, standardvärde 1. |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | Hämtar eller sätter ID:t för den tråd som exekverades som en del av denna körning. |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | Hämtar eller sätter vilken (om någon) verktyg som anropas av modellen. none betyder att modellen inte kommer att anropa några verktyg och istället genererar ett meddelande. auto är standardvärdet och betyder att modellen kan välja mellan att generera ett meddelande eller anropa ett eller flera verktyg. required betyder att modellen måste anropa ett eller flera verktyg innan den svarar användaren. Att specificera ett särskilt verktyg som {"type": "file_search"} eller {"type": "function", "function": {"name": "my_function"}} tvingar modellen att anropa det verktyget. |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | Hämtar eller sätter listan över verktyg som assistenten använde för denna körning. |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | Hämtar eller sätter nucleus sampling-värdet som användes för denna körning. Om den inte är inställd, standardvärde 1. |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | Hämtar eller sätter avkortningsstrategin som kontrollerar hur en tråd kommer att avkortas före körningen. Använd detta för att kontrollera det initiala kontextfönstret för körningen. |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | Hämtar eller sätter användningsstatistik relaterad till körningen. Detta värde kommer att vara null om körningen inte är i ett terminalt tillstånd (dvs. in_progress, queued, etc.). |

### Se Även

* klass [BaseResponse](../baseresponse/)
* gränssnitt [IStatus](../istatus/)
* namnrymd [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)