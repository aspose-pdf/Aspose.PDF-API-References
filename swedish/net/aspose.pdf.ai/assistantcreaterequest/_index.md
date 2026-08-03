---
title: "Klass AssistantCreateRequest"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.AssistantCreateRequest klass. Begäranobjekt för att skapa en assistent."
type: docs
weight: 100
url: /sv/net/aspose.pdf.ai/assistantcreaterequest/
---
## AssistantCreateRequest class

Begäranobjekt för att skapa en assistent.

```csharp
public class AssistantCreateRequest
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [AssistantCreateRequest](assistantcreaterequest/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Description](../../aspose.pdf.ai/assistantcreaterequest/description/) { get; set; } | Hämtar eller anger beskrivningen av assistenten. Maxlängden är 512 tecken. |
| [Instructions](../../aspose.pdf.ai/assistantcreaterequest/instructions/) { get; set; } | Hämtar eller anger systeminstruktionerna som assistenten använder. Maxlängden är 256 000 tecken. |
| [Metadata](../../aspose.pdf.ai/assistantcreaterequest/metadata/) { get; set; } | Hämtar eller anger en uppsättning av 16 nyckel‑värdepar som kan bifogas ett objekt. Detta kan vara användbart för att lagra ytterligare information om objektet i ett strukturerat format. Nycklar kan vara högst 64 tecken långa och värden kan vara högst 512 tecken långa. |
| [Model](../../aspose.pdf.ai/assistantcreaterequest/model/) { get; set; } | Hämtar eller anger ID för den modell som ska användas. Du kan använda List models API:t för att se alla dina tillgängliga modeller, eller se vår Modellöversikt för beskrivningar av dem. |
| [Name](../../aspose.pdf.ai/assistantcreaterequest/name/) { get; set; } | Hämtar eller anger namnet på assistenten. Maxlängden är 256 tecken. |
| [ResponseFormat](../../aspose.pdf.ai/assistantcreaterequest/responseformat/) { get; set; } | Hämtar eller anger det format som modellen måste producera. Kompatibel med GPT-4o, GPT-4 Turbo och alla GPT-3.5 Turbo‑modeller sedan gpt-3.5-turbo-1106. Att sätta till { "type": "json_object" } aktiverar JSON‑läge, vilket garanterar att meddelandet som modellen genererar är giltig JSON. Viktigt: när du använder JSON‑läge måste du också instruera modellen att producera JSON själv via ett system‑ eller användarmeddelande. Utan detta kan modellen generera ett oändligt flöde av blanksteg tills genereringen når token‑gränsen, vilket resulterar i en långvarig och till synes "fast" begäran. Observera också att meddelandeinnehållet kan bli delvis avklippt om finish_reason="length", vilket indikerar att genereringen överskred max_tokens eller att konversationen överskred den maximala kontextlängden. |
| [Temperature](../../aspose.pdf.ai/assistantcreaterequest/temperature/) { get; set; } | Hämtar eller anger provtagnings‑temperaturen att använda, mellan 0 och 2. Högre värden som 0.8 gör output mer slumpmässig, medan lägre värden som 0.2 gör den mer fokuserad och deterministisk. |
| [ToolResources](../../aspose.pdf.ai/assistantcreaterequest/toolresources/) { get; set; } | Hämtar eller anger resurser som används av assistentens verktyg. Resurserna är specifika för verktygstypen. Till exempel kräver code_interpreter‑verktyget en lista med fil‑ID:n, medan file_search‑verktyget kräver en lista med vektor‑lagrings‑ID:n. |
| [Tools](../../aspose.pdf.ai/assistantcreaterequest/tools/) { get; set; } | Hämtar eller anger en lista med verktyg som är aktiverade på assistenten. Det kan finnas högst 128 verktyg per assistent. Verktyg kan vara av typerna code_interpreter, file_search eller function. |
| [TopP](../../aspose.pdf.ai/assistantcreaterequest/topp/) { get; set; } | Hämtar eller anger ett alternativ till provtagning med temperatur, kallat nucleus‑sampling, där modellen beaktar tokenresultaten med top_p‑sannolikhetsmassa. Så betyder 0.1 att endast de token som utgör de översta 10 % av sannolikhetsmassan beaktas. Vi rekommenderar generellt att justera detta eller temperatur, men inte båda. |

### Se även

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


