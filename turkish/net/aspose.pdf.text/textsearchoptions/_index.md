---
title: Class TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextSearchOptions sınıfı. Metin arama seçeneklerini temsil eder
type: docs
weight: 11040
url: /tr/net/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions sınıfı

Metin arama seçeneklerini temsil eder

```csharp
public sealed class TextSearchOptions : TextOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | `TextSearchOptions` nesnesinin yeni bir örneğini başlatır. Düzenli ifade kullanım modunu belirtir. |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | `TextSearchOptions` nesnesinin yeni bir örneğini başlatır. Aranan metni sınırlayan dikdörtgeni belirtir. |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | `TextSearchOptions` nesnesinin yeni bir örneğini başlatır. Aranan metni sınırlayan dikdörtgeni ve düzenli ifade kullanım modunu belirtir. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | Metin (parça) alıcısı tarafından font eksikliği ile ilgili hataların göz ardı edilip edilmeyeceğini alır veya ayarlar. true - font eksikliği hatalarının göz ardı edileceğini belirtir. Yanlış kaynaklara atıfta bulunan metin segmentleri işleme sırasında atlanacaktır. false (varsayılan) - font eksikliği hatası, bir istisna fırlatarak işlemi sonlandırır. |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | Normal metnin gölgesini temsil eden metin parçalarının arama sırasında göz ardı edilip edilmeyeceğini alır veya ayarlar. true - gölge metnin bulunmayacağını belirtir (metin araması yakın konumlarda tekrar eden parçalar döndürüyorsa bunu deneyin) false - gölge metin normal metinle birlikte bulunacaktır (varsayılan değer) |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | Düzenli ifadenin kullanılıp kullanılmadığını alır veya ayarlar. |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | Metnin sayfa sınırları içinde aranıp aranmayacağını alır veya ayarlar. |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | Metin çıkarma (kod çözme) hatalarının metin (parça) alıcısında kaydedilip edilmeyeceğini alır veya ayarlar. true - metin çıkarma (kod çözme) hatalarının kaydedileceğini belirtir. Bu performansı düşürebilir. false (varsayılan) - hata kaydı yok. |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | Aranan metni sınırlayan dikdörtgeni alır veya ayarlar. |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | Metin araması sırasında metinle ilgili grafiklerin (altı çizme, arka plan vb.) aranmasına izin veren değeri alır veya ayarlar. true - metinle ilgili grafiklerin aranacağı belirtilir (varsayılan değer). false - kaynak belgede mevcut olabilecek grafik unsurlar göz ardı edilecektir. Performans sorunları veya altı çizme, arka plan veya kesme ile ilgilenme gereği olmadığında bunu ayarlayın. |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | Anotasyonlarda metin aramaya izin veren değeri alır veya ayarlar. true - metin Anotasyonlarda aranacaktır. false - Anotasyonlardaki metin, TextFragmentAbsorber tarafından ayrıştırılmayacaktır. |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | Belirtilen sayıda öğe için bir sayfadaki metinle ilgili grafiklerin (altı çizme, arka plan vb.) aranmasını sınırlayan değeri alır veya ayarlar. Varsayılan 250'dir. Performans sorunları durumunda daha düşük bir değer ayarlayın, bazı grafik unsurlar bulunmadığında daha büyük bir değer deneyin. |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | Metnin font motoru kodlaması kullanılarak aranıp aranmayacağını alır veya ayarlar. true - font motoru kodlamasının kullanılacağını belirtir (metin araması belgedeki eksik kodlama nedeniyle başarısız olursa bunu deneyin) false - belgenin font kodlamasının kullanılacağını belirtir (varsayılan değer) |

### Ayrıca Bakınız

* sınıf [TextOptions](../textoptions/)
* ad alanı [Aspose.Pdf.Text](../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../)