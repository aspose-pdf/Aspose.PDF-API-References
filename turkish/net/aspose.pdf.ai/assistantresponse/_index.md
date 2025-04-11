---
title: Class AssistantResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.AssistantResponse sınıfı. Modeli çağırabilen ve araçları kullanabilen bir asistanı temsil eder.
type: docs
weight: 140
url: /tr/net/aspose.pdf.ai/assistantresponse/
---
## AssistantResponse sınıfı

Modeli çağırabilen ve araçları kullanabilen bir asistanı temsil eder.

```csharp
public class AssistantResponse : BaseResponse
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [AssistantResponse](assistantresponse/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/assistantresponse/createdat/) { get; set; } | Asistanın oluşturulduğu Unix zaman damgasını (saniye cinsinden) alır veya ayarlar. |
| [Description](../../aspose.pdf.ai/assistantresponse/description/) { get; set; } | Asistanın açıklamasını alır veya ayarlar. Maksimum uzunluk 512 karakterdir. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Yanıt detayını alır veya ayarlar. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP yanıt hatasını alır veya ayarlar. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hata bilgilerini alır veya ayarlar. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP yanıt başlıklarını alır veya ayarlar. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP durum kodunu alır veya ayarlar. |
| [Id](../../aspose.pdf.ai/assistantresponse/id/) { get; set; } | API uç noktalarında referans alınabilecek tanımlayıcıyı alır veya ayarlar. |
| [Instructions](../../aspose.pdf.ai/assistantresponse/instructions/) { get; set; } | Asistanın kullandığı sistem talimatlarını alır veya ayarlar. Maksimum uzunluk 256.000 karakterdir. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Yanıtın başarılı olup olmadığını gösterir. |
| [Metadata](../../aspose.pdf.ai/assistantresponse/metadata/) { get; set; } | Bir nesneye eklenebilecek 16 anahtar-değer çiftinden oluşan bir küme alır veya ayarlar. Bu, nesne hakkında yapılandırılmış bir formatta ek bilgi saklamak için yararlı olabilir. Anahtarlar maksimum 64 karakter uzunluğunda ve değerler maksimum 512 karakter uzunluğunda olabilir. |
| [Model](../../aspose.pdf.ai/assistantresponse/model/) { get; set; } | Kullanılacak modelin kimliğini alır veya ayarlar. Tüm mevcut modellerinizi görmek için List models API'sini kullanabilir veya açıklamalar için Model genel bakışımıza göz atabilirsiniz. |
| [Name](../../aspose.pdf.ai/assistantresponse/name/) { get; set; } | Asistanın adını alır veya ayarlar. Maksimum uzunluk 256 karakterdir. |
| [Object](../../aspose.pdf.ai/assistantresponse/object/) { get; set; } | Her zaman asistan olan nesne türünü alır veya ayarlar. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hata neden ifadesini alır. |
| [ResponseFormat](../../aspose.pdf.ai/assistantresponse/responseformat/) { get; set; } | Modelin çıktısının formatını alır veya ayarlar. GPT-4o, GPT-4 Turbo ve gpt-3.5-turbo-1106'dan itibaren tüm GPT-3.5 Turbo modelleri ile uyumludur. { "type": "json_object" } olarak ayarlamak, modelin ürettiği mesajın geçerli JSON olmasını garanti eden JSON modunu etkinleştirir. Önemli: JSON modunu kullanırken, modelin kendinizin bir sistem veya kullanıcı mesajı aracılığıyla JSON üretmesini de talimatlandırmalısınız. Bunu yapmadan, model, token limitine ulaşana kadar sonsuz bir boşluk akışı üretebilir, bu da uzun süren ve görünüşte "takılmış" bir isteğe neden olur. Ayrıca, finish_reason="length" olduğunda mesaj içeriği kısmen kesilebilir; bu, üretimin max_tokens'ı aştığını veya konuşmanın maksimum bağlam uzunluğunu aştığını gösterir. |
| [Temperature](../../aspose.pdf.ai/assistantresponse/temperature/) { get; set; } | Kullanılacak örnekleme sıcaklığını alır veya ayarlar, 0 ile 2 arasında. 0.8 gibi daha yüksek değerler çıktıyı daha rastgele hale getirirken, 0.2 gibi daha düşük değerler daha odaklı ve belirleyici hale getirir. |
| [ToolResources](../../aspose.pdf.ai/assistantresponse/toolresources/) { get; set; } | Asistanın araçları tarafından kullanılan bir kaynak kümesini alır veya ayarlar. Kaynaklar, aracın türüne özgüdür. Örneğin, code_interpreter aracı bir dosya kimleri listesi gerektirirken, file_search aracı bir vektör deposu kimleri listesi gerektirir. |
| [Tools](../../aspose.pdf.ai/assistantresponse/tools/) { get; set; } | Asistanda etkinleştirilen araçların bir listesini alır veya ayarlar. Her asistan için maksimum 128 araç olabilir. Araçlar code_interpreter, file_search veya function türünde olabilir. |
| [TopP](../../aspose.pdf.ai/assistantresponse/topp/) { get; set; } | Sıcaklıkla örnekleme için bir alternatif alır veya ayarlar, nükleus örnekleme olarak adlandırılır; burada model, top_p olasılık kütlesine sahip tokenların sonuçlarını dikkate alır. Yani 0.1, yalnızca en üst %10 olasılık kütlesini oluşturan tokenların dikkate alındığı anlamına gelir. Genellikle bunu veya sıcaklığı değiştirmeyi öneriyoruz, ancak her ikisini birden değil. |

### Ayrıca Bakınız

* sınıf [BaseResponse](../baseresponse/)
* ad alanı [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../)