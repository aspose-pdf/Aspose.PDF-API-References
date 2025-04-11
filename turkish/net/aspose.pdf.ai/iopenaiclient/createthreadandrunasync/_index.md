---
title: IOpenAIClient.CreateThreadAndRunAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Asenkron olarak bir thread ve içinde bir run oluşturur
type: docs
weight: 60
url: /tr/net/aspose.pdf.ai/iopenaiclient/createthreadandrunasync/
---
## IOpenAIClient.CreateThreadAndRunAsync metodu

Asenkron olarak bir thread ve içinde bir run oluşturur.

```csharp
public Task<RunResponse> CreateThreadAndRunAsync(RunThreadCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| runCreateRequest | RunThreadCreateRequest | Thread ve run oluşturma için istek detayları. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, thread ve run oluşturma yanıtını içerir.

### Ayrıca Bakınız

* sınıf [RunResponse](../../runresponse/)
* sınıf [RunThreadCreateRequest](../../runthreadcreaterequest/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)