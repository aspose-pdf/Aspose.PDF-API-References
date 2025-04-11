---
title: OpenAIClient.CreateRunAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Belirtilen bir iş parçacığında asenkron olarak bir çalışma oluşturur
type: docs
weight: 50
url: /tr/net/aspose.pdf.ai/openaiclient/createrunasync/
---
## OpenAIClient.CreateRunAsync metodu

Belirtilen bir iş parçacığında asenkron olarak bir çalışma oluşturur.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadId | String | Çalışmanın oluşturulacağı iş parçacığının kimliği. |
| runCreateRequest | RunCreateRequest | Çalışmayı oluşturmak için istek detayları. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, çalışma oluşturma yanıtını içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | İş parçacığı kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [RunResponse](../../runresponse/)
* sınıf [RunCreateRequest](../../runcreaterequest/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)