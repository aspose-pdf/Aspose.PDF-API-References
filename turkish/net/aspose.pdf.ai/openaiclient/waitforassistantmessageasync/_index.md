---
title: OpenAIClient.WaitForAssistantMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Bir iş parçacığında asenkron olarak asistandan gelen ilk mesajı bekler
type: docs
weight: 460
url: /tr/net/aspose.pdf.ai/openaiclient/waitforassistantmessageasync/
---
## OpenAIClient.WaitForAssistantMessageAsync metodu

Bir iş parçacığında asenkron olarak asistandan gelen ilk mesajı bekler.

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadId | String | İlk asistan mesajını izlemek için iş parçacığının kimliği. |
| queryParameters | ThreadMessageListQueryParameters | Mesaj listesini filtrelemek için isteğe bağlı sorgu parametreleri. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, iş parçacığındaki ilk asistan mesajını içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | İş parçacığı kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [ThreadMessageResponse](../../threadmessageresponse/)
* sınıf [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)