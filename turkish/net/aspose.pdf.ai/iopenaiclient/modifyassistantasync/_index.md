---
title: IOpenAIClient.ModifyAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Mevcut bir asistanı asenkron olarak değiştirir
type: docs
weight: 360
url: /tr/net/aspose.pdf.ai/iopenaiclient/modifyassistantasync/
---
## IOpenAIClient.ModifyAssistantAsync metodu

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

Asenkron işlemi temsil eden bir görev. Görev sonucu, asistan değişikliğinden gelen yanıtı içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Asistan ID'si null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [AssistantResponse](../../assistantresponse/)
* sınıf [AssistantModifyRequest](../../assistantmodifyrequest/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)