---
title: Class RunStepResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunStepResponse sınıfı. Bir çalışmanın yürütülmesinde bir adımı temsil eder.
type: docs
weight: 1060
url: /tr/net/aspose.pdf.ai/runstepresponse/
---
## RunStepResponse sınıfı

Bir çalışmanın yürütülmesinde bir adımı temsil eder.

```csharp
public class RunStepResponse : BaseResponse
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [RunStepResponse](runstepresponse/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | Çalışma adımı ile ilişkili asistanın kimliğini alır veya ayarlar. |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | Çalışma adımının iptal edildiği Unix zaman damgasını (saniye cinsinden) alır veya ayarlar. |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | Çalışma adımının tamamlandığı Unix zaman damgasını (saniye cinsinden) alır veya ayarlar. |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | Çalışma adımının oluşturulduğu Unix zaman damgasını (saniye cinsinden) alır veya ayarlar. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Yanıt detayını alır veya ayarlar. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP yanıt hatasını alır veya ayarlar. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hata bilgilerini alır veya ayarlar. |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | Çalışma adımının süresinin dolduğu Unix zaman damgasını (saniye cinsinden) alır veya ayarlar. Bir adım, ana çalışmanın süresi dolmuşsa süresi dolmuş olarak kabul edilir. |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | Çalışma adımının başarısız olduğu Unix zaman damgasını (saniye cinsinden) alır veya ayarlar. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP yanıt başlıklarını alır veya ayarlar. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP durum kodunu alır veya ayarlar. |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | API uç noktalarında referans alınabilecek çalışma adımının tanımlayıcısını alır veya ayarlar. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Yanıtın başarılı olup olmadığını gösterir. |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | Bu çalışma adımı ile ilişkili son hatayı alır veya ayarlar. Hata yoksa null olacaktır. |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | Bir nesneye eklenebilecek 16 anahtar-değer çiftinden oluşan bir küme alır veya ayarlar. Bu, nesne hakkında yapılandırılmış bir formatta ek bilgi saklamak için yararlı olabilir. Anahtarlar en fazla 64 karakter uzunluğunda ve değerler en fazla 512 karakter uzunluğunda olabilir. |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | Her zaman thread.run.step olan nesne türünü alır veya ayarlar. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hata nedenini ifade eden ifadeyi alır. |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | Bu çalışma adımının parçası olduğu çalışmanın kimliğini alır veya ayarlar. |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | Çalışma adımının türünü alır veya ayarlar; bu ya message_creation ya da tool_calls olabilir. |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | Çalışma adımının durumunu alır veya ayarlar; bu ya in_progress, cancelled, failed, completed veya expired olabilir. |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | Çalışma adımının detaylarını alır veya ayarlar. |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | Çalışmanın yürütüldüğü iş parçacığının kimliğini alır veya ayarlar. |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | Çalışma adımı ile ilgili kullanım istatistiklerini alır veya ayarlar. Bu değer, çalışma adımının durumu in_progress iken null olacaktır. |

### Ayrıca Bakınız

* sınıf [BaseResponse](../baseresponse/)
* ad alanı [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../)