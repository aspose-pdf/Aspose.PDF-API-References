---
title: Class CompletionResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CompletionResponse sınıfı. Sağlanan girdi temelinde model tarafından döndürülen bir sohbet tamamlama yanıtını temsil eder.
type: docs
weight: 240
url: /tr/net/aspose.pdf.ai/completionresponse/
---
## CompletionResponse sınıfı

Sağlanan girdi temelinde model tarafından döndürülen bir sohbet tamamlama yanıtını temsil eder.

```csharp
public class CompletionResponse : BaseResponse
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [CompletionResponse](completionresponse/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Choices](../../aspose.pdf.ai/completionresponse/choices/) { get; set; } | Sohbet tamamlama seçeneklerinin bir listesini alır veya ayarlar. n 1'den büyükse birden fazla olabilir. |
| [Created](../../aspose.pdf.ai/completionresponse/created/) { get; set; } | Sohbet tamamlama oluşturulduğunda Unix zaman damgasını (saniye cinsinden) alır veya ayarlar. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Yanıt detayını alır veya ayarlar. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP yanıt hatasını alır veya ayarlar. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hata bilgilerini alır veya ayarlar. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP yanıt başlıklarını alır veya ayarlar. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP durum kodunu alır veya ayarlar. |
| [Id](../../aspose.pdf.ai/completionresponse/id/) { get; set; } | Sohbet tamamlama için benzersiz bir tanımlayıcı alır veya ayarlar. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Yanıtın başarılı olup olmadığını gösterir. |
| [Model](../../aspose.pdf.ai/completionresponse/model/) { get; set; } | Sohbet tamamlama için kullanılan modeli alır veya ayarlar. |
| [Object](../../aspose.pdf.ai/completionresponse/object/) { get; set; } | Her zaman chat.completion olan nesne türünü alır veya ayarlar. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hata neden ifadesini alır. |
| [SystemFingerprint](../../aspose.pdf.ai/completionresponse/systemfingerprint/) { get; set; } | Modelin çalıştığı arka uç yapılandırmasını temsil eden parmak izini alır veya ayarlar. Determinizmi etkileyebilecek arka uç değişikliklerinin ne zaman yapıldığını anlamak için tohum istek parametresi ile birlikte kullanılabilir. |
| [Usage](../../aspose.pdf.ai/completionresponse/usage/) { get; set; } | Tamamlama isteği için kullanım istatistiklerini alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/completionresponse/tostring/)() | İlk seçeneğin içeriğini bir dize olarak döndürür. |

### Ayrıca Bakınız

* sınıf [BaseResponse](../baseresponse/)
* ad alanı [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../)