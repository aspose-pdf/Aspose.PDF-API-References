---
title: OpenAIClient.GetRunsAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Belirtilen bir iş parçacığı için çalışmaları asenkron olarak alır
type: docs
weight: 260
url: /tr/net/aspose.pdf.ai/openaiclient/getrunsasync/
---
## OpenAIClient.GetRunsAsync metodu

Belirtilen bir iş parçacığı için çalışmaları asenkron olarak alır.

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadId | String | Çalışmaları almak için iş parçacığının kimliği. |
| queryParameters | RunListQueryParameters | Çalışma listesini filtrelemek için isteğe bağlı sorgu parametreleri. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, bir çalışma listesi içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | İş parçacığı kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [RunListResponse](../../runlistresponse/)
* sınıf [RunListQueryParameters](../../runlistqueryparameters/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)