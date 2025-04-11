---
title: Class AssistantModifyRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.AssistantModifyRequest klass. Begärningsobjekt för att modifiera en assistent
type: docs
weight: 130
url: /sv/net/aspose.pdf.ai/assistantmodifyrequest/
---
## AssistantModifyRequest klass

Begärningsobjekt för att modifiera en assistent.

```csharp
public class AssistantModifyRequest : AssistantCreateRequest
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [AssistantModifyRequest](assistantmodifyrequest/)() | Den standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Description](../../aspose.pdf.ai/assistantcreaterequest/description/) { get; set; } | Hämtar eller sätter beskrivningen av assistenten. Den maximala längden är 512 tecken. |
| [Instructions](../../aspose.pdf.ai/assistantcreaterequest/instructions/) { get; set; } | Hämtar eller sätter systeminstruktionerna som assistenten använder. Den maximala längden är 256 000 tecken. |
| [Metadata](../../aspose.pdf.ai/assistantcreaterequest/metadata/) { get; set; } | Hämtar eller sätter en uppsättning av 16 nyckel-värde-par som kan kopplas till ett objekt. Detta kan vara användbart för att lagra ytterligare information om objektet i ett strukturerat format. Nycklar kan vara maximalt 64 tecken långa och värden kan vara maximalt 512 tecken långa. |
| [Model](../../aspose.pdf.ai/assistantcreaterequest/model/) { get; set; } | Hämtar eller sätter ID för den modell som ska användas. Du kan använda List models API för att se alla dina tillgängliga modeller, eller se vår Modellöversikt för beskrivningar av dem. |
| [Name](../../aspose.pdf.ai/assistantcreaterequest/name/) { get; set; } | Hämtar eller sätter namnet på assistenten. Den maximala längden är 256 tecken. |
| [ResponseFormat](../../aspose.pdf.ai/assistantcreaterequest/responseformat/) { get; set; } | Hämtar eller sätter formatet som modellen måste producera. Kompatibel med GPT-4o, GPT-4 Turbo och alla GPT-3.5 Turbo-modeller sedan gpt-3.5-turbo-1106. Att ställa in på { "type": "json_object" } aktiverar JSON-läge, vilket garanterar att meddelandet som modellen genererar är giltig JSON. Viktigt: när du använder JSON-läge måste du också instruera modellen att producera JSON själv via ett system- eller användarmedelande. Utan detta kan modellen generera en oändlig ström av vita tecken tills generationen når token-gränsen, vilket resulterar i en långvarig och till synes "fast" begäran. Observera också att meddelandets innehåll kan bli delvis avskuret om finish_reason="length", vilket indikerar att generationen överskred max_tokens eller att konversationen överskred den maximala kontextlängden. |
| [Temperature](../../aspose.pdf.ai/assistantcreaterequest/temperature/) { get; set; } | Hämtar eller sätter provtagningstemperaturen som ska användas, mellan 0 och 2. Högre värden som 0.8 gör utdata mer slumpmässiga, medan lägre värden som 0.2 gör dem mer fokuserade och deterministiska. |
| [ToolResources](../../aspose.pdf.ai/assistantcreaterequest/toolresources/) { get; set; } | Hämtar eller sätter resurser som används av assistentens verktyg. Resurserna är specifika för typen av verktyg. Till exempel kräver verktyget code_interpreter en lista över fil-ID:n, medan verktyget file_search kräver en lista över vektorbutiks-ID:n. |
| [Tools](../../aspose.pdf.ai/assistantcreaterequest/tools/) { get; set; } | Hämtar eller sätter en lista över verktyg som är aktiverade på assistenten. Det kan finnas maximalt 128 verktyg per assistent. Verktyg kan vara av typerna code_interpreter, file_search eller function. |
| [TopP](../../aspose.pdf.ai/assistantcreaterequest/topp/) { get; set; } | Hämtar eller sätter ett alternativ till provtagning med temperatur, kallad nucleus sampling, där modellen överväger resultaten av token med top_p sannolikhetsmassa. Så 0.1 betyder att endast de token som utgör den översta 10% sannolikhetsmassan beaktas. Vi rekommenderar generellt att ändra detta eller temperaturen men inte båda. |

### Se Även

* klass [AssistantCreateRequest](../assistantcreaterequest/)
* namnrymd [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../)