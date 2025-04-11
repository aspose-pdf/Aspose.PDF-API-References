---
title: IOpenAIClient.GetRunAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Bir iş parçacığı içindeki belirli bir çalışmanın ayrıntılarını asenkron olarak alır
type: docs
weight: 230
url: /tr/net/aspose.pdf.ai/iopenaiclient/getrunasync/
---
## IOpenAIClient.GetRunAsync metodu

Bir iş parçacığı içindeki belirli bir çalışmanın ayrıntılarını asenkron olarak alır.

```csharp
public Task<RunResponse> GetRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadId | String | Çalışmayı içeren iş parçacığının kimliği. |
| runId | String | Alınacak çalışmanın kimliği. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, çalışmanın ayrıntılarını içerir.

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