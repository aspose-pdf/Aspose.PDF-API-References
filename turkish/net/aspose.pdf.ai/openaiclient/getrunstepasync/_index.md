---
title: OpenAIClient.GetRunStepAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Bir çalışmadaki belirli bir adımın ayrıntılarını asenkron olarak alır
type: docs
weight: 270
url: /tr/net/aspose.pdf.ai/openaiclient/getrunstepasync/
---
## OpenAIClient.GetRunStepAsync metodu

Bir çalışmadaki belirli bir adımın ayrıntılarını asenkron olarak alır.

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadId | String | Çalışmayı içeren iş parçacığının kimliği. |
| runId | String | Adımı içeren çalışmanın kimliği. |
| runStepId | String | Alınacak çalışma adımının kimliği. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, çalışma adımının ayrıntılarını içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | İş parçacığı kimliği null veya boş olduğunda fırlatılır. |
| [AIClientException](../../aiclientexception/) | Çalışma kimliği null veya boş olduğunda fırlatılır. |
| [AIClientException](../../aiclientexception/) | Çalışma adımı kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [RunStepResponse](../../runstepresponse/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)