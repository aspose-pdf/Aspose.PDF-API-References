---
title: OpenAIClient.CreateVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Yeni bir vektör mağaza dosya grubunu asenkron olarak oluşturur
type: docs
weight: 120
url: /tr/net/aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/
---
## OpenAIClient.CreateVectorStoreFileBatchAsync metodu

Yeni bir vektör mağaza dosya grubunu asenkron olarak oluşturur.

```csharp
public Task<VectorStoreFileBatchResponse> CreateVectorStoreFileBatchAsync(string vectorStoreId, 
    VectorStoreFileBatchCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vectorStoreId | String | Dosya grubunun oluşturulacağı vektör mağazasının kimliği. |
| vectorStoreFileCreateRequest | VectorStoreFileBatchCreateRequest | Dosya grubunu oluşturmak için ayrıntıları içeren istek nesnesi. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, dosya grubu oluşturma yanıtını içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Vektör mağaza kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* sınıf [VectorStoreFileBatchCreateRequest](../../vectorstorefilebatchcreaterequest/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)