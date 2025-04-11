---
title: OpenAIClient.GetThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient yöntemi. Bir iplik içindeki belirli bir mesajın ayrıntılarını asenkron olarak alır
type: docs
weight: 310
url: /tr/net/aspose.pdf.ai/openaiclient/getthreadmessageasync/
---
## OpenAIClient.GetThreadMessageAsync yöntemi

Bir iplik içindeki belirli bir mesajın ayrıntılarını asenkron olarak alır.

```csharp
public Task<ThreadMessageResponse> GetThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadId | String | Mesajı içeren ipliğin kimliği. |
| threadMessageId | String | Alınacak mesajın kimliği. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, iplik mesajının ayrıntılarını içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | İplik Kimliği null veya boş olduğunda fırlatılır. |
| [AIClientException](../../aiclientexception/) | İplik mesajı Kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [ThreadMessageResponse](../../threadmessageresponse/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)