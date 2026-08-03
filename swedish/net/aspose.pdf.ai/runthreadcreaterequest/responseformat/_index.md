---
title: "RunThreadCreateRequest.ResponseFormat"
second_title: "Aspose.PDF för .NET API‑referens"
description: "RunThreadCreateRequest egenskap. Hämtar eller anger formatet som modellen måste returnera. Kompatibel med GPT4o, GPT4 Turbo och alla GPT3.5 Turbo-modeller sedan gpt3.5turbo1106. Att sätta till typ json_object aktiverar JSON-läge som garanterar att meddelandet som modellen genererar är giltig JSON. Viktigt: när du använder JSON-läge måste du även instruera modellen att producera JSON själv via ett system- eller användarmeddelande. Utan detta kan modellen generera ett oändligt flöde av blanksteg tills genereringen når token-gränsen, vilket resulterar i en långvarig och till synes fastfrusen begäran. Observera också att meddelandeinnehållet kan bli delvis avklippt om finish_reasonlength, vilket indikerar att genereringen överskred max_tokens eller att konversationen överskred den maximala kontextlängden."
type: docs
weight: 80
url: /sv/net/aspose.pdf.ai/runthreadcreaterequest/responseformat/
---
## RunThreadCreateRequest.ResponseFormat property

Hämtar eller anger det format som modellen måste returnera. Kompatibel med GPT-4o, GPT-4 Turbo och alla GPT-3.5 Turbo-modeller sedan gpt-3.5-turbo-1106. Att sätta till { "type": "json_object" } aktiverar JSON-läge, vilket garanterar att meddelandet som modellen genererar är giltig JSON. Viktigt: när du använder JSON-läge måste du också instruera modellen att själv producera JSON via ett system‑ eller användarmeddelande. Utan detta kan modellen generera en oändlig ström av blanksteg tills genereringen når token‑gränsen, vilket resulterar i en långvarig och till synes "fast" begäran. Observera också att meddelandeinnehållet kan bli delvis avklippt om finish_reason="length", vilket indikerar att genereringen överskred max_tokens eller att konversationen överskred den maximala kontextlängden.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### Se även

* class [ResponseFormat](../../responseformat/)
* class [RunThreadCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


