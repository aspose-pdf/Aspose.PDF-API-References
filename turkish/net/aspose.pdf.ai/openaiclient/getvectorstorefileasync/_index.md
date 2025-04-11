---
title: OpenAIClient.GetVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient yöntemi. Bir vektör deposundaki belirli bir dosyanın ayrıntılarını asenkron olarak alır
type: docs
weight: 340
url: /tr/net/aspose.pdf.ai/openaiclient/getvectorstorefileasync/
---
## OpenAIClient.GetVectorStoreFileAsync yöntemi

Bir vektör deposundaki belirli bir dosyanın ayrıntılarını asenkron olarak alır.

```csharp
public Task<VectorStoreFileResponse> GetVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vectorStoreId | String | Dosyayı içeren vektör deposunun ID'si. |
| fileId | String | Alınacak dosyanın ID'si. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, dosyanın ayrıntılarını içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Vektör deposu ID'si null veya boş olduğunda fırlatılır. |
| [AIClientException](../../aiclientexception/) | Dosya ID'si null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [VectorStoreFileResponse](../../vectorstorefileresponse/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)