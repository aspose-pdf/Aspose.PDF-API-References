---
title: Class SvgExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.SvgExtractionOptions sınıfı. PDF belgesi sayfasından vektör grafikleri çıkarmak için bir seçenek sınıfını temsil eder.
type: docs
weight: 11240
url: /tr/net/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions sınıfı

PDF belgesi sayfasından vektör grafikleri çıkarmak için bir seçenek sınıfını temsil eder.

```csharp
public class SvgExtractionOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [SvgExtractionOptions](svgextractionoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | Alt yolları otomatik olarak resimlere gruplama seçeneğini alır ve ayarlar. Bu seçenek [`GroupStrength`](./groupstrength/) seçeneğini hariç tutar. |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | Her alt yolu bir PDF belgesinden ayrı SVG resimlerine çıkarmak için seçeneği alır ve ayarlar. |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | SVG çıkarımı için çıkarım alanını tanımlayan sınırlayıcı dikdörtgeni alır ve ayarlar. |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | Alt yolları resimlere gruplamanın gücünü belirleyen bir seçeneği alır ve ayarlar. Alt yolların gruplama derecesini yapılandırmanıza olanak tanır. Değer aralığı 0 ile 1 arasındadır. 0 değeri, [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/) seçeneğinin etkin olduğunu gösterir. 1 değeri, sayfadaki tüm vektör yolları için tek bir resim oluşturur. Bu seçenek, [`AutoGrouping`](./autogrouping/) yanlış olduğunda etkilidir. Varsayılan değer `0.8`'dir. |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | Sonuçta elde edilen SVG'de kullanılacak minimum çizgi kalınlığını alır veya ayarlar. PDF daha ince bir çizgi kalınlığı kullanıyorsa, bu kalınlıkla değiştirilir. Varsayılan değer 0.5'tir. |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | Alt yolların [`ExtractionAreaBound`](./extractionareabound/) içinde belirtilen dikdörtgenin içinde olup olmadığını kesin bir şekilde kontrol etme seçeneğini alır ve ayarlar. Yanlış olarak ayarlandığında, [`ExtractionAreaBound`](./extractionareabound/) içinde tamamen yer almayan alt yollar çıkarılacaktır. Varsayılan değer `True`'dur. |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | Sayfalarda bulunan XForm'un açılıp açılmayacağını belirleyen bir bayrağı alır ve ayarlar. XForm öğeleri farklı SVG dosyalarında yer alabilir. Sadece sayfa içeriğinden Do ifadeleriyle işlenen XForm'lar açılır. İç içe geçmiş XForm'lar açılmaz. |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | Belirtilen predikata karşılık gelen yalnızca XForm'u açma seçeneğini alır ve ayarlar. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)