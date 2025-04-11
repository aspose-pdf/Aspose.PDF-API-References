---
title: Class CreateChatCompletionChunkResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CreateChatCompletionChunkResponse sınıfı. Sağlanan girdi temelinde model tarafından döndürülen bir sohbet tamamlama yanıtının akışa dayalı parçasını temsil eder.
type: docs
weight: 250
url: /tr/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## CreateChatCompletionChunkResponse sınıfı

Sağlanan girdi temelinde model tarafından döndürülen bir sohbet tamamlama yanıtının akışa dayalı parçasını temsil eder.

```csharp
public class CreateChatCompletionChunkResponse
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [CreateChatCompletionChunkResponse](createchatcompletionchunkresponse/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | Sohbet tamamlama seçeneklerinin bir listesini alır veya ayarlar. n 1'den büyükse birden fazla öğe içerebilir. Ayrıca, stream_options: {"include_usage": true} ayarlandığında son parça için boş da olabilir. |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | Sohbet tamamlama oluşturulduğunda Unix zaman damgasını (saniye cinsinden) alır veya ayarlar. Her parça aynı zaman damgasına sahiptir. |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | Sohbet tamamlama için benzersiz bir tanımlayıcı alır veya ayarlar. Her parça aynı ID'ye sahiptir. |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | Tamamlamayı oluşturmak için modeli alır veya ayarlar. |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | Her zaman chat.completion.chunk olan nesne türünü alır veya ayarlar. |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | Modelin çalıştığı arka uç yapılandırmasını temsil eden parmak izini alır veya ayarlar. Determinizm üzerinde etkisi olabilecek arka uç değişikliklerinin ne zaman yapıldığını anlamak için seed istek parametresi ile birlikte kullanılabilir. |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | İsteğinizde stream_options: {"include_usage": true} ayarlandığında yalnızca mevcut olacak isteğe bağlı bir alanı alır veya ayarlar. Mevcut olduğunda, tüm istek için token kullanım istatistiklerini içeren son parça hariç null değer içerir. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)