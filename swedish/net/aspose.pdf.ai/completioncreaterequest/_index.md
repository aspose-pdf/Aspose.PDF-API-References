---
title: "Klass CompletionCreateRequest"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.CompletionCreateRequest-klass. Representerar en begäran för Create Chat Completion-endpunkten"
type: docs
weight: 230
url: /sv/net/aspose.pdf.ai/completioncreaterequest/
---
## CompletionCreateRequest class

Representerar en begäran för slutpunkten Create Chat Completion.

```csharp
public class CompletionCreateRequest
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [CompletionCreateRequest](completioncreaterequest/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | Hämtar eller anger ett tal mellan -2.0 och 2.0. Positiva värden straffar nya token baserat på deras befintliga frekvens i texten hittills, vilket minskar modellens sannolikhet att upprepa samma rad ordagrant. |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | Hämtar eller anger sannolikheten för att specificerade token visas i slutförandet. Accepterar ett JSON-objekt som mappar token (specificerade av deras token-ID i tokeniseraren) till ett associerat biasvärde från -100 till 100. |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | Hämtar eller anger om loggsannolikheter för utdata-token ska returneras eller inte. Om true returneras loggsannolikheterna för varje utdata-token som returneras i meddelandets innehåll. |
| [MaxCompletionTokens](../../aspose.pdf.ai/completioncreaterequest/maxcompletiontokens/) { get; set; } | Hämtar eller anger det maximala antalet token som ska genereras i slutförandet. |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | Hämtar eller anger en lista med meddelanden som utgör konversationen hittills. |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | Hämtar eller anger ID för modellen som ska användas. |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | Hämtar eller anger hur många chattslutförandeval som ska genereras för varje inmatningsmeddelande. Observera att du debiteras baserat på antalet genererade token över alla val. Håll n som 1 för att minimera kostnaderna. |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | Hämtar eller anger ett tal mellan -2,0 och 2,0. Positiva värden straffar nya token baserat på om de redan förekommer i texten, vilket ökar modellens sannolikhet att prata om nya ämnen. |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | Hämtar eller anger ett objekt som specificerar det format som modellen måste producera. Kompatibel med GPT-4 Turbo och alla GPT-3.5 Turbo-modeller nyare än gpt-3.5-turbo-1106. Att sätta till { \"type\": \"json_object\" } aktiverar JSON-läge, vilket garanterar att meddelandet som modellen genererar är giltig JSON. |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | Hämtar eller anger Seed‑värdet. Denna funktion är i Beta. Om den anges kommer vårt system att göra sitt bästa för att provta deterministiskt, så att upprepade förfrågningar med samma seed och parametrar bör returnera samma resultat. Determinism garanteras inte, och du bör referera till svarparametern system_fingerprint för att övervaka förändringar i backend. |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | Hämtar eller anger upp till 4 sekvenser där API‑et kommer att sluta generera ytterligare token. |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | Hämtar eller anger om streaming ska användas. Om satt kommer partiella meddelandedelta att skickas, som i ChatGPT. Token kommer att skickas som enbart data‑server‑sent‑events när de blir tillgängliga, och strömmen avslutas med ett data: [DONE]-meddelande. |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | Hämtar eller anger vilken samplingstemperatur som ska användas, mellan 0 och 2. Högre värden som 0,8 gör utsignalet mer slumpmässigt, medan lägre värden som 0,2 gör det mer fokuserat och deterministiskt. |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | Hämtar eller anger ett objekt som styr vilket (om något) verktyg som modellen anropar. none betyder att modellen inte kommer att anropa något verktyg utan istället genererar ett meddelande. auto betyder att modellen kan välja mellan att generera ett meddelande eller anropa ett eller flera verktyg. required betyder att modellen måste anropa ett eller flera verktyg. Att specificera ett särskilt verktyg via {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} tvingar modellen att anropa det verktyget. none är standard när inga verktyg finns. auto är standard om verktyg finns. |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | Hämtar eller anger en lista med verktyg som modellen kan anropa. För närvarande stöds endast funktioner som verktyg. Använd detta för att tillhandahålla en lista med funktioner som modellen kan generera JSON‑inmatningar för. Högst 128 funktioner stöds. |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | Hämtar eller anger ett alternativ till sampling med temperatur, kallat nucleus‑sampling, där modellen beaktar tokenresultaten med top_p‑sannolikhetsmassa. Så 0,1 betyder att endast de token som utgör de översta 10 % av sannolikhetsmassan beaktas. |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | Hämtar eller anger en unik identifierare som representerar din slutanvändare, vilket kan hjälpa OpenAI att övervaka och upptäcka missbruk. |

### Se även

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


