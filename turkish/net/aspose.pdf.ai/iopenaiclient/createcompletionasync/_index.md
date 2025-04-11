---
title: IOpenAIClient.CreateCompletionAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Yeni bir tamamlamayı asenkron olarak oluşturur
type: docs
weight: 40
url: /tr/net/aspose.pdf.ai/iopenaiclient/createcompletionasync/
---
## IOpenAIClient.CreateCompletionAsync metodu

Yeni bir tamamlamayı asenkron olarak oluşturur.

```csharp
public Task<CompletionResponse> CreateCompletionAsync(
    CompletionCreateRequest completionCreateRequest, CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| completionCreateRequest | CompletionCreateRequest | Tamamlamayı oluşturmak için detayları içeren istek nesnesi. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, tamamlamanın oluşturulmasından gelen yanıtı içerir.

### Ayrıca Bakınız

* sınıf [CompletionResponse](../../completionresponse/)
* sınıf [CompletionCreateRequest](../../completioncreaterequest/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)