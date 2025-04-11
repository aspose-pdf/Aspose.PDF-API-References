---
title: Class PsSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PsSaveOptions sınıfı. PS PostScript veya EPS formatına dışa aktarma için kaydetme seçenekleri
type: docs
weight: 9740
url: /tr/net/aspose.pdf/pssaveoptions/
---
## PsSaveOptions Sınıfı

PS (PostScript) veya EPS formatına dışa aktarma için kaydetme seçenekleri.

```csharp
public class PsSaveOptions : UnifiedSaveOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PsSaveOptions](pssaveoptions/#constructor)() | Yapıcı. |
| [PsSaveOptions](pssaveoptions/#constructor_1)(SaveFormat) | Yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Aps sayfaları hazırlanırken font gliflerinin önbelleğe alınıp alınmayacağını belirten boolean değeri alır veya ayarlar. PDF'nin diğer formatlara dönüştürülmesi performansını artırır ancak bellek tüketimini artırır. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Belge yanıt olarak kaydedildikten sonra Yanıt nesnesinin kapatılıp kapatılmayacağını belirten boolean değeri alır veya ayarlar. |
| [EmbedFont](../../aspose.pdf/pssaveoptions/embedfont/) { get; set; } | Sonuçta elde edilen PS belgesinde fontların gömülmesi gerekip gerekmediğini belirten bayrağı alır/ayarlar. |
| [EmbedFontAs](../../aspose.pdf/pssaveoptions/embedfontas/) { get; set; } | Sonuçta elde edilen PS belgesinde fontların hangi türde gömülmesi gerektiğini alır/ayarlar. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Bu özellik, OCR alt katmanına sahip PDF belgeleri için görüntü veya metin çıkarmak için işlevselliği etkinleştirir. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Veri kaydetme formatı. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Oluşan herhangi bir uyarıyı işlemek için geri çağırma. WarningHandler, devam etme veya iptal etme belirten ReturnAction enum öğesini döndürür. Devam etme varsayılan eylemdir ve Kaydetme işlemi devam eder, ancak kullanıcı iptal etme döndürebilir; bu durumda Kaydetme işlemi durmalıdır. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Sayfaları birkaç iş parçacığında işleme. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Bazen PDF'ler, yan yana yerleştirilmiş birkaç aynı döşeme arka plan görüntüsünden oluşan arka plan görüntüleri içerir (sayfalar veya tablo hücreleri). Bu durumda, hedef formatların (örneğin, DOCS formatı için MsWord) renderlayıcıları bazen arka plan görüntülerinin parçaları arasında görünür sınırlar oluşturur; çünkü görüntü kenar yumuşatma (anti-aliasing) teknikleri Acrobat Reader'dan farklıdır. Eğer dışa aktarılan belgede aynı arka plan görüntülerinin parçaları arasında görünür sınırlar varsa, bu ayarı kullanarak istenmeyen etkiden kurtulmayı deneyin. DİKKAT! Bu kalite optimizasyonu genellikle dönüşümü önemli ölçüde yavaşlatır, bu nedenle bu seçeneği yalnızca gerçekten gerekli olduğunda kullanın. |

### Ayrıca Bakınız

* sınıf [UnifiedSaveOptions](../unifiedsaveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)