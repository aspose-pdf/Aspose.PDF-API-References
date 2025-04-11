---
title: OpenAIClient.WaitForRunToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Bir çalışmanın bir iş parçacığında asenkron olarak tamamlanmasını bekler
type: docs
weight: 470
url: /tr/net/aspose.pdf.ai/openaiclient/waitforruntocompleteasync/
---
## OpenAIClient.WaitForRunToCompleteAsync metodu

Bir çalışmanın bir iş parçacığında asenkron olarak tamamlanmasını bekler.

```csharp
public Task<RunResponse> WaitForRunToCompleteAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadId | String | Çalışmayı içeren iş parçacığının kimliği. |
| runId | String | Tamamlanana kadar izlenecek çalışmanın kimliği. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, çalışmanın son durumunu içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | İş parçacığı kimliği null veya boş olduğunda fırlatılır. |
| [AIClientException](../../aiclientexception/) | Çalışma kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [RunResponse](../../runresponse/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)