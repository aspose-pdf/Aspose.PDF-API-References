---
title: OpenAIClient.ModifyAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Mevcut bir asistanı asenkron olarak değiştirir
type: docs
weight: 390
url: /tr/net/aspose.pdf.ai/openaiclient/modifyassistantasync/
---
## OpenAIClient.ModifyAssistantAsync metodu

Mevcut bir asistanı asenkron olarak değiştirir.

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| assistantId | String | Değiştirilecek asistanın ID'si. |
| assistantModifyRequest | AssistantModifyRequest | Değişiklik detaylarını içeren istek nesnesi. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, asistan değişikliği ile ilgili yanıtı içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Asistan ID'si null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [AssistantResponse](../../assistantresponse/)
* sınıf [AssistantModifyRequest](../../assistantmodifyrequest/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)