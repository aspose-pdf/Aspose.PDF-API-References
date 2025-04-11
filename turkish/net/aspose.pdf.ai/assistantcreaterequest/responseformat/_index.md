---
title: AssistantCreateRequest.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: AssistantCreateRequest özelliği. Modelin çıkarması gereken formatı alır veya ayarlar. gpt3.5turbo1106'dan itibaren GPT-4o, GPT-4 Turbo ve tüm GPT-3.5 Turbo modelleri ile uyumludur. { "type": "json_object" } olarak ayarlamak, modelin ürettiği mesajın geçerli JSON olmasını garanti eden JSON modunu etkinleştirir. Önemli: JSON modunu kullanırken, modelin JSON üretmesini de bir sistem veya kullanıcı mesajı aracılığıyla talimat vermeniz gerekir. Bunu yapmazsanız, model, üretim token limitine ulaşana kadar durmaksızın boşluk akışı üretebilir ve bu da uzun süren ve görünüşte "takılmış" bir isteğe yol açabilir. Ayrıca, finish_reason="length" ise mesaj içeriğinin kısmen kesilebileceğini unutmayın; bu, üretimin max_tokens'ı aştığını veya konuşmanın max context uzunluğunu aştığını gösterir.
type: docs
weight: 70
url: /tr/net/aspose.pdf.ai/assistantcreaterequest/responseformat/
---
## AssistantCreateRequest.ResponseFormat özelliği

Modelin çıkarması gereken formatı alır veya ayarlar. gpt-3.5-turbo-1106'dan itibaren GPT-4o, GPT-4 Turbo ve tüm GPT-3.5 Turbo modelleri ile uyumludur. { "type": "json_object" } olarak ayarlamak, modelin ürettiği mesajın geçerli JSON olmasını garanti eden JSON modunu etkinleştirir. Önemli: JSON modunu kullanırken, modelin JSON üretmesini de bir sistem veya kullanıcı mesajı aracılığıyla talimat vermeniz gerekir. Bunu yapmazsanız, model, üretim token limitine ulaşana kadar durmaksızın boşluk akışı üretebilir ve bu da uzun süren ve görünüşte "takılmış" bir isteğe yol açabilir. Ayrıca, finish_reason="length" ise mesaj içeriğinin kısmen kesilebileceğini unutmayın; bu, üretimin max_tokens'ı aştığını veya konuşmanın max context uzunluğunu aştığını gösterir.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### Ayrıca Bakınız

* class [ResponseFormat](../../responseformat/)
* class [AssistantCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)