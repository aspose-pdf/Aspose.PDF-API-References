---
title: RunResponse.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: RunResponse özelliği. Modelin çıktısının formatını alır veya ayarlar. GPT-4o, GPT-4 Turbo ve gpt-3.5turbo1106'dan beri tüm GPT-3.5 Turbo modelleri ile uyumludur. { "type": "json_object" } olarak ayarlamak, modelin ürettiği mesajın geçerli bir JSON olduğunu garanti eden JSON modunu etkinleştirir. Önemli: JSON modunu kullanırken, modelin JSON üretmesini de bir sistem veya kullanıcı mesajı aracılığıyla kendiniz talimat vermelisiniz. Bunu yapmazsanız, model, üretim token limitine ulaşana kadar bitmeyen bir boşluk akışı üretebilir ve bu da uzun süren ve görünüşte "takılmış" bir isteğe yol açar. Ayrıca, finish_reason="length" olduğunda mesaj içeriğinin kısmen kesilebileceğini unutmayın; bu, üretimin max_tokens'ı aştığını veya konuşmanın max context uzunluğunu aştığını gösterir.
type: docs
weight: 180
url: /tr/net/aspose.pdf.ai/runresponse/responseformat/
---
## RunResponse.ResponseFormat özelliği

Modelin çıktısının formatını alır veya ayarlar. GPT-4o, GPT-4 Turbo ve gpt-3.5-turbo-1106'dan beri tüm GPT-3.5 Turbo modelleri ile uyumludur. { "type": "json_object" } olarak ayarlamak, modelin ürettiği mesajın geçerli bir JSON olduğunu garanti eden JSON modunu etkinleştirir. Önemli: JSON modunu kullanırken, modelin JSON üretmesini de bir sistem veya kullanıcı mesajı aracılığıyla kendiniz talimat vermelisiniz. Bunu yapmazsanız, model, üretim token limitine ulaşana kadar bitmeyen bir boşluk akışı üretebilir ve bu da uzun süren ve görünüşte "takılmış" bir isteğe yol açar. Ayrıca, finish_reason="length" olduğunda mesaj içeriğinin kısmen kesilebileceğini unutmayın; bu, üretimin max_tokens'ı aştığını veya konuşmanın max context uzunluğunu aştığını gösterir.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### Ayrıca Bakınız

* sınıf [ResponseFormat](../../responseformat/)
* sınıf [RunResponse](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)