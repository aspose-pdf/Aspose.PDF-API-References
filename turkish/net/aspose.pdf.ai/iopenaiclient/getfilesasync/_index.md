---
title: IOpenAIClient.GetFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Belirtilen amaca dayalı olarak dosyaların listesini asenkron olarak alır
type: docs
weight: 220
url: /tr/net/aspose.pdf.ai/iopenaiclient/getfilesasync/
---
## IOpenAIClient.GetFilesAsync metodu

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

* sınıf [FileListResponse](../../filelistresponse/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)