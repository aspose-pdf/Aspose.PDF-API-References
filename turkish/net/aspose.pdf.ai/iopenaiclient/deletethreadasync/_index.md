---
title: IOpenAIClient.DeleteThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Mevcut bir ipliği asenkron olarak siler
type: docs
weight: 150
url: /tr/net/aspose.pdf.ai/iopenaiclient/deletethreadasync/
---
## IOpenAIClient.DeleteThreadAsync metodu

Mevcut bir ipliği asenkron olarak siler.

```csharp
public Task<DeleteStatusResponse> DeleteThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadId | String | Silinecek ipliğin kimliği. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, silme işleminin durumunu içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thread Id null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [DeleteStatusResponse](../../deletestatusresponse/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)