---
title: IOpenAIClient.GetRunStepsAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Bir iş parçacığı içindeki belirli bir çalışmanın adımlarının listesini asenkron olarak alır
type: docs
weight: 260
url: /tr/net/aspose.pdf.ai/iopenaiclient/getrunstepsasync/
---
## IOpenAIClient.GetRunStepsAsync metodu

Bir iş parçacığı içindeki belirli bir çalışmanın adımlarının listesini asenkron olarak alır.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadId | String | Çalışmayı içeren iş parçacığının kimliği. |
| runId | String | Adımların alınacağı çalışmanın kimliği. |
| queryParameters | RunStepListQueryParameters | Çalışma adımlarının listesini filtrelemek için isteğe bağlı sorgu parametreleri. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, çalışma adımlarının listesini içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | İş parçacığı kimliği null veya boş olduğunda fırlatılır. |
| [AIClientException](../../aiclientexception/) | Çalışma kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [RunStepListResponse](../../runsteplistresponse/)
* sınıf [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)