---
title: Class CreateEmbeddingRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CreateEmbeddingRequest sınıfı. Create Embeddings uç noktası için bir isteği temsil eder
type: docs
weight: 260
url: /tr/net/aspose.pdf.ai/createembeddingrequest/
---
## CreateEmbeddingRequest sınıfı

Create Embeddings uç noktası için bir isteği temsil eder.

```csharp
public class CreateEmbeddingRequest
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [CreateEmbeddingRequest](createembeddingrequest/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | Ortaya çıkan çıktı gömme işlemlerinin sahip olması gereken boyut sayısını alır veya ayarlar. Sadece text-embedding-3 ve sonraki modellerde desteklenir. |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | Gömme işlemlerinin döndürüleceği formatı alır veya ayarlar. float veya base64 olabilir. |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | Gömülecek giriş metnini alır veya ayarlar, bir dize veya token dizisi olarak kodlanmıştır. Tek bir istekte birden fazla girişi gömmek için, bir dize dizisi veya token dizileri dizisi geçirin. Giriş, modelin maksimum giriş token sayısını aşmamalıdır (text-embedding-ada-002 için 8192 token), boş bir dize olamaz ve herhangi bir dizi 2048 boyutundan az olmalıdır. |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | Gömme işlemi oluşturulacak modeli alır veya ayarlar. |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | OpenAI'nin kötüye kullanımı izleyip tespit etmesine yardımcı olabilecek, son kullanıcıyı temsil eden benzersiz bir tanımlayıcıyı alır veya ayarlar. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)