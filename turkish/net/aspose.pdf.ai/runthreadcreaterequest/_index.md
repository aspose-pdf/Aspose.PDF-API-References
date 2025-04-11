---
title: Class RunThreadCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunThreadCreateRequest sınıfı. Bir iş parçacığı oluşturma ve bunu tek bir istekte çalıştırma talebini temsil eder.
type: docs
weight: 1070
url: /tr/net/aspose.pdf.ai/runthreadcreaterequest/
---
## RunThreadCreateRequest sınıfı

Bir iş parçacığı oluşturma ve bunu tek bir istekte çalıştırma talebini temsil eder.

```csharp
public class RunThreadCreateRequest
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [RunThreadCreateRequest](runthreadcreaterequest/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runthreadcreaterequest/assistantid/) { get; set; } | Bu çalışmayı yürütmek için kullanılacak asistanın kimliğini alır veya ayarlar. |
| [Instructions](../../aspose.pdf.ai/runthreadcreaterequest/instructions/) { get; set; } | Asistanın talimatlarını geçersiz kılan talimatları alır veya ayarlar. Bu, her çalışmada davranışı değiştirmek için yararlıdır. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxcompletiontokens/) { get; set; } | Çalışma süresince kullanılabilecek maksimum tamamlanma token sayısını alır veya ayarlar. Çalışma, belirtilen tamamlanma token sayısını kullanmak için en iyi çabayı gösterecektir, çalışmanın birden fazla turu boyunca. Eğer çalışma belirtilen tamamlanma token sayısını aşarsa, çalışma tamamlanmamış durumu ile sona erecektir. Daha fazla bilgi için incomplete_details'e bakın. |
| [MaxPromptTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxprompttokens/) { get; set; } | Çalışma süresince kullanılabilecek maksimum istem token sayısını alır veya ayarlar. Çalışma, belirtilen istem token sayısını kullanmak için en iyi çabayı gösterecektir, çalışmanın birden fazla turu boyunca. Eğer çalışma belirtilen istem token sayısını aşarsa, çalışma tamamlanmamış durumu ile sona erecektir. Daha fazla bilgi için incomplete_details'e bakın. |
| [Metadata](../../aspose.pdf.ai/runthreadcreaterequest/metadata/) { get; set; } | Bir nesneye eklenebilecek 16 anahtar-değer çiftinden oluşan bir küme alır veya ayarlar. Bu, nesne hakkında yapılandırılmış bir formatta ek bilgi saklamak için yararlı olabilir. Anahtarlar en fazla 64 karakter uzunluğunda ve değerler en fazla 512 karakter uzunluğunda olabilir. |
| [Model](../../aspose.pdf.ai/runthreadcreaterequest/model/) { get; set; } | Bu çalışmayı yürütmek için kullanılacak Model'in kimliğini alır veya ayarlar. Burada bir değer sağlanırsa, bu asistanla ilişkili modeli geçersiz kılacaktır. Aksi takdirde, asistanla ilişkili model kullanılacaktır. |
| [ResponseFormat](../../aspose.pdf.ai/runthreadcreaterequest/responseformat/) { get; set; } | Modelin çıktısının hangi formatta olması gerektiğini alır veya ayarlar. GPT-4o, GPT-4 Turbo ve gpt-3.5-turbo-1106'dan itibaren tüm GPT-3.5 Turbo modelleri ile uyumludur. { "type": "json_object" } olarak ayarlamak, modelin ürettiği mesajın geçerli bir JSON olmasını garanti eden JSON modunu etkinleştirir. Önemli: JSON modunu kullanırken, modelin kendinizin de bir sistem veya kullanıcı mesajı aracılığıyla JSON üretmesini sağlamalısınız. Bunu yapmadan, model boşlukların sonsuz bir akışını üretebilir, bu da üretim token limitine ulaşana kadar devam eder ve uzun süren ve görünüşte "takılmış" bir isteğe neden olur. Ayrıca, finish_reason="length" olduğunda mesaj içeriği kısmen kesilebilir; bu, üretimin max_tokens'ı aştığını veya konuşmanın max context uzunluğunu aştığını gösterir. |
| [Stream](../../aspose.pdf.ai/runthreadcreaterequest/stream/) { get; set; } | Akışın kullanılıp kullanılmayacağını alır veya ayarlar. Eğer doğruysa, Çalışma sırasında meydana gelen olayların bir akışını sunucu tarafından gönderilen olaylar olarak döndürür ve Çalışma terminal bir duruma girdiğinde data: [DONE] mesajı ile sona erer. |
| [Temperature](../../aspose.pdf.ai/runthreadcreaterequest/temperature/) { get; set; } | Kullanılacak örnekleme sıcaklığını alır veya ayarlar, 0 ile 2 arasında. 0.8 gibi daha yüksek değerler çıktıyı daha rastgele hale getirirken, 0.2 gibi daha düşük değerler daha odaklı ve belirleyici hale getirir. |
| [Thread](../../aspose.pdf.ai/runthreadcreaterequest/thread/) { get; set; } | Bir iş parçacığı oluşturma talebini alır veya ayarlar. |
| [ToolChoice](../../aspose.pdf.ai/runthreadcreaterequest/toolchoice/) { get; set; } | Model tarafından çağrılan (varsa) aracı alır veya ayarlar. none, modelin herhangi bir aracı çağırmayacağı ve bunun yerine bir mesaj üreteceği anlamına gelir. auto varsayılan değerdir ve modelin bir mesaj üretmek veya bir veya daha fazla aracı çağırmak arasında seçim yapabileceği anlamına gelir. required, modelin kullanıcıya yanıt vermeden önce bir veya daha fazla aracı çağırması gerektiği anlamına gelir. {"type": "file_search"} veya {"type": "function", "function": {"name": "my_function"}} gibi belirli bir aracı belirtmek, modelin o aracı çağırmasını zorlar. |
| [ToolResources](../../aspose.pdf.ai/runthreadcreaterequest/toolresources/) { get; set; } | Asistanın araçları tarafından kullanılan bir kaynak kümesini alır veya ayarlar. |
| [Tools](../../aspose.pdf.ai/runthreadcreaterequest/tools/) { get; set; } | Bu çalışmada asistanın kullanabileceği araçları geçersiz kılan araçları alır veya ayarlar. Bu, her çalışmada davranışı değiştirmek için yararlıdır. |
| [TopP](../../aspose.pdf.ai/runthreadcreaterequest/topp/) { get; set; } | Sıcaklık ile örnekleme alternatif bir değer alır veya ayarlar, çekirdek örnekleme olarak adlandırılır; burada model, en yüksek p olasılık kütlesine sahip token'ların sonuçlarını dikkate alır. Yani 0.1, yalnızca en yüksek %10 olasılık kütlesini oluşturan token'ların dikkate alındığı anlamına gelir. Genellikle bunu veya sıcaklığı değiştirmeyi öneriyoruz, ancak her ikisini birden değil. |
| [TruncationStrategy](../../aspose.pdf.ai/runthreadcreaterequest/truncationstrategy/) { get; set; } | Bir iş parçacığının çalışmadan önce nasıl kesileceğini kontrol eden kesme stratejisini alır veya ayarlar. Bunu, çalışmanın başlangıç bağlam penceresini kontrol etmek için kullanın. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)