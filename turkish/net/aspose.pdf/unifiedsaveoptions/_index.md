---
title: UnifiedSaveOptions
second_title: Aspose.PDF for .NET API Referansı
description: Bu sınıf nin birleşik dönüştürme yolunu kullandığı birleşik dahili belge modeliyle kaydetmeye yönelik kaydetme seçeneklerini temsil eder
type: docs
weight: 7280
url: /tr/net/aspose.pdf/unifiedsaveoptions/
---
## UnifiedSaveOptions class

Bu sınıf, 'nin birleşik dönüştürme yolunu kullandığı (birleşik dahili belge modeliyle) kaydetmeye yönelik kaydetme seçeneklerini temsil eder

```csharp
public class UnifiedSaveOptions : SaveOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [UnifiedSaveOptions](unifiedsaveoptions)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | Belge yanıta kaydedildikten sonra Response nesnesinin kapatılacağını belirten boole değerini alır veya ayarlar. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | Bu özellik, OCR alt katmanına sahip PDF belgeleri için resim veya metin çıkarma işlevini açtı . |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | Veri kaydetme biçimi. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | Oluşturulan uyarıları işlemek için geri arama. WarningHandler, Continue veya Abort'u belirten ReturnAction numaralandırma öğesini döndürür. Devam, varsayılan eylemdir ve Kaydetme işlemi devam eder, ancak kullanıcı ayrıca Durdur'a da dönebilir, bu durumda Kaydetme işlemi sona ermelidir. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | Bazen PDF'ler arka plan görüntülerini (sayfaların veya tablo hücrelerinin) içerir , birbirinin yanına yerleştirilmiş birkaç aynı döşeme arka plan görüntüsünden oluşturulmuştur. Bu durumda hedef biçimlerin oluşturucuları (DOCS biçimi için fe MsWord) bazen arka plan görüntülerinin bölümleri arasında görünür sınırlar oluşturur , görüntü kenar yumuşatma (anti-aliasing) tekniklerinin Acrobat Reader'dan farklı olmasına neden olur. Dışa aktarılan belge, aynı arka plan görüntülerinin bölümleri arasında bu tür görünür sınırlar içeriyor gibi görünüyorsa, bundan kurtulmak için lütfen bu ayarı kullanmayı deneyin istenmeyen etki. DİKKAT! Bu kalite optimizasyonu genellikle dönüşümü yavaşlatır, bu nedenle, lütfen bu seçeneği yalnızca gerçekten gerekli olduğunda kullanın. |

### Ayrıca bakınız

* class [SaveOptions](../saveoptions)
* ad alanı [Aspose.Pdf](../../aspose.pdf)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
