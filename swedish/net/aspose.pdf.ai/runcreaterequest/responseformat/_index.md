---
title: RunCreateRequest.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: RunCreateRequest-egenskap. Hämtar eller ställer in svaret format. Anger det format som modellen måste producera. Kompatibel med GPT-4o, GPT-4 Turbo och alla GPT-3.5 Turbo-modeller sedan gpt-3.5turbo1106. Att ställa in till  type json_object  aktiverar JSON-läge vilket garanterar att meddelandet som modellen genererar är giltig JSON. Viktigt: när du använder JSON-läge måste du också instruera modellen att producera JSON själv via ett system- eller användarmeddelande. Utan detta kan modellen generera en oändlig ström av vita tecken tills generationen når token-gränsen, vilket resulterar i en långvarig och till synes "fast" begäran. Observera också att meddelandets innehåll kan delvis klippas av om finish_reason="length", vilket indikerar att generationen överskred max_tokens eller att konversationen överskred max kontextlängd.
type: docs
weight: 100
url: /sv/net/aspose.pdf.ai/runcreaterequest/responseformat/
---
## RunCreateRequest.ResponseFormat-egenskap

Hämtar eller ställer in svaret format. Anger det format som modellen måste producera. Kompatibel med GPT-4o, GPT-4 Turbo och alla GPT-3.5 Turbo-modeller sedan gpt-3.5-turbo-1106. Att ställa in till { "type": "json_object" } aktiverar JSON-läge, vilket garanterar att meddelandet som modellen genererar är giltig JSON. Viktigt: när du använder JSON-läge måste du också instruera modellen att producera JSON själv via ett system- eller användarmeddelande. Utan detta kan modellen generera en oändlig ström av vita tecken tills generationen når token-gränsen, vilket resulterar i en långvarig och till synes "fast" begäran. Observera också att meddelandets innehåll kan delvis klippas av om finish_reason="length", vilket indikerar att generationen överskred max_tokens eller att konversationen överskred max kontextlängd.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### Se Även

* klass [ResponseFormat](../../responseformat/)
* klass [RunCreateRequest](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)