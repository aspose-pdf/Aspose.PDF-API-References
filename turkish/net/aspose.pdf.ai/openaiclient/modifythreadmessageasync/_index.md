---
title: OpenAIClient.ModifyThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Bir iplikte mevcut bir mesajı asenkron olarak değiştirir
type: docs
weight: 420
url: /tr/net/aspose.pdf.ai/openaiclient/modifythreadmessageasync/
---
## OpenAIClient.ModifyThreadMessageAsync metodu

Bir iplikte mevcut bir mesajı asenkron olarak değiştirir.

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadId | String | Değiştirilecek mesajı içeren ipliğin ID'si. |
| threadMessageId | String | Değiştirilecek mesajın ID'si. |
| threadMessageModifyRequest | ThreadMessageModifyRequest | Mesajı değiştirmek için istek detayları. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, mesaj değişikliğinden gelen yanıtı içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | İplik ID'si null veya boş olduğunda fırlatılır. |
| [AIClientException](../../aiclientexception/) | İplik mesaj ID'si null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [ThreadMessageResponse](../../threadmessageresponse/)
* sınıf [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)