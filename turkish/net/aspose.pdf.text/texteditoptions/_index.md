---
title: Class TextEditOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextEditOptions sınıfı. Metin düzenleme işlemlerinin seçeneklerini açıklar.
type: docs
weight: 10820
url: /tr/net/aspose.pdf.text/texteditoptions/
---
## TextEditOptions sınıfı

Metin düzenleme işlemlerinin seçeneklerini açıklar.

```csharp
public sealed class TextEditOptions : TextOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | Belirtilen dil dönüşüm izni için `TextEditOptions` nesnesinin yeni bir örneğini başlatır. |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | Belirtilen yazı tipi değiştirme davranış modu için `TextEditOptions` nesnesinin yeni bir örneğini başlatır. |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | Belirtilen dil dönüşüm davranış modu için `TextEditOptions` nesnesinin yeni bir örneğini başlatır. |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | Belirtilen karakter yok davranış modu için `TextEditOptions` nesnesinin yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | Metin ekleme veya düzenleme sırasında dil dönüşümünün kullanımına izin veren değeri alır veya ayarlar. true - gerekli olduğunda dil dönüşümü uygulanacaktır (varsayılan değer). false - dil dönüşümü uygulanmayacaktır. |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | Düzenlenen metnin kesme yolunu işleme modunu alır. |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | Yazı tipi değiştirme senaryoları için davranışı tanımlayan modu alır. |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | Dil dönüşüm senaryoları için davranışı tanımlayan modu alır. |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | Yazı tiplerinin istenen karakterleri içermediği durumlarda davranışı tanımlayan modu alır veya ayarlar. |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | Kullanıcı yazı tipi gerekli karakteri içermediğinde kullanılacak yazı tipini alır veya ayarlar. |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | Kaynak belgenin sayfasında metin altı çizgisi aramaya izin veren değeri alır veya ayarlar. (Eski) Bunun yerine TextSearchOptions.SearchForTextRelatedGraphics kullanın. |

### Ayrıca Bakınız

* sınıf [TextOptions](../textoptions/)
* ad alanı [Aspose.Pdf.Text](../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../)