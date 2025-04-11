---
title: OpenAIClient.CreateVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Yeni bir vektör mağaza dosyasını asenkron olarak oluşturur
type: docs
weight: 110
url: /tr/net/aspose.pdf.ai/openaiclient/createvectorstorefileasync/
---
## OpenAIClient.CreateVectorStoreFileAsync metodu

Yeni bir vektör mağaza dosyasını asenkron olarak oluşturur.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vectorStoreId | String | Dosyanın oluşturulacağı vektör mağazasının ID'si. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | Dosyayı oluşturmak için detayları içeren istek nesnesi. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, dosya oluşturma yanıtını içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Vektör mağaza ID'si null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [VectorStoreFileResponse](../../vectorstorefileresponse/)
* sınıf [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)