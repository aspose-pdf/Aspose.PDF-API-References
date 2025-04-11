---
title: Class CompletionCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CompletionCreateRequest sınıfı. Create Chat Completion uç noktasına bir istek temsil eder
type: docs
weight: 220
url: /tr/net/aspose.pdf.ai/completioncreaterequest/
---
## CompletionCreateRequest sınıfı

Create Chat Completion uç noktasına bir istek temsil eder.

```csharp
public class CompletionCreateRequest
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [CompletionCreateRequest](completioncreaterequest/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | -2.0 ile 2.0 arasında bir sayı alır veya ayarlar. Pozitif değerler, mevcut metindeki sıklıklarına dayanarak yeni token'ları cezalandırır, modelin aynı satırı kelimesi kelimesine tekrar etme olasılığını azaltır. |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | Tamamlamada belirtilen token'ların görünme olasılığını alır veya ayarlar. Token'ları (tokenizer'daki token ID'leri ile belirtilen) -100 ile 100 arasında bir ilişkilendirilmiş önyargı değeri ile eşleyen bir JSON nesnesi kabul eder. |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | Çıktı token'larının log olasılıklarını döndürüp döndürmeyeceğini alır veya ayarlar. Eğer doğruysa, mesajın içeriğinde döndürülen her çıktı token'ının log olasılıklarını döndürür. |
| [MaxTokens](../../aspose.pdf.ai/completioncreaterequest/maxtokens/) { get; set; } | Tamamlamada oluşturulacak maksimum token sayısını alır veya ayarlar. |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | Şu ana kadar olan konuşmayı içeren bir mesajlar listesi alır veya ayarlar. |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | Kullanılacak modelin ID'sini alır veya ayarlar. |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | Her giriş mesajı için oluşturulacak kaç tane sohbet tamamlama seçeneği olduğunu alır veya ayarlar. Üretilen token sayısına göre ücretlendirileceğinizi unutmayın. Maliyetleri minimize etmek için n'yi 1 olarak tutun. |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | -2.0 ile 2.0 arasında bir sayı alır veya ayarlar. Pozitif değerler, yeni token'ların şu ana kadar metinde görünüp görünmediğine dayanarak ceza verir, modelin yeni konular hakkında konuşma olasılığını artırır. |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | Modelin çıktısının hangi formatta olması gerektiğini belirten bir nesne alır veya ayarlar. GPT-4 Turbo ve gpt-3.5-turbo-1106'dan daha yeni tüm GPT-3.5 Turbo modelleri ile uyumludur. { "type": "json_object" } olarak ayarlandığında, modelin ürettiği mesajın geçerli bir JSON olmasını garanti eden JSON modunu etkinleştirir. |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | Seed değerini alır veya ayarlar. Bu özellik Beta aşamasındadır. Belirtilirse, sistemimiz, aynı seed ve parametrelerle tekrar eden isteklerin aynı sonucu döndürmesi için deterministik olarak örneklemeye en iyi çabayı gösterecektir. Determinizm garanti edilmez ve arka plandaki değişiklikleri izlemek için system_fingerprint yanıt parametresine başvurmalısınız. |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | API'nin daha fazla token üretmeyi durduracağı 4'e kadar diziyi alır veya ayarlar. |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | Akış kullanılıp kullanılmayacağını alır veya ayarlar. Ayarlandığında, ChatGPT'deki gibi kısmi mesaj delta'ları gönderilecektir. Token'lar, mevcut olduklarında veri yalnızca sunucu tarafından gönderilen olaylar olarak gönderilecektir ve akış, data: [DONE] mesajı ile sonlandırılacaktır. |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | Kullanılacak örnekleme sıcaklığını alır veya ayarlar, 0 ile 2 arasında. 0.8 gibi daha yüksek değerler çıktıyı daha rastgele hale getirirken, 0.2 gibi daha düşük değerler daha odaklı ve deterministik hale getirir. |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | Model tarafından çağrılan (varsa) aracı kontrol eden bir nesne alır veya ayarlar. none, modelin herhangi bir aracı çağırmayacağı ve bunun yerine bir mesaj üreteceği anlamına gelir. auto, modelin bir mesaj üretmek veya bir veya daha fazla aracı çağırmak arasında seçim yapabileceği anlamına gelir. required, modelin bir veya daha fazla aracı çağırması gerektiği anlamına gelir. {"type": "function", "function": {"name": "my_function"}} ile belirli bir aracı belirtmek, modelin o aracı çağırmasını zorlar. Araç yoksa none varsayılandır. Araçlar varsa auto varsayılandır. |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | Modelin çağırabileceği araçların bir listesini alır veya ayarlar. Şu anda, yalnızca işlevler bir araç olarak desteklenmektedir. Modelin JSON girdileri oluşturabileceği işlevlerin bir listesini sağlamak için bunu kullanın. Maksimum 128 işlev desteklenmektedir. |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | Sıcaklık ile örnekleme alternatifini alır veya ayarlar, nükleus örnekleme olarak adlandırılır, burada model, top_p olasılık kütlesine sahip token'ların sonuçlarını dikkate alır. Yani 0.1, yalnızca en üst %10 olasılık kütlesini oluşturan token'ların dikkate alındığı anlamına gelir. |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | OpenAI'nin kötüye kullanımı izleyip tespit etmesine yardımcı olabilecek, son kullanıcıyı temsil eden benzersiz bir tanımlayıcı alır veya ayarlar. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)