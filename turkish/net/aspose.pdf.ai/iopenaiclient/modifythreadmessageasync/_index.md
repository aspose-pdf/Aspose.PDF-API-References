---
title: IOpenAIClient.ModifyThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient yöntemi. Bir iplik içindeki mevcut bir mesajı asenkron olarak değiştirir
type: docs
weight: 390
url: /tr/net/aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/
---
## IOpenAIClient.ModifyThreadMessageAsync yöntemi

Bir iplik içindeki mevcut bir mesajı asenkron olarak değiştirir.

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadId | String | Değiştirilecek mesajı içeren ipliğin kimliği. |
| threadMessageId | String | Değiştirilecek mesajın kimliği. |
| threadMessageModifyRequest | ThreadMessageModifyRequest | Mesajı değiştirmek için istek detayları. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, mesaj değişikliğinden gelen yanıtı içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | İplik kimliği null veya boş olduğunda fırlatılır. |
| [AIClientException](../../aiclientexception/) | İplik mesaj kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [ThreadMessageResponse](../../threadmessageresponse/)
* sınıf [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)