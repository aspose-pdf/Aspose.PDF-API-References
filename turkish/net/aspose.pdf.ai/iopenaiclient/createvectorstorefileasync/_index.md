---
title: IOpenAIClient.CreateVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Yeni bir vektör mağaza dosyasını asenkron olarak oluşturur
type: docs
weight: 110
url: /tr/net/aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/
---
## IOpenAIClient.CreateVectorStoreFileAsync metodu

Yeni bir vektör mağaza dosyasını asenkron olarak oluşturur.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vectorStoreId | String | Dosyanın oluşturulacağı vektör mağazasının kimliği. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | Dosyayı oluşturmak için detayları içeren istek nesnesi. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, dosya oluşturma yanıtını içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Vektör mağaza kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [VectorStoreFileResponse](../../vectorstorefileresponse/)
* sınıf [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)