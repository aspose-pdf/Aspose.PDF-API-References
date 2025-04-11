---
title: OpenAIClient.ModifyRunAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Bir iş parçacığı içindeki mevcut bir çalışmayı asenkron olarak değiştirir
type: docs
weight: 400
url: /tr/net/aspose.pdf.ai/openaiclient/modifyrunasync/
---
## OpenAIClient.ModifyRunAsync metodu

Bir iş parçacığı içindeki mevcut bir çalışmayı asenkron olarak değiştirir.

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadId | String | Çalışmayı içeren iş parçacığının kimliği. |
| runId | String | Değiştirilecek çalışmanın kimliği. |
| assistantModifyRequest | RunModifyRequest | Çalışmayı değiştirmek için istek detayları. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, çalışma değişikliği ile ilgili yanıtı içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | İş parçacığı kimliği null veya boş olduğunda fırlatılır. |
| [AIClientException](../../aiclientexception/) | Çalışma kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [RunResponse](../../runresponse/)
* sınıf [RunModifyRequest](../../runmodifyrequest/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)