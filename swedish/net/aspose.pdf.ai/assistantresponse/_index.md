---
title: "Klass AssistantResponse"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.AssistantResponse-klass. Representerar en assistent som kan anropa modellen och använda verktyg"
type: docs
weight: 140
url: /sv/net/aspose.pdf.ai/assistantresponse/
---
## AssistantResponse class

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
| [CreatedAt](../../aspose.pdf.ai/assistantresponse/createdat/) { get; set; } | Hämtar eller anger Unix-tidsstämpeln (i sekunder) för när assistenten skapades. |
| [Description](../../aspose.pdf.ai/assistantresponse/description/) { get; set; } | Hämtar eller anger beskrivningen av assistenten. Maxlängden är 512 tecken. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Hämtar eller anger svarsdetaljen. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Hämtar eller anger HTTP‑svarsfelet. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hämtar eller anger felinformationen. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Hämtar eller anger HTTP‑svarsrubriker. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Hämtar eller anger HTTP‑statuskoden. |
| [Id](../../aspose.pdf.ai/assistantresponse/id/) { get; set; } | Hämtar eller anger identifieraren, som kan refereras i API‑slutpunkter. |
| [Instructions](../../aspose.pdf.ai/assistantresponse/instructions/) { get; set; } | Hämtar eller anger systeminstruktionerna som assistenten använder. Maxlängden är 256 000 tecken. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indikerar om svaret var framgångsrikt. |
| [Metadata](../../aspose.pdf.ai/assistantresponse/metadata/) { get; set; } | Hämtar eller anger en uppsättning av 16 nyckel‑värdepar som kan bifogas ett objekt. Detta kan vara användbart för att lagra ytterligare information om objektet i ett strukturerat format. Nycklar kan vara högst 64 tecken långa och värden kan vara högst 512 tecken långa. |
| [Model](../../aspose.pdf.ai/assistantresponse/model/) { get; set; } | Hämtar eller anger ID för den modell som ska användas. Du kan använda List models API för att se alla dina tillgängliga modeller, eller se vår Model‑översikt för beskrivningar av dem. |
| [Name](../../aspose.pdf.ai/assistantresponse/name/) { get; set; } | Hämtar eller anger namnet på assistenten. Maxlängden är 256 tecken. |
| [Object](../../aspose.pdf.ai/assistantresponse/object/) { get; set; } | Hämtar eller anger objekttypen, som alltid är assistant. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hämtar felorsakens fras. |
| [ResponseFormat](../../aspose.pdf.ai/assistantresponse/responseformat/) { get; set; } | Hämtar eller anger det format som modellen måste producera. Kompatibel med GPT-4o, GPT-4 Turbo och alla GPT-3.5 Turbo‑modeller sedan gpt-3.5-turbo-1106. Att sätta till { "type": "json_object" } aktiverar JSON‑läge, vilket garanterar att meddelandet som modellen genererar är giltig JSON. Viktigt: när du använder JSON‑läge måste du också instruera modellen att producera JSON själv via ett system‑ eller användarmeddelande. Utan detta kan modellen generera ett oändligt flöde av blanksteg tills genereringen når token‑gränsen, vilket resulterar i en långvarig och till synes "fast" begäran. Observera också att meddelandeinnehållet kan bli delvis avklippt om finish_reason="length", vilket indikerar att genereringen överskred max_tokens eller att konversationen överskred den maximala kontextlängden. |
| [Temperature](../../aspose.pdf.ai/assistantresponse/temperature/) { get; set; } | Hämtar eller anger vilken samplingstemperatur som ska användas, mellan 0 och 2. Högre värden som 0,8 gör utsignalet mer slumpmässigt, medan lägre värden som 0,2 gör det mer fokuserat och deterministiskt. |
| [ToolResources](../../aspose.pdf.ai/assistantresponse/toolresources/) { get; set; } | Hämtar eller anger en uppsättning resurser som används av assistentens verktyg. Resurserna är specifika för verktygstypen. Till exempel kräver verktyget code_interpreter en lista med fil‑ID:n, medan verktyget file_search kräver en lista med vektorlager‑ID:n. |
| [Tools](../../aspose.pdf.ai/assistantresponse/tools/) { get; set; } | Hämtar eller anger en lista med verktyg som är aktiverade på assistenten. Det kan finnas högst 128 verktyg per assistent. Verktyg kan vara av typerna code_interpreter, file_search eller function. |
| [TopP](../../aspose.pdf.ai/assistantresponse/topp/) { get; set; } | Hämtar eller anger ett alternativ till provtagning med temperatur, kallat nucleus‑sampling, där modellen beaktar tokenresultaten med top_p‑sannolikhetsmassa. Så betyder 0.1 att endast de token som utgör de översta 10 % av sannolikhetsmassan beaktas. Vi rekommenderar generellt att justera detta eller temperatur, men inte båda. |

### Se även

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


