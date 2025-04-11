---
title: OpenAIClient.GetVectorStoreFileBatchFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Belirli bir vektör depolama dosya grubundaki dosyaların listesini asenkron olarak alır
type: docs
weight: 360
url: /tr/net/aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/
---
## OpenAIClient.GetVectorStoreFileBatchFilesAsync metodu

Belirli bir vektör depolama dosya grubundaki dosyaların listesini asenkron olarak alır.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vectorStoreId | String | Dosya grubunu içeren vektör depolamanın kimliği. |
| fileBatchId | String | Dosyaların alınacağı dosya grubunun kimliği. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | Dosya listesini filtrelemek için isteğe bağlı sorgu parametreleri. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, dosya grubundaki dosyaların listesini içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Vektör depolama kimliği null veya boş olduğunda fırlatılır. |
| [AIClientException](../../aiclientexception/) | Vektör depolama dosya grubu kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* sınıf [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)