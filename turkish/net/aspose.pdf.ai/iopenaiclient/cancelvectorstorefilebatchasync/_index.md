---
title: IOpenAIClient.CancelVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Belirli bir vektör depolama dosya grubunu asenkron olarak iptal eder
type: docs
weight: 20
url: /tr/net/aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/
---
## IOpenAIClient.CancelVectorStoreFileBatchAsync metodu

Belirli bir vektör depolama dosya grubunu asenkron olarak iptal eder.

```csharp
public Task<VectorStoreFileBatchResponse> CancelVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vectorStoreId | String | İptal edilecek dosya grubunu içeren vektör deposunun kimliği. |
| fileBatchId | String | İptal edilecek dosya grubunun kimliği. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, dosya grubunun iptal edilmesinden gelen yanıtı içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Vektör deposu kimliği null veya boş olduğunda fırlatılır. |
| [AIClientException](../../aiclientexception/) | Vektör depolama dosya grubu kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)