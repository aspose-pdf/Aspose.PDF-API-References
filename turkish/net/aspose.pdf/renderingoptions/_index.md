---
title: Class RenderingOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.RenderingOptions sınıfı. Render seçeneklerini temsil eder
type: docs
weight: 9760
url: /tr/net/aspose.pdf/renderingoptions/
---
## RenderingOptions sınıfı

Render seçeneklerini temsil eder.

```csharp
public sealed class RenderingOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [RenderingOptions](renderingoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | Metindeki tüm karakterlerin görüntülenebilmesini sağlamak için gerekli olduğunda fontları değiştirir. Font değiştirme algoritması şu adımları izler: 1. Kullanıcı DefaultFontName özelliğini açıkça ayarlarsa, belirtilen fontun istenen karakterleri görüntüleyip görüntüleyemeyeceğini kontrol edin. 2. Kullanıcı tanımlı bir font ayarlanmamışsa, !:FontRepository.Sources aracılığıyla eklenen fontlar arasında arama yapın. 3. Metni analiz ederek alfabesini veya yazı tipini belirleyin ve buna göre font isimleri önerin. Bu fontları sistemden bulmaya ve kullanmaya çalışın. 4. Yedek olarak, gerekli karakterleri görüntüleyebilen herhangi bir font için sistemi arayın. |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | Barkod optimizasyon modunu alır veya ayarlar. |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | Tüm fontların TTF unicode versiyonlarına dönüştürüleceğini belirtir. Bu, uyumluluk nedenleri ve font kullanımını optimize etmek için yararlıdır, çünkü her yeni TTF font, kaynak fontun tüm sembollerini değil, yalnızca metinde kullanılan sembolleri içerecektir. |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | Eksik fontların yerine kullanılacak varsayılan font adını alır/ayarlar. |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | AppendRectangle operatörü için dikdörtgenin yüksekliğini artırmak veya azaltmak için kullanılan bir değeri alır veya ayarlar. |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | Font eksikliği ile ilgili hataların göz ardı edileceğini belirtir. true - font eksikliği hatalarının göz ardı edileceği anlamına gelir. Yanlış kaynaklara atıfta bulunan metin segmentleri işleme sırasında atlanacaktır. varsayılan olarak false |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | İnterpolasyon için yüksek kaliteli modu alır veya ayarlar. |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | Font önbelleğindeki maksimum font sayısı. Varsayılan değer 10'dur. |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | Sembol önbelleğindeki maksimum sembol sayısı. Varsayılan değer 100'dür. |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | Boyutları optimize etme modunu alır veya ayarlar. |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | Sistem fontlarının yerel olarak render edildiği bir modu alır veya ayarlar. |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | Bu bayrağın kullanımı font hinting mekanizmasını açar. Font hinting, bir kontur fontunun görüntülenmesini ayarlamak için matematiksel talimatların kullanılmasını ifade eder. Bu bayrağı açmak, metin okunabilirliği ile ilgili sorunları çözebilir. Şu anda bu bayrağın kullanımı yalnızca TTF fontları için etki gösterebilir, eğer bu fontlar kaynak belgede kullanılıyorsa. |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | AppendRectangle operatörü için dikdörtgenin genişliğini artırmak veya azaltmak için kullanılan bir değeri alır veya ayarlar. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)