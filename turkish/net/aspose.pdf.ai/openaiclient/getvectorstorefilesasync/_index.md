---
title: OpenAIClient.GetVectorStoreFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient yöntemi. Belirli bir vektör deposundaki dosyaların listesini asenkron olarak alır
type: docs
weight: 370
url: /tr/net/aspose.pdf.ai/openaiclient/getvectorstorefilesasync/
---
## OpenAIClient.GetVectorStoreFilesAsync yöntemi

Belirli bir vektör deposundaki dosyaların listesini asenkron olarak alır.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFilesAsync(string vectorStoreId, 
    VectorStoreFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vectorStoreId | String | Dosyaları içeren vektör deposunun kimliği. |
| queryParameters | VectorStoreFileListQueryParameters | Dosya listesini filtrelemek için isteğe bağlı sorgu parametreleri. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, vektör deposundaki dosyaların bir listesini içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Vektör deposu kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* sınıf [VectorStoreFileListQueryParameters](../../vectorstorefilelistqueryparameters/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)