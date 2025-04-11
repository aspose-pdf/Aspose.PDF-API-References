---
title: Class CompletionCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CompletionCreateRequest klass. Representerar en begäran för Create Chat Completion slutpunkt
type: docs
weight: 220
url: /sv/net/aspose.pdf.ai/completioncreaterequest/
---
## CompletionCreateRequest klass

Representerar en begäran för Create Chat Completion slutpunkt.

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
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | Hämtar eller ställer in ett nummer mellan -2.0 och 2.0. Positiva värden straffar nya token baserat på deras befintliga frekvens i texten hittills, vilket minskar modellens sannolikhet att upprepa samma rad ordagrant. |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | Hämtar eller ställer in sannolikheten för att specificerade token ska dyka upp i fullföljandet. Accepterar ett JSON-objekt som kartlägger token (specificerade med deras token-ID i tokenizer) till ett associerat biasvärde från -100 till 100. |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | Hämtar eller ställer in om log-sannolikheter för utdata-token ska returneras eller inte. Om sant, returnerar log-sannolikheterna för varje utdata-token som returneras i meddelandets innehåll. |
| [MaxTokens](../../aspose.pdf.ai/completioncreaterequest/maxtokens/) { get; set; } | Hämtar eller ställer in det maximala antalet token som ska genereras i fullföljandet. |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | Hämtar eller ställer in en lista med meddelanden som utgör konversationen hittills. |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | Hämtar eller ställer in ID:t för den modell som ska användas. |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | Hämtar eller ställer in hur många chat fullföljande val som ska genereras för varje inmatningsmeddelande. Observera att du kommer att debiteras baserat på antalet genererade token över alla val. Håll n som 1 för att minimera kostnader. |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | Hämtar eller ställer in ett nummer mellan -2.0 och 2.0. Positiva värden straffar nya token baserat på om de dyker upp i texten hittills, vilket ökar modellens sannolikhet att prata om nya ämnen. |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | Hämtar eller ställer in ett objekt som specificerar formatet som modellen måste producera. Kompatibel med GPT-4 Turbo och alla GPT-3.5 Turbo-modeller nyare än gpt-3.5-turbo-1106. Att ställa in på { "type": "json_object" } aktiverar JSON-läge, vilket garanterar att meddelandet som modellen genererar är giltig JSON. |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | Hämtar eller ställer in Seed-värdet. Denna funktion är i Beta. Om specificerat kommer vårt system att göra sitt bästa för att provta deterministiskt, så att upprepade begärningar med samma seed och parametrar bör returnera samma resultat. Determinism garanteras inte, och du bör hänvisa till system_fingerprint-svarparametern för att övervaka förändringar i backend. |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | Hämtar eller ställer in upp till 4 sekvenser där API:et kommer att sluta generera ytterligare token. |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | Hämtar eller ställer in om streaming ska användas. Om inställt kommer delvisa meddelandedeltan att skickas, som i ChatGPT. Token kommer att skickas som data-endast server-sända händelser när de blir tillgängliga, med strömmen avslutad av ett data: [DONE] meddelande. |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | Hämtar eller ställer in vilken samplingstemperatur som ska användas, mellan 0 och 2. Högre värden som 0.8 kommer att göra utdata mer slumpmässiga, medan lägre värden som 0.2 kommer att göra dem mer fokuserade och deterministiska. |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | Hämtar eller ställer in ett objekt som kontrollerar vilken (om någon) verktyg som anropas av modellen. none betyder att modellen inte kommer att anropa något verktyg och istället genererar ett meddelande. auto betyder att modellen kan välja mellan att generera ett meddelande eller anropa ett eller flera verktyg. required betyder att modellen måste anropa ett eller flera verktyg. Att specificera ett särskilt verktyg via {"type": "function", "function": {"name": "my_function"}} tvingar modellen att anropa det verktyget. none är standard när inga verktyg är närvarande. auto är standard om verktyg är närvarande. |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | Hämtar eller ställer in en lista med verktyg som modellen kan anropa. För närvarande stöds endast funktioner som verktyg. Använd detta för att tillhandahålla en lista med funktioner som modellen kan generera JSON-inmatningar för. Max 128 funktioner stöds. |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | Hämtar eller ställer in ett alternativ till sampling med temperatur, kallad nucleus sampling, där modellen överväger resultaten av token med top_p sannolikhetsmassa. Så 0.1 betyder att endast token som utgör den översta 10% sannolikhetsmassan beaktas. |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | Hämtar eller ställer in en unik identifierare som representerar din slutanvändare, vilket kan hjälpa OpenAI att övervaka och upptäcka missbruk. |

### Se Även

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)