---
title: RunThreadCreateRequest.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: RunThreadCreateRequest özelliği. Modelin çıkış formatını alır veya ayarlar. GPT-4o, GPT-4 Turbo ve gpt-3.5turbo1106'dan itibaren tüm GPT-3.5 Turbo modelleri ile uyumludur. "type": "json_object" olarak ayarlamak, modelin ürettiği mesajın geçerli JSON olduğunu garanti eden JSON modunu etkinleştirir. Önemli: JSON modunu kullanırken, modelin JSON üretmesini de bir sistem veya kullanıcı mesajı aracılığıyla kendiniz talimat vermelisiniz. Bunu yapmazsanız, model, üretim token limitine ulaşana kadar bitmeyen bir boşluk akışı üretebilir ve bu da uzun süren ve görünüşte "takılmış" bir isteğe neden olabilir. Ayrıca, mesaj içeriğinin, üretimin max_tokens'ı aştığını veya konuşmanın max context uzunluğunu aştığını belirten finish_reason="length" olduğunda kısmen kesilebileceğini unutmayın.
type: docs
weight: 80
url: /tr/net/aspose.pdf.ai/runthreadcreaterequest/responseformat/
---
## RunThreadCreateRequest.ResponseFormat özelliği

Modelin çıkış formatını alır veya ayarlar. GPT-4o, GPT-4 Turbo ve gpt-3.5-turbo-1106'dan itibaren tüm GPT-3.5 Turbo modelleri ile uyumludur. { "type": "json_object" } olarak ayarlamak, modelin ürettiği mesajın geçerli JSON olduğunu garanti eden JSON modunu etkinleştirir. Önemli: JSON modunu kullanırken, modelin JSON üretmesini de bir sistem veya kullanıcı mesajı aracılığıyla kendiniz talimat vermelisiniz. Bunu yapmazsanız, model, üretim token limitine ulaşana kadar bitmeyen bir boşluk akışı üretebilir ve bu da uzun süren ve görünüşte "takılmış" bir isteğe neden olabilir. Ayrıca, mesaj içeriğinin, üretimin max_tokens'ı aştığını veya konuşmanın max context uzunluğunu aştığını belirten finish_reason="length" olduğunda kısmen kesilebileceğini unutmayın.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### Ayrıca Bakınız

* class [ResponseFormat](../../responseformat/)
* class [RunThreadCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)