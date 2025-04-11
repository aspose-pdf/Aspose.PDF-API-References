---
title: OpenAIClient.GetFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Belirtilen amaca dayalı olarak dosyaların listesini asenkron olarak alır
type: docs
weight: 230
url: /tr/net/aspose.pdf.ai/openaiclient/getfilesasync/
---
## OpenAIClient.GetFilesAsync metodu

Belirtilen amaca dayalı olarak dosyaların listesini asenkron olarak alır.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| purpose | String | Opsiyonel. Alınacak dosyaların amacı. Null ise, tüm amaçlar için dosyalar alınır. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, dosyaların bir listesini içerir.

### Ayrıca Bakınız

* class [FileListResponse](../../filelistresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)