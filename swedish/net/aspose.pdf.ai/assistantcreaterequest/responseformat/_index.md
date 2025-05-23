---
title: AssistantCreateRequest.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: AssistantCreateRequest-egenskap. Hämtar eller ställer in det format som modellen måste producera. Kompatibel med GPT-4o, GPT-4 Turbo och alla GPT-3.5 Turbo-modeller sedan gpt-3.5-turbo-1106. Att ställa in till "type" "json_object" aktiverar JSON-läge, vilket garanterar att meddelandet som modellen genererar är giltig JSON. Viktigt när du använder JSON-läge måste du också instruera modellen att producera JSON själv via ett system- eller användarmedelande. Utan detta kan modellen generera en oändlig ström av vita tecken tills generationen når token-gränsen, vilket resulterar i en långvarig och till synes "fast" begäran. Observera också att meddelandets innehåll kan bli delvis avskuret om finish_reason="length", vilket indikerar att generationen överskred max_tokens eller att konversationen överskred den maximala kontextlängden.
type: docs
weight: 70
url: /sv/net/aspose.pdf.ai/assistantcreaterequest/responseformat/
---
## AssistantCreateRequest.ResponseFormat-egenskap

Hämtar eller ställer in det format som modellen måste producera. Kompatibel med GPT-4o, GPT-4 Turbo och alla GPT-3.5 Turbo-modeller sedan gpt-3.5-turbo-1106. Att ställa in till { "type": "json_object" } aktiverar JSON-läge, vilket garanterar att meddelandet som modellen genererar är giltig JSON. Viktigt: när du använder JSON-läge måste du också instruera modellen att producera JSON själv via ett system- eller användarmedelande. Utan detta kan modellen generera en oändlig ström av vita tecken tills generationen når token-gränsen, vilket resulterar i en långvarig och till synes "fast" begäran. Observera också att meddelandets innehåll kan bli delvis avskuret om finish_reason="length", vilket indikerar att generationen överskred max_tokens eller att konversationen överskred den maximala kontextlängden.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### Se Även

* klass [ResponseFormat](../../responseformat/)
* klass [AssistantCreateRequest](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)