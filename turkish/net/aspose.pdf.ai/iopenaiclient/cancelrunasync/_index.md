---
title: IOpenAIClient.CancelRunAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Bir iş parçacığı içindeki mevcut bir çalışmayı asenkron olarak iptal eder
type: docs
weight: 10
url: /tr/net/aspose.pdf.ai/iopenaiclient/cancelrunasync/
---
## IOpenAIClient.CancelRunAsync metodu

Bir iş parçacığı içindeki mevcut bir çalışmayı asenkron olarak iptal eder.

```csharp
public Task<RunResponse> CancelRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadId | String | İptal edilecek çalışmayı içeren iş parçacığının kimliği. |
| runId | String | İptal edilecek çalışmanın kimliği. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, çalışma iptali ile ilgili yanıtı içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | İş parçacığı kimliği null veya boş olduğunda fırlatılır. |
| [AIClientException](../../aiclientexception/) | Çalışma kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [RunResponse](../../runresponse/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)