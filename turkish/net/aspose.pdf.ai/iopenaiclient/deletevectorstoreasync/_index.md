---
title: IOpenAIClient.DeleteVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Bir vektör deposunu asenkron olarak siler
type: docs
weight: 170
url: /tr/net/aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/
---
## IOpenAIClient.DeleteVectorStoreAsync metodu

Bir vektör deposunu asenkron olarak siler.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vectorStoreId | String | Silinecek vektör deposunun kimliği. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, silme işleminin durumunu içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Vektör deposu kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [DeleteStatusResponse](../../deletestatusresponse/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)