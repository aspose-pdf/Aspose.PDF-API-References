---
title: Class AssistantCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.AssistantCreateRequest sınıfı. Bir asistan oluşturmak için istek nesnesi
type: docs
weight: 100
url: /tr/net/aspose.pdf.ai/assistantcreaterequest/
---
## AssistantCreateRequest sınıfı

Bir asistan oluşturmak için istek nesnesi.

```csharp
public class AssistantCreateRequest
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [AssistantCreateRequest](assistantcreaterequest/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Description](../../aspose.pdf.ai/assistantcreaterequest/description/) { get; set; } | Asistanın açıklamasını alır veya ayarlar. Maksimum uzunluk 512 karakterdir. |
| [Instructions](../../aspose.pdf.ai/assistantcreaterequest/instructions/) { get; set; } | Asistanın kullandığı sistem talimatlarını alır veya ayarlar. Maksimum uzunluk 256.000 karakterdir. |
| [Metadata](../../aspose.pdf.ai/assistantcreaterequest/metadata/) { get; set; } | Bir nesneye eklenebilecek 16 anahtar-değer çiftinden oluşan bir küme alır veya ayarlar. Bu, nesne hakkında yapılandırılmış bir formatta ek bilgi depolamak için yararlı olabilir. Anahtarlar maksimum 64 karakter uzunluğunda olabilir ve değerler maksimum 512 karakter uzunluğunda olabilir. |
| [Model](../../aspose.pdf.ai/assistantcreaterequest/model/) { get; set; } | Kullanılacak modelin kimliğini alır veya ayarlar. Tüm mevcut modellerinizi görmek için List models API'sini kullanabilir veya açıklamaları için Model genel bakışımıza göz atabilirsiniz. |
| [Name](../../aspose.pdf.ai/assistantcreaterequest/name/) { get; set; } | Asistanın adını alır veya ayarlar. Maksimum uzunluk 256 karakterdir. |
| [ResponseFormat](../../aspose.pdf.ai/assistantcreaterequest/responseformat/) { get; set; } | Modelin çıkarması gereken formatı alır veya ayarlar. GPT-4o, GPT-4 Turbo ve gpt-3.5-turbo-1106'dan itibaren tüm GPT-3.5 Turbo modelleri ile uyumludur. { "type": "json_object" } olarak ayarlamak, modelin ürettiği mesajın geçerli JSON olmasını garanti eden JSON modunu etkinleştirir. Önemli: JSON modunu kullanırken, modelin kendinizin bir sistem veya kullanıcı mesajı aracılığıyla JSON üretmesini de talimat vermeniz gerekir. Bunu yapmadan, model, üretim token limitine ulaşana kadar sonsuz bir boşluk akışı üretebilir, bu da uzun süren ve görünüşte "takılmış" bir isteğe neden olabilir. Ayrıca, finish_reason="length" olduğunda mesaj içeriğinin kısmen kesilebileceğini unutmayın; bu, üretimin max_tokens'ı aştığını veya konuşmanın maksimum bağlam uzunluğunu aştığını gösterir. |
| [Temperature](../../aspose.pdf.ai/assistantcreaterequest/temperature/) { get; set; } | Kullanılacak örnekleme sıcaklığını alır veya ayarlar, 0 ile 2 arasında. 0.8 gibi daha yüksek değerler çıktıyı daha rastgele hale getirirken, 0.2 gibi daha düşük değerler daha odaklı ve belirleyici hale getirir. |
| [ToolResources](../../aspose.pdf.ai/assistantcreaterequest/toolresources/) { get; set; } | Asistanın araçları tarafından kullanılan kaynakları alır veya ayarlar. Kaynaklar, aracın türüne özgüdür. Örneğin, code_interpreter aracı bir dosya kimlikleri listesi gerektirirken, file_search aracı bir vektör deposu kimlikleri listesi gerektirir. |
| [Tools](../../aspose.pdf.ai/assistantcreaterequest/tools/) { get; set; } | Asistanda etkinleştirilen araçların bir listesini alır veya ayarlar. Her asistan için maksimum 128 araç olabilir. Araçlar code_interpreter, file_search veya function türlerinde olabilir. |
| [TopP](../../aspose.pdf.ai/assistantcreaterequest/topp/) { get; set; } | Sıcaklık ile örnekleme için bir alternatif alır veya ayarlar, çekirdek örnekleme olarak adlandırılır; burada model, en yüksek p olasılık kütlesine sahip tokenların sonuçlarını dikkate alır. Yani 0.1, yalnızca en yüksek %10 olasılık kütlesini oluşturan tokenların dikkate alındığı anlamına gelir. Genellikle bunu veya sıcaklığı değiştirmeyi öneriyoruz, ancak her ikisini birden değil. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)