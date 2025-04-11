---
title: Class MarkdownSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.MarkdownSaveOptions sınıfı. Markdown formatında belge kaydetme seçenekleri sınıfını temsil eder.
type: docs
weight: 6910
url: /tr/net/aspose.pdf/markdownsaveoptions/
---
## MarkdownSaveOptions sınıfı

Markdown formatında belge kaydetme seçenekleri sınıfını temsil eder.

```csharp
public class MarkdownSaveOptions : UnifiedSaveOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | İçeriği markdown'a çıkarmak için bir dikdörtgen alanı alır veya ayarlar. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Aps sayfaları hazırlanırken font gliflerinin önbelleğe alınıp alınmayacağını belirten boolean değeri alır veya ayarlar. PDF'nin diğer formatlara dönüştürülmesi performansını artırır ancak bellek tüketimini artırır. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Belge yanıt olarak kaydedildikten sonra Response nesnesinin kapatılıp kapatılmayacağını belirten boolean değeri alır veya ayarlar. |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | Üretilen belgenin vurgulama stilini alır veya ayarlar. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Bu özellik, OCR alt katmanına sahip PDF belgeleri için resim veya metin çıkarmak için işlevselliği etkinleştirir. |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | Vektör grafiklerin çıkarılıp çıkarılmayacağını belirten bir özelliği alır ve ayarlar. |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | FontBoyut tanıma başlıkları stratejisinde kullanılacak beklenen başlık seviyelerini tanımlar. Bu özellik değeri ayarlandığında, başlık tanıma !:PdfToMarkdown.HeadingRecognitionStrategy.Heuristic stratejisi seçilecektir, !:PdfToMarkdown.HeadingRecognitionStrategy.Auto stratejileri ayarlandığında bile, belge yer işaretleri içeriyorsa. |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | Başlık tanıma stratejisini alır veya ayarlar. |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | Üretilen belgenin başlık stilini alır veya ayarlar. |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | Üretilen belgenin satır sonu stilini alır veya ayarlar. |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | Belge kaynaklarını (görüntüler gibi) kaydetmek için dizin adını alır ve ayarlar. Değer belirtilmezse, görüntüler markdown dosyasının bulunduğu dizine yazılacaktır. Bu bir yol değil, sadece bir isimdir! Bu dizin, kaydedilen markdown dosyasının bulunduğu dizinde otomatik olarak oluşturulacaktır. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Veri kaydetme formatı. |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | Alt ve üst simgelerin dönüştürülmesine izin verir veya ayarlar. Bu değer varsayılan olarak doğrudur. |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | Metnin soluna ve sağına resim eklemek için bir img etiketinin kullanımına izin verir ve ayarlar. Bu durumda, markdown görüntüleyicisinde metin resmin etrafında sarılacaktır. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Oluşan uyarıları işlemek için geri çağırma. WarningHandler, devam et veya iptal et belirten ReturnAction enum öğesini döndürür. Devam et varsayılan eylemdir ve kaydetme işlemi devam eder, ancak kullanıcı iptal de döndürebilir; bu durumda kaydetme işlemi durmalıdır. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Sayfaları birkaç iş parçacığında işleyin. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Bazen PDF'ler, yan yana yerleştirilmiş birkaç aynı döşeme arka plan görüntüsünden oluşan arka plan görüntüleri (sayfalar veya tablo hücreleri) içerir. Bu durumda, hedef formatların (örneğin, DOCS formatı için MsWord) renderlayıcıları bazen arka plan görüntülerinin parçaları arasında görünür sınırlar oluşturur, çünkü görüntü kenar yumuşatma (anti-aliasing) teknikleri Acrobat Reader'dan farklıdır. Eğer dışa aktarılan belgede aynı arka plan görüntülerinin parçaları arasında böyle görünür sınırlar varsa, bu ayarı kullanarak istenmeyen etkiden kurtulmayı deneyin. DİKKAT! Bu kalite optimizasyonu genellikle dönüşümü önemli ölçüde yavaşlatır, bu nedenle bu seçeneği yalnızca gerçekten gerekli olduğunda kullanın. |

### Ayrıca Bakınız

* sınıf [UnifiedSaveOptions](../unifiedsaveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)