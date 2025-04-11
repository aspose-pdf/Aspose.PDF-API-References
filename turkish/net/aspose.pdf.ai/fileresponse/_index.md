---
title: Class FileResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.FileResponse sınıfı. FileResponse nesnesi, OpenAI'ye yüklenmiş bir belgeyi temsil eder.
type: docs
weight: 400
url: /tr/net/aspose.pdf.ai/fileresponse/
---
## FileResponse sınıfı

FileResponse nesnesi, OpenAI'ye yüklenmiş bir belgeyi temsil eder.

```csharp
public class FileResponse : BaseResponse, IEntityId
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [FileResponse](fileresponse/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Bytes](../../aspose.pdf.ai/fileresponse/bytes/) { get; set; } | Dosyanın boyutunu, bayt cinsinden alır veya ayarlar. |
| [CreatedAt](../../aspose.pdf.ai/fileresponse/createdat/) { get; set; } | Dosyanın oluşturulduğu Unix zaman damgasını (saniye cinsinden) alır veya ayarlar. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Yanıt detayını alır veya ayarlar. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP yanıt hatasını alır veya ayarlar. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hata bilgisini alır veya ayarlar. |
| [Filename](../../aspose.pdf.ai/fileresponse/filename/) { get; set; } | Dosyanın adını alır veya ayarlar. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP yanıt başlıklarını alır veya ayarlar. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP durum kodunu alır veya ayarlar. |
| [Id](../../aspose.pdf.ai/fileresponse/id/) { get; set; } | API uç noktalarında referans alınabilecek dosya tanımlayıcısını alır veya ayarlar. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Yanıtın başarılı olup olmadığını gösterir. |
| [Object](../../aspose.pdf.ai/fileresponse/object/) { get; set; } | Her zaman dosya olan nesne türünü alır veya ayarlar. |
| [Purpose](../../aspose.pdf.ai/fileresponse/purpose/) { get; set; } | Dosyanın amaçlanan amacını alır veya ayarlar. Desteklenen değerler assistants, assistants_output, batch, batch_output, fine-tune, fine-tune-results ve vision'dır. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hata neden ifadesini alır. |

### Ayrıca Bakınız

* sınıf [BaseResponse](../baseresponse/)
* arayüz [IEntityId](../ientityid/)
* ad alanı [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../)