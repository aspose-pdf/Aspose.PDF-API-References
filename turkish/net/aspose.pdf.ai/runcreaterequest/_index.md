---
title: Class RunCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunCreateRequest sınıfı. Bir çalıştırma oluşturma isteğini temsil eder
type: docs
weight: 980
url: /tr/net/aspose.pdf.ai/runcreaterequest/
---
## RunCreateRequest sınıfı

Bir çalıştırma oluşturma isteğini temsil eder.

```csharp
public class RunCreateRequest
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [RunCreateRequest](runcreaterequest/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [AdditionalInstructions](../../aspose.pdf.ai/runcreaterequest/additionalinstructions/) { get; set; } | Ekstra talimatları alır veya ayarlar. Çalıştırma için talimatların sonuna ek talimatlar ekler. Bu, diğer talimatları geçersiz kılmadan çalıştırma başına davranışı değiştirmek için yararlıdır. |
| [AdditionalMessages](../../aspose.pdf.ai/runcreaterequest/additionalmessages/) { get; set; } | Çalıştırma oluşturmadan önce iş parçacığına ek mesajları alır veya ayarlar. |
| [AssistantId](../../aspose.pdf.ai/runcreaterequest/assistantid/) { get; set; } | Bu çalıştırmayı yürütmek için kullanılacak asistanın kimliğini alır veya ayarlar. |
| [Instructions](../../aspose.pdf.ai/runcreaterequest/instructions/) { get; set; } | Asistanın talimatlarını geçersiz kılan talimatları alır veya ayarlar. Bu, çalıştırma başına davranışı değiştirmek için yararlıdır. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runcreaterequest/maxcompletiontokens/) { get; set; } | Çalıştırma süresince kullanılabilecek maksimum tamamlama jetonlarının sayısını alır veya ayarlar. Çalıştırma, birden fazla tur boyunca yalnızca belirtilen tamamlama jetonları sayısını kullanmak için en iyi çabayı gösterecektir. Çalıştırma, belirtilen tamamlama jetonları sayısını aşarsa, durum tamamlanmamış olarak sona erecektir. Daha fazla bilgi için incomplete_details'e bakın. |
| [MaxPromptTokens](../../aspose.pdf.ai/runcreaterequest/maxprompttokens/) { get; set; } | Çalıştırma süresince kullanılabilecek maksimum istem jetonlarının sayısını alır veya ayarlar. Çalıştırma, birden fazla tur boyunca yalnızca belirtilen istem jetonları sayısını kullanmak için en iyi çabayı gösterecektir. Çalıştırma, belirtilen istem jetonları sayısını aşarsa, durum tamamlanmamış olarak sona erecektir. Daha fazla bilgi için incomplete_details'e bakın. |
| [Metadata](../../aspose.pdf.ai/runcreaterequest/metadata/) { get; set; } | Bir nesneye eklenebilecek 16 anahtar-değer çiftinden oluşan bir küme alır veya ayarlar. Bu, nesne hakkında yapılandırılmış bir formatta ek bilgi depolamak için yararlı olabilir. Anahtarlar en fazla 64 karakter uzunluğunda ve değerler en fazla 512 karakter uzunluğunda olabilir. |
| [Model](../../aspose.pdf.ai/runcreaterequest/model/) { get; set; } | Bu çalıştırmayı yürütmek için kullanılacak modelin kimliğini alır veya ayarlar. Burada bir değer sağlanırsa, bu asistanla ilişkili modeli geçersiz kılacaktır. Aksi takdirde, asistanla ilişkili model kullanılacaktır. |
| [ResponseFormat](../../aspose.pdf.ai/runcreaterequest/responseformat/) { get; set; } | Yanıt formatını alır veya ayarlar. Modelin çıktısının hangi formatta olması gerektiğini belirtir. GPT-4o, GPT-4 Turbo ve gpt-3.5-turbo-1106'dan itibaren tüm GPT-3.5 Turbo modelleri ile uyumludur. { "type": "json_object" } olarak ayarlamak, modelin ürettiği mesajın geçerli JSON olmasını garanti eden JSON modunu etkinleştirir. Önemli: JSON modunu kullanırken, modelin kendisinin bir sistem veya kullanıcı mesajı aracılığıyla JSON üretmesini de talimatlandırmalısınız. Bunu yapmadan, model, token limitine ulaşana kadar bitmeyen bir boşluk akışı üretebilir, bu da uzun süren ve görünüşte "takılmış" bir isteğe neden olur. Ayrıca, finish_reason="length" olduğunda mesaj içeriği kısmen kesilebilir; bu, üretimin max_tokens'ı aştığını veya konuşmanın maksimum bağlam uzunluğunu aştığını gösterir. |
| [Stream](../../aspose.pdf.ai/runcreaterequest/stream/) { get; set; } | Akışın kullanılıp kullanılmayacağını alır veya ayarlar. Eğer doğruysa, Çalıştırma sırasında meydana gelen olayların bir akışını sunucu tarafından gönderilen olaylar olarak döndürür ve Çalıştırma, bir data: [DONE] mesajı ile terminal bir duruma girdiğinde sona erer. |
| [Temperature](../../aspose.pdf.ai/runcreaterequest/temperature/) { get; set; } | Kullanılacak örnekleme sıcaklığını alır veya ayarlar, 0 ile 2 arasında. 0.8 gibi daha yüksek değerler çıktıyı daha rastgele hale getirirken, 0.2 gibi daha düşük değerler daha odaklı ve belirleyici hale getirir. |
| [ToolChoice](../../aspose.pdf.ai/runcreaterequest/toolchoice/) { get; set; } | Model tarafından çağrılan hangi (varsa) aracın alındığını alır veya ayarlar. none, modelin herhangi bir aracı çağırmayacağı ve bunun yerine bir mesaj üreteceği anlamına gelir. auto varsayılan değerdir ve modelin bir mesaj üretmek veya bir veya daha fazla aracı çağırmak arasında seçim yapabileceği anlamına gelir. required, modelin kullanıcıya yanıt vermeden önce bir veya daha fazla aracı çağırması gerektiği anlamına gelir. {"type": "file_search"} veya {"type": "function", "function": {"name": "my_function"}} gibi belirli bir aracı belirtmek, modelin o aracı çağırmasını zorlar. |
| [Tools](../../aspose.pdf.ai/runcreaterequest/tools/) { get; set; } | Bu çalıştırma için asistanın kullanabileceği araçları geçersiz kılan araçları alır veya ayarlar. Bu, çalıştırma başına davranışı değiştirmek için yararlıdır. |
| [TopP](../../aspose.pdf.ai/runcreaterequest/topp/) { get; set; } | Sıcaklık ile örnekleme için bir alternatif alır veya ayarlar, nükleus örnekleme olarak adlandırılır; burada model, en yüksek p olasılık kütlesine sahip jetonların sonuçlarını dikkate alır. Yani 0.1, yalnızca en yüksek %10 olasılık kütlesini oluşturan jetonların dikkate alındığı anlamına gelir. Genellikle bunu veya sıcaklığı değiştirmeyi öneriyoruz, ancak her ikisini birden değil. |
| [TruncationStrategy](../../aspose.pdf.ai/runcreaterequest/truncationstrategy/) { get; set; } | Kısaltma stratejisini alır veya ayarlar. Bir iş parçacığının çalıştırmadan önce nasıl kısaltılacağını kontrol eder. Bunu, çalıştırmanın başlangıç bağlam penceresini kontrol etmek için kullanın. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)