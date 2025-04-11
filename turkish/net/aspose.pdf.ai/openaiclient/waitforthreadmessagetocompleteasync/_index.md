---
title: OpenAIClient.WaitForThreadMessageToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Belirli bir thread mesajının asenkron olarak tamamlanmasını bekler
type: docs
weight: 480
url: /tr/net/aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/
---
## OpenAIClient.WaitForThreadMessageToCompleteAsync metodu

Belirli bir thread mesajının asenkron olarak tamamlanmasını bekler.

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadId | String | Mesajı içeren thread'in ID'si. |
| threadMessageId | String | Tamamlanana kadar izlenecek mesajın ID'si. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, mesajın son durumunu içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thread ID'si null veya boş olduğunda fırlatılır. |
| [AIClientException](../../aiclientexception/) | Thread mesaj ID'si null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [ThreadMessageResponse](../../threadmessageresponse/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)