---
title: OpenAIClient.GetFileAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Belirli bir dosyanın ayrıntılarını asenkron olarak alır
type: docs
weight: 220
url: /tr/net/aspose.pdf.ai/openaiclient/getfileasync/
---
## OpenAIClient.GetFileAsync metodu

Belirli bir dosyanın ayrıntılarını asenkron olarak alır.

```csharp
public Task<FileResponse> GetFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileId | String | Alınacak dosyanın ID'si. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu dosyanın ayrıntılarını içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dosya ID'si null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [FileResponse](../../fileresponse/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)