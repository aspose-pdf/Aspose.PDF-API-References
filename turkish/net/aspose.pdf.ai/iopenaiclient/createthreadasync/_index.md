---
title: IOpenAIClient.CreateThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Yeni bir iş parçacığını asenkron olarak oluşturur
type: docs
weight: 70
url: /tr/net/aspose.pdf.ai/iopenaiclient/createthreadasync/
---
## IOpenAIClient.CreateThreadAsync metodu

Yeni bir iş parçacığını asenkron olarak oluşturur.

```csharp
public Task<ThreadResponse> CreateThreadAsync(ThreadCreateRequest threadCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadCreateRequest | ThreadCreateRequest | İş parçacığını oluşturmak için detayları içeren istek nesnesi. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, iş parçacığı oluşturma yanıtını içerir.

### Ayrıca Bakınız

* sınıf [ThreadResponse](../../threadresponse/)
* sınıf [ThreadCreateRequest](../../threadcreaterequest/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)