---
title: Class ThreadMessageResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadMessageResponse sınıfı. Bir iplik içindeki mesajı temsil eder
type: docs
weight: 1160
url: /tr/net/aspose.pdf.ai/threadmessageresponse/
---
## ThreadMessageResponse sınıfı

Bir iplik içindeki mesajı temsil eder.

```csharp
public class ThreadMessageResponse : BaseResponse, IStatus
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [ThreadMessageResponse](threadmessageresponse/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/threadmessageresponse/assistantid/) { get; set; } | Bu mesajı yazan asistanın kimliğini alır veya ayarlar, varsa. |
| [Attachments](../../aspose.pdf.ai/threadmessageresponse/attachments/) { get; set; } | Mesaja eklenmiş dosyaların listesini alır veya ayarlar. |
| [CompletedAt](../../aspose.pdf.ai/threadmessageresponse/completedat/) { get; set; } | Mesajın tamamlandığı Unix zaman damgasını (saniye cinsinden) alır veya ayarlar. |
| [Content](../../aspose.pdf.ai/threadmessageresponse/content/) { get; set; } | Mesajın içeriğini bir metin ve/veya resim dizisi olarak alır veya ayarlar. |
| [CreatedAt](../../aspose.pdf.ai/threadmessageresponse/createdat/) { get; set; } | Mesajın oluşturulduğu Unix zaman damgasını (saniye cinsinden) alır veya ayarlar. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Yanıt detayını alır veya ayarlar. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP yanıt hatasını alır veya ayarlar. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hata bilgilerini alır veya ayarlar. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP yanıt başlıklarını alır veya ayarlar. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP durum kodunu alır veya ayarlar. |
| [Id](../../aspose.pdf.ai/threadmessageresponse/id/) { get; set; } | API uç noktalarında referans alınabilecek tanımlayıcıyı alır veya ayarlar. |
| [IncompleteAt](../../aspose.pdf.ai/threadmessageresponse/incompleteat/) { get; set; } | Mesajın eksik olarak işaretlendiği Unix zaman damgasını (saniye cinsinden) alır veya ayarlar. |
| [IncompleteDetails](../../aspose.pdf.ai/threadmessageresponse/incompletedetails/) { get; set; } | Eksik bir mesajı alır veya ayarlar, mesajın neden eksik olduğuna dair detayları içerir. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Yanıtın başarılı olup olmadığını gösterir. |
| [Metadata](../../aspose.pdf.ai/threadmessageresponse/metadata/) { get; set; } | Bir nesneye eklenebilecek 16 anahtar-değer çiftinden oluşan bir küme alır veya ayarlar. Bu, nesne hakkında yapılandırılmış bir formatta ek bilgi saklamak için yararlı olabilir. Anahtarlar en fazla 64 karakter uzunluğunda ve değerler en fazla 512 karakter uzunluğunda olabilir. |
| [Object](../../aspose.pdf.ai/threadmessageresponse/object/) { get; set; } | Nesne türünü alır veya ayarlar, bu her zaman "thread.message"dır. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hata neden ifadesini alır. |
| [Role](../../aspose.pdf.ai/threadmessageresponse/role/) { get; set; } | Mesajı üreten varlığı alır veya ayarlar. "user" veya "assistant"dan biri. |
| [RunId](../../aspose.pdf.ai/threadmessageresponse/runid/) { get; set; } | Bu mesajın oluşturulmasıyla ilişkili çalışmanın kimliğini alır veya ayarlar. Değer, mesajlar manuel olarak oluşturulduğunda null'dır. |
| [Status](../../aspose.pdf.ai/threadmessageresponse/status/) { get; set; } | Mesajın durumunu alır veya ayarlar. "queued", "in_progress", "requires_action" veya "completed"dan biri. |
| [ThreadId](../../aspose.pdf.ai/threadmessageresponse/threadid/) { get; set; } | Bu mesajın ait olduğu ipliğin kimliğini alır veya ayarlar. |

### Ayrıca Bakınız

* sınıf [BaseResponse](../baseresponse/)
* arayüz [IStatus](../istatus/)
* ad alanı [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../)