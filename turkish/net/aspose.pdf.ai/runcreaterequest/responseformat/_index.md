---
title: RunCreateRequest.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: RunCreateRequest özelliği. Yanıt formatını alır veya ayarlar. Modelin çıkarması gereken formatı belirtir. GPT-4o, GPT-4 Turbo ve gpt-3.5turbo1106'dan beri tüm GPT-3.5 Turbo modelleri ile uyumludur. { "type": "json_object" } olarak ayarlamak, modelin ürettiği mesajın geçerli JSON olduğunu garanti eden JSON modunu etkinleştirir. Önemli: JSON modunu kullanırken, modelin JSON üretmesini kendiniz bir sistem veya kullanıcı mesajı aracılığıyla da talimat vermeniz gerekir. Bunu yapmadan, model, üretim token limitine ulaşana kadar sonsuz bir boşluk akışı üretebilir ve bu da uzun süren ve görünüşte "takılmış" bir isteğe yol açabilir. Ayrıca, finish_reason="length" olduğunda mesaj içeriğinin kısmen kesilebileceğini unutmayın; bu, üretimin max_tokens'ı aştığını veya konuşmanın max context uzunluğunu aştığını gösterir.
type: docs
weight: 100
url: /tr/net/aspose.pdf.ai/runcreaterequest/responseformat/
---
## RunCreateRequest.ResponseFormat özelliği

Yanıt formatını alır veya ayarlar. Modelin çıkarması gereken formatı belirtir. GPT-4o, GPT-4 Turbo ve gpt-3.5-turbo-1106'dan beri tüm GPT-3.5 Turbo modelleri ile uyumludur. { "type": "json_object" } olarak ayarlamak, modelin ürettiği mesajın geçerli JSON olduğunu garanti eden JSON modunu etkinleştirir. Önemli: JSON modunu kullanırken, modelin JSON üretmesini kendiniz bir sistem veya kullanıcı mesajı aracılığıyla da talimat vermeniz gerekir. Bunu yapmadan, model, üretim token limitine ulaşana kadar sonsuz bir boşluk akışı üretebilir ve bu da uzun süren ve görünüşte "takılmış" bir isteğe yol açabilir. Ayrıca, finish_reason="length" olduğunda mesaj içeriğinin kısmen kesilebileceğini unutmayın; bu, üretimin max_tokens'ı aştığını veya konuşmanın max context uzunluğunu aştığını gösterir.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### Ayrıca Bakınız

* class [ResponseFormat](../../responseformat/)
* class [RunCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)