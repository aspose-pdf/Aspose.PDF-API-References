---
title: IOpenAIClient.GetThreadMessagesAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Belirli bir konu için mesajların listesini asenkron olarak alır
type: docs
weight: 290
url: /tr/net/aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/
---
## IOpenAIClient.GetThreadMessagesAsync metodu

Belirli bir konu için mesajların listesini asenkron olarak alır.

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadId | String | Mesajların alınacağı konunun kimliği. |
| queryParameters | ThreadMessageListQueryParameters | Mesajlar listesini filtrelemek için isteğe bağlı sorgu parametreleri. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, konu mesajlarının bir listesini içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thread Id null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [ThreadMessageListResponse](../../threadmessagelistresponse/)
* sınıf [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)