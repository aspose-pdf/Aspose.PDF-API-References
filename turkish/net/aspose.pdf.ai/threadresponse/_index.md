---
title: Class ThreadResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadResponse sınıfı. Mesajları içeren bir ipliği temsil eder
type: docs
weight: 1180
url: /tr/net/aspose.pdf.ai/threadresponse/
---
## ThreadResponse sınıfı

Mesajları içeren bir ipliği temsil eder.

```csharp
public class ThreadResponse : BaseResponse
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [ThreadResponse](threadresponse/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/threadresponse/createdat/) { get; set; } | İpliğin oluşturulduğu Unix zaman damgasını (saniye cinsinden) alır veya ayarlar. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Yanıt detayını alır veya ayarlar. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP yanıt hatasını alır veya ayarlar. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hata bilgilerini alır veya ayarlar. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP yanıt başlıklarını alır veya ayarlar. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP durum kodunu alır veya ayarlar. |
| [Id](../../aspose.pdf.ai/threadresponse/id/) { get; set; } | API uç noktalarında referans alınabilecek tanımlayıcıyı alır veya ayarlar. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Yanıtın başarılı olup olmadığını gösterir. |
| [Metadata](../../aspose.pdf.ai/threadresponse/metadata/) { get; set; } | Bir nesneye eklenebilecek 16 anahtar-değer çiftinden oluşan bir küme alır veya ayarlar. Bu, nesne hakkında yapılandırılmış bir formatta ek bilgi depolamak için yararlı olabilir. Anahtarlar en fazla 64 karakter uzunluğunda ve değerler en fazla 512 karakter uzunluğunda olabilir. |
| [Object](../../aspose.pdf.ai/threadresponse/object/) { get; set; } | Her zaman iplik olan nesne türünü alır veya ayarlar. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hata neden ifadesini alır. |
| [ToolResources](../../aspose.pdf.ai/threadresponse/toolresources/) { get; set; } | Bu iplikte asistanın araçlarına sunulan bir kaynak kümesini alır veya ayarlar. Kaynaklar, aracın türüne özgüdür. Örneğin, code_interpreter aracı bir dosya kimlikleri listesine ihtiyaç duyarken, file_search aracı bir vektör deposu kimlikleri listesine ihtiyaç duyar. |

### Ayrıca Bakınız

* sınıf [BaseResponse](../baseresponse/)
* ad alanı [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../)