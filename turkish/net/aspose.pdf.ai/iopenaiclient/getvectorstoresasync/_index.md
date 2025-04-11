---
title: IOpenAIClient.GetVectorStoresAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient yöntemi. Vektör depolarının listesini asenkron olarak alır
type: docs
weight: 350
url: /tr/net/aspose.pdf.ai/iopenaiclient/getvectorstoresasync/
---
## IOpenAIClient.GetVectorStoresAsync yöntemi

Vektör depolarının listesini asenkron olarak alır.

```csharp
public Task<VectorStoreListResponse> GetVectorStoresAsync(
    VectorStoreListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| queryParameters | VectorStoreListQueryParameters | Vektör depoları listesini filtrelemek için isteğe bağlı sorgu parametreleri. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, vektör depolarının bir listesini içerir.

### Ayrıca Bakınız

* sınıf [VectorStoreListResponse](../../vectorstorelistresponse/)
* sınıf [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)