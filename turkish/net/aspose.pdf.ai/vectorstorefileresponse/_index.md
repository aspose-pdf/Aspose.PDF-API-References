---
title: Class VectorStoreFileResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreFileResponse sınıfı. Bir vektör mağaza dosyası yanıtı
type: docs
weight: 1350
url: /tr/net/aspose.pdf.ai/vectorstorefileresponse/
---
## VectorStoreFileResponse sınıfı

Bir vektör mağaza dosyası yanıtı.

```csharp
public class VectorStoreFileResponse : BaseResponse, IStatus
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [VectorStoreFileResponse](vectorstorefileresponse/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstorefileresponse/createdat/) { get; set; } | Vektör mağaza dosyasının oluşturulduğu Unix zaman damgasını (saniye cinsinden) alır veya ayarlar. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Yanıt detayını alır veya ayarlar. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP yanıt hatasını alır veya ayarlar. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hata bilgilerini alır veya ayarlar. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP yanıt başlıklarını alır veya ayarlar. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP durum kodunu alır veya ayarlar. |
| [Id](../../aspose.pdf.ai/vectorstorefileresponse/id/) { get; set; } | API uç noktalarında referans alınabilecek tanımlayıcıyı alır veya ayarlar. /// |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Yanıtın başarılı olup olmadığını gösterir. |
| [LastError](../../aspose.pdf.ai/vectorstorefileresponse/lasterror/) { get; set; } | Bu vektör mağaza dosyasıyla ilişkili son hatayı alır veya ayarlar. Hata yoksa null olacaktır. |
| [Object](../../aspose.pdf.ai/vectorstorefileresponse/object/) { get; set; } | Her zaman vector_store.file olan nesne türünü alır veya ayarlar. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hata nedenini alır. |
| [Status](../../aspose.pdf.ai/vectorstorefileresponse/status/) { get; set; } | Vektör mağaza dosyasının durumunu alır veya ayarlar; bu durum in_progress, completed, cancelled veya failed olabilir. Tamamlanmış durumu, vektör mağaza dosyasının kullanıma hazır olduğunu gösterir. |
| [UsageBytes](../../aspose.pdf.ai/vectorstorefileresponse/usagebytes/) { get; set; } | Bayt cinsinden toplam vektör mağaza kullanımını alır veya ayarlar. Bunun orijinal dosya boyutundan farklı olabileceğini unutmayın. |
| [VectorStoreId](../../aspose.pdf.ai/vectorstorefileresponse/vectorstoreid/) { get; set; } | Dosyanın bağlı olduğu vektör mağazasının kimliğini alır veya ayarlar. |

### Ayrıca Bakınız

* sınıf [BaseResponse](../baseresponse/)
* arayüz [IStatus](../istatus/)
* ad alanı [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../)