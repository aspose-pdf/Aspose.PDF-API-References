---
title: Class UnifiedSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.UnifiedSaveOptions sınıfı. Bu sınıf, birleşik iç belge modeli ile birleşik dönüşüm yolu kullanan kaydetme seçeneklerini temsil eder.
type: docs
weight: 11140
url: /tr/net/aspose.pdf/unifiedsaveoptions/
---
## UnifiedSaveOptions sınıfı

Bu sınıf, birleşik dönüşüm yolu (birleşik iç belge modeli ile) kullanan kaydetme seçeneklerini temsil eder.

```csharp
public class UnifiedSaveOptions : SaveOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [UnifiedSaveOptions](unifiedsaveoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Aps sayfaları hazırlanırken font gliflerinin önbelleğe alınıp alınmayacağını belirten boolean değeri alır veya ayarlar. PDF'nin diğer formatlara dönüştürülmesi performansını artırır ancak bellek tüketimini artırır. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Belgenin yanıt içine kaydedildikten sonra Yanıt nesnesinin kapatılıp kapatılmayacağını belirten boolean değeri alır veya ayarlar. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Bu özellik, OCR alt katmanına sahip PDF belgeleri için görüntü veya metin çıkarma işlevselliğini etkinleştirir. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Veri kaydetme formatı. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Oluşan uyarıları işlemek için geri çağırma. WarningHandler, devam etme veya iptal etme belirten ReturnAction enum öğesini döndürür. Devam etme varsayılan eylemdir ve Kaydetme işlemi devam eder, ancak kullanıcı iptal etmeyi de döndürebilir; bu durumda Kaydetme işlemi durmalıdır. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Sayfaları birkaç iş parçacığında işleme. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Bazen PDF'ler, yan yana yerleştirilmiş birkaç aynı döşeme arka plan görüntüsünden oluşan arka plan görüntüleri (sayfaların veya tablo hücrelerinin) içerir. Bu durumda, hedef formatların (örneğin, DOCS formatı için MsWord) renderlayıcıları bazen arka plan görüntülerinin parçaları arasında görünür sınırlar oluşturur; çünkü görüntü kenar yumuşatma (anti-aliasing) teknikleri Acrobat Reader'dan farklıdır. Eğer dışa aktarılan belgede aynı arka plan görüntülerinin parçaları arasında böyle görünür sınırlar varsa, bu ayarı kullanarak istenmeyen etkiden kurtulmayı deneyin. DİKKAT! Bu kalite optimizasyonu genellikle dönüşümü önemli ölçüde yavaşlatır, bu nedenle lütfen bu seçeneği yalnızca gerçekten gerekli olduğunda kullanın. |

### Ayrıca Bakınız

* sınıf [SaveOptions](../saveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)