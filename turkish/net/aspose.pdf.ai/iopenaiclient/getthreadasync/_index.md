---
title: IOpenAIClient.GetThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Belirli bir ipliğin ayrıntılarını asenkron olarak alır
type: docs
weight: 270
url: /tr/net/aspose.pdf.ai/iopenaiclient/getthreadasync/
---
## IOpenAIClient.GetThreadAsync metodu

Belirli bir ipliğin ayrıntılarını asenkron olarak alır.

```csharp
public Task<ThreadResponse> GetThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadId | String | Alınacak ipliğin kimliği. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir jeton. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, ipliğin ayrıntılarını içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | İpliğin kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [ThreadResponse](../../threadresponse/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)