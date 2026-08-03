---
title: "AssistantResponse.ResponseFormat"
second_title: "Aspose.PDF för .NET API‑referens"
description: "AssistantResponse egenskap. Hämtar eller anger formatet som modellen måste leverera. Kompatibel med GPT4o, GPT4 Turbo och alla GPT3.5 Turbo-modeller sedan gpt3.5turbo1106. Att sätta till  type json_object  aktiverar JSON‑läge som garanterar att meddelandet modellen genererar är giltig JSON. Viktigt att när du använder JSON‑läge måste du också instruera modellen att producera JSON själv via ett system‑ eller användarmeddelande. Utan detta kan modellen generera ett oändligt flöde av blanksteg tills genereringen når token‑gränsen, vilket resulterar i en långvarig och till synes fast request. Observera också att meddelandeinnehållet kan bli delvis avklippt om finish_reasonlength, vilket indikerar att genereringen överskred max_tokens eller att konversationen överskred max context length"
type: docs
weight: 100
url: /sv/net/aspose.pdf.ai/assistantresponse/responseformat/
---
## AssistantResponse.ResponseFormat property

Hämtar eller anger det format som modellen måste producera. Kompatibel med GPT-4o, GPT-4 Turbo och alla GPT-3.5 Turbo‑modeller sedan gpt-3.5-turbo-1106. Att sätta till { "type": "json_object" } aktiverar JSON‑läge, vilket garanterar att meddelandet som modellen genererar är giltig JSON. Viktigt: när du använder JSON‑läge måste du också instruera modellen att producera JSON själv via ett system‑ eller användarmeddelande. Utan detta kan modellen generera ett oändligt flöde av blanksteg tills genereringen når token‑gränsen, vilket resulterar i en långvarig och till synes "fast" begäran. Observera också att meddelandeinnehållet kan bli delvis avklippt om finish_reason="length", vilket indikerar att genereringen överskred max_tokens eller att konversationen överskred den maximala kontextlängden.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### Se även

* class [ResponseFormat](../../responseformat/)
* class [AssistantResponse](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


