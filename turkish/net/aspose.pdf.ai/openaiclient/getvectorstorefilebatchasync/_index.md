---
title: OpenAIClient.GetVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Belirli bir vektör mağaza dosya grubunun ayrıntılarını asenkron olarak alır
type: docs
weight: 350
url: /tr/net/aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/
---
## OpenAIClient.GetVectorStoreFileBatchAsync metodu

Belirli bir vektör mağaza dosya grubunun ayrıntılarını asenkron olarak alır.

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vectorStoreId | String | Dosya grubunu içeren vektör mağazasının ID'si. |
| fileBatchId | String | Alınacak dosya grubunun ID'si. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, dosya grubunun ayrıntılarını içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Vektör mağaza ID'si null veya boş olduğunda fırlatılır. |
| [AIClientException](../../aiclientexception/) | Vektör mağaza dosya grubu ID'si null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)