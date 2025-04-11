---
title: IOpenAIClient.UploadFileAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Bir dosyayı OpenAI sunucusuna asenkron olarak yükler
type: docs
weight: 420
url: /tr/net/aspose.pdf.ai/iopenaiclient/uploadfileasync/
---
## IOpenAIClient.UploadFileAsync metodu

Bir dosyayı OpenAI sunucusuna asenkron olarak yükler.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| purpose | String | Dosya yüklemenin amacı, genellikle dosyanın nasıl kullanılacağını açıklar. |
| fileName | String | Yüklenecek dosyanın adı. |
| fileBytes | Byte[] | Dosya verilerini içeren byte dizisi. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, dosya yüklemeden gelen yanıtı içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dosya amacı null veya boş olduğunda fırlatılır. |
| [AIClientException](../../aiclientexception/) | Dosya adı null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [FileResponse](../../fileresponse/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)