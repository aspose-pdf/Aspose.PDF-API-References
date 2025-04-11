---
title: OpenAIClient.DeleteVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Bir vektör deposundaki dosyayı asenkron olarak siler
type: docs
weight: 180
url: /tr/net/aspose.pdf.ai/openaiclient/deletevectorstorefileasync/
---
## OpenAIClient.DeleteVectorStoreFileAsync metodu

Bir vektör deposundaki dosyayı asenkron olarak siler.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vectorStoreId | String | Silinecek dosyayı içeren vektör deposunun ID'si. |
| fileId | String | Silinecek dosyanın ID'si. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, silme işleminin durumunu içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Vektör deposu ID'si null veya boş olduğunda fırlatılır. |
| [AIClientException](../../aiclientexception/) | Dosya ID'si null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [DeleteStatusResponse](../../deletestatusresponse/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)