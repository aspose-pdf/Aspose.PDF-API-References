---
title: OpenAIClient.WaitForVectorStoreFileToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Belirli bir vektör depolama dosyasının asenkron olarak tamamlanmasını bekler
type: docs
weight: 490
url: /tr/net/aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/
---
## OpenAIClient.WaitForVectorStoreFileToCompleteAsync metodu

Belirli bir vektör depolama dosyasının asenkron olarak tamamlanmasını bekler.

```csharp
public Task<VectorStoreFileResponse> WaitForVectorStoreFileToCompleteAsync(string vectorStoreId, 
    string fileId, CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vectorStoreId | String | Dosyayı içeren vektör deposunun kimliği. |
| fileId | String | Tamamlanana kadar izlenecek dosyanın kimliği. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, dosyanın son durumunu içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Vektör deposu kimliği null veya boş olduğunda fırlatılır. |
| [AIClientException](../../aiclientexception/) | Dosya kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [VectorStoreFileResponse](../../vectorstorefileresponse/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)