---
title: IOpenAIClient.GetVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Belirli bir vektör deposunun ayrıntılarını asenkron olarak alır
type: docs
weight: 300
url: /tr/net/aspose.pdf.ai/iopenaiclient/getvectorstoreasync/
---
## IOpenAIClient.GetVectorStoreAsync metodu

Belirli bir vektör deposunun ayrıntılarını asenkron olarak alır.

```csharp
public Task<VectorStoreResponse> GetVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vectorStoreId | String | Alınacak vektör deposunun ID'si. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, vektör deposunun ayrıntılarını içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Vektör deposu ID'si null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [VectorStoreResponse](../../vectorstoreresponse/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)