---
title: IOpenAIClient.CreateThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Bir iş parçacığında asenkron olarak yeni bir mesaj oluşturur
type: docs
weight: 80
url: /tr/net/aspose.pdf.ai/iopenaiclient/createthreadmessageasync/
---
## IOpenAIClient.CreateThreadMessageAsync metodu

Bir iş parçacığında asenkron olarak yeni bir mesaj oluşturur.

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, 
    ThreadMessageCreateRequest threadMessageRequest, CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadId | String | Mesajın oluşturulacağı iş parçacığının kimliği. |
| threadMessageRequest | ThreadMessageCreateRequest | Mesajı oluşturmak için istek detayları. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, mesaj oluşturma yanıtını içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thread Id null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [ThreadMessageResponse](../../threadmessageresponse/)
* sınıf [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)