---
title: Class AssistantResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.AssistantResponse klass. Representerar en assistent som kan anropa modellen och använda verktyg
type: docs
weight: 140
url: /sv/net/aspose.pdf.ai/assistantresponse/
---
## AssistantResponse klass

Representerar en assistent som kan anropa modellen och använda verktyg.

```csharp
public class AssistantResponse : BaseResponse
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [AssistantResponse](assistantresponse/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/assistantresponse/createdat/) { get; set; } | Hämtar eller sätter Unix-tidsstämpeln (i sekunder) för när assistenten skapades. |
| [Description](../../aspose.pdf.ai/assistantresponse/description/) { get; set; } | Hämtar eller sätter beskrivningen av assistenten. Den maximala längden är 512 tecken. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Hämtar eller sätter svaret i detalj. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Hämtar eller sätter HTTP-svarsfel. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hämtar eller sätter felinformationen. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Hämtar eller sätter HTTP-svarshuvuden. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Hämtar eller sätter HTTP-statuskoden. |
| [Id](../../aspose.pdf.ai/assistantresponse/id/) { get; set; } | Hämtar eller sätter identifieraren, som kan refereras i API-slutpunkter. |
| [Instructions](../../aspose.pdf.ai/assistantresponse/instructions/) { get; set; } | Hämtar eller sätter systeminstruktionerna som assistenten använder. Den maximala längden är 256 000 tecken. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indikerar om svaret var framgångsrikt. |
| [Metadata](../../aspose.pdf.ai/assistantresponse/metadata/) { get; set; } | Hämtar eller sätter en uppsättning av 16 nyckel-värde-par som kan kopplas till ett objekt. Detta kan vara användbart för att lagra ytterligare information om objektet i ett strukturerat format. Nycklar kan vara maximalt 64 tecken långa och värden kan vara maximalt 512 tecken långa. |
| [Model](../../aspose.pdf.ai/assistantresponse/model/) { get; set; } | Hämtar eller sätter ID:t för modellen som ska användas. Du kan använda List models API för att se alla dina tillgängliga modeller, eller se vår Modellöversikt för beskrivningar av dem. |
| [Name](../../aspose.pdf.ai/assistantresponse/name/) { get; set; } | Hämtar eller sätter namnet på assistenten. Den maximala längden är 256 tecken. |
| [Object](../../aspose.pdf.ai/assistantresponse/object/) { get; set; } | Hämtar eller sätter objekttypen, som alltid är assistent. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hämtar felorsaksfrasen. |
| [ResponseFormat](../../aspose.pdf.ai/assistantresponse/responseformat/) { get; set; } | Hämtar eller sätter formatet som modellen måste producera. Kompatibel med GPT-4o, GPT-4 Turbo och alla GPT-3.5 Turbo-modeller sedan gpt-3.5-turbo-1106. Att ställa in på { "type": "json_object" } aktiverar JSON-läget, vilket garanterar att meddelandet som modellen genererar är giltig JSON. Viktigt: när du använder JSON-läget måste du också instruera modellen att producera JSON själv via ett system- eller användarmeddelande. Utan detta kan modellen generera en oändlig ström av vita tecken tills generationen når token-gränsen, vilket resulterar i en långvarig och till synes "fast" begäran. Observera också att meddelandets innehåll kan bli delvis avskuret om finish_reason="length", vilket indikerar att generationen överskred max_tokens eller att konversationen överskred den maximala kontextlängden. |
| [Temperature](../../aspose.pdf.ai/assistantresponse/temperature/) { get; set; } | Hämtar eller sätter vilken provtagningstemperatur som ska användas, mellan 0 och 2. Högre värden som 0.8 gör utdata mer slumpmässiga, medan lägre värden som 0.2 gör dem mer fokuserade och deterministiska. |
| [ToolResources](../../aspose.pdf.ai/assistantresponse/toolresources/) { get; set; } | Hämtar eller sätter en uppsättning resurser som används av assistentens verktyg. Resurserna är specifika för typen av verktyg. Till exempel kräver verktyget code_interpreter en lista över fil-ID:n, medan verktyget file_search kräver en lista över vektorbutiks-ID:n. |
| [Tools](../../aspose.pdf.ai/assistantresponse/tools/) { get; set; } | Hämtar eller sätter en lista över verktyg som är aktiverade på assistenten. Det kan finnas maximalt 128 verktyg per assistent. Verktyg kan vara av typerna code_interpreter, file_search eller function. |
| [TopP](../../aspose.pdf.ai/assistantresponse/topp/) { get; set; } | Hämtar eller sätter ett alternativ till provtagning med temperatur, kallad nucleus sampling, där modellen överväger resultaten av token med top_p sannolikhetsmassa. Så 0.1 betyder att endast de token som utgör den översta 10% sannolikhetsmassan beaktas. Vi rekommenderar generellt att ändra detta eller temperaturen men inte båda. |

### Se Även

* klass [BaseResponse](../baseresponse/)
* namnrymd [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../)