---
title: IOpenAIClient.CreateVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Yeni bir vektör deposunu asenkron olarak oluşturur
type: docs
weight: 100
url: /tr/net/aspose.pdf.ai/iopenaiclient/createvectorstoreasync/
---
## IOpenAIClient.CreateVectorStoreAsync metodu

Yeni bir vektör deposunu asenkron olarak oluşturur.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | Vektör deposunu oluşturmak için detayları içeren istek nesnesi. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, vektör deposu oluşturma yanıtını içerir.

### Ayrıca Bakınız

* sınıf [VectorStoreResponse](../../vectorstoreresponse/)
* sınıf [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)