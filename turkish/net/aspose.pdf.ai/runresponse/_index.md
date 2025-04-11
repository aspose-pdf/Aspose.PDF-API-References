---
title: Class RunResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunResponse sınıfı. Bir iş parçacığında bir yürütme çalışmasını temsil eder
type: docs
weight: 1020
url: /tr/net/aspose.pdf.ai/runresponse/
---
## RunResponse sınıfı

Bir iş parçacığında bir yürütme çalışmasını temsil eder.

```csharp
public class RunResponse : BaseResponse, IStatus
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [RunResponse](runresponse/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | Bu çalışmanın yürütülmesi için kullanılan asistanın kimliğini alır veya ayarlar. |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | Çalışmanın iptal edildiği zamanı (saniye cinsinden) alır veya ayarlar. |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | Çalışmanın tamamlandığı zamanı (saniye cinsinden) alır veya ayarlar. |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | Çalışmanın oluşturulduğu zamanı (saniye cinsinden) alır veya ayarlar. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Yanıt detayını alır veya ayarlar. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP yanıt hatasını alır veya ayarlar. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hata bilgilerini alır veya ayarlar. |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | Çalışmanın sona ereceği zamanı (saniye cinsinden) alır veya ayarlar. |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | Çalışmanın başarısız olduğu zamanı (saniye cinsinden) alır veya ayarlar. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP yanıt başlıklarını alır veya ayarlar. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP durum kodunu alır veya ayarlar. |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | API uç noktalarında referans alınabilecek tanımlayıcıyı alır veya ayarlar. |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | Çalışmanın neden tamamlanmadığına dair detayları alır veya ayarlar. Çalışma tamamlanmamışsa null olur. |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | Bu çalışma için asistanın kullandığı talimatları alır veya ayarlar. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Yanıtın başarılı olup olmadığını gösterir. |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | Bu çalışmayla ilişkili son hatayı alır veya ayarlar. Hata yoksa null olur. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | Çalışma süresince kullanıldığı belirtilen maksimum tamamlama token sayısını alır veya ayarlar. |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | Çalışma süresince kullanıldığı belirtilen maksimum istem token sayısını alır veya ayarlar. |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | Bir nesneye eklenebilecek 16 anahtar-değer çiftinden oluşan bir küme alır veya ayarlar. Bu, nesne hakkında yapılandırılmış bir formatta ek bilgi depolamak için yararlı olabilir. Anahtarlar en fazla 64 karakter uzunluğunda ve değerler en fazla 512 karakter uzunluğunda olabilir. |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | Bu çalışma için asistanın kullandığı modeli alır veya ayarlar. |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | Her zaman thread.run olan nesne türünü alır veya ayarlar. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hata neden ifadesini alır. |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | Çalışmaya devam etmek için gereken eyleme dair detayları alır veya ayarlar. Eylem gerekmiyorsa null olur. |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | Modelin çıktısının formatını alır veya ayarlar. GPT-4o, GPT-4 Turbo ve gpt-3.5-turbo-1106'dan itibaren tüm GPT-3.5 Turbo modelleriyle uyumludur. { "type": "json_object" } olarak ayarlamak, modelin ürettiği mesajın geçerli bir JSON olmasını garanti eden JSON modunu etkinleştirir. Önemli: JSON modunu kullanırken, modelin kendinizin de bir sistem veya kullanıcı mesajı aracılığıyla JSON üretmesini sağlamalısınız. Bunu yapmadan, model token limitine ulaşana kadar sonsuz bir boşluk akışı üretebilir, bu da uzun süren ve görünüşte "takılmış" bir isteğe neden olur. Ayrıca, finish_reason="length" olduğunda mesaj içeriği kısmen kesilebilir; bu, üretimin max_tokens'ı aştığını veya konuşmanın max context uzunluğunu aştığını gösterir. |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | Çalışmanın başlatıldığı zamanı (saniye cinsinden) alır veya ayarlar. |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | Çalışmanın durumunu alır veya ayarlar; bu durum queued, in_progress, requires_action, cancelling, cancelled, failed, completed, incomplete veya expired olabilir. |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | Bu çalışma için kullanılan örnekleme sıcaklığını alır veya ayarlar. Ayarlanmazsa varsayılan değeri 1'dir. |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | Bu çalışmanın bir parçası olarak yürütülen iş parçacığının kimliğini alır veya ayarlar. |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | Model tarafından çağrılan aracı (varsa) alır veya ayarlar. none, modelin herhangi bir aracı çağırmayacağı ve bunun yerine bir mesaj üreteceği anlamına gelir. auto varsayılan değerdir ve modelin bir mesaj üretmek veya bir veya daha fazla aracı çağırmak arasında seçim yapabileceği anlamına gelir. required, modelin kullanıcıya yanıt vermeden önce bir veya daha fazla aracı çağırması gerektiği anlamına gelir. {"type": "file_search"} veya {"type": "function", "function": {"name": "my_function"}} gibi belirli bir aracı belirtmek, modelin o aracı çağırmasını zorlar. |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | Bu çalışma için asistanın kullandığı araçların listesini alır veya ayarlar. |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | Bu çalışma için kullanılan çekirdek örnekleme değerini alır veya ayarlar. Ayarlanmazsa varsayılan değeri 1'dir. |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | Bir iş parçacığının çalışmadan önce nasıl kesileceğini kontrol eden kesme stratejisini alır veya ayarlar. Bunu, çalışmanın başlangıç bağlam penceresini kontrol etmek için kullanın. |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | Çalışma ile ilgili kullanım istatistiklerini alır veya ayarlar. Bu değer, çalışma terminal bir durumda değilse (yani in_progress, queued, vb.) null olur. |

### Ayrıca Bakınız

* sınıf [BaseResponse](../baseresponse/)
* arayüz [IStatus](../istatus/)
* ad alanı [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../)