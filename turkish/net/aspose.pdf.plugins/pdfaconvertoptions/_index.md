---
title: Class PdfAConvertOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfAConvertOptions sınıfı. PDF belgelerini PdfAConverter eklentisi ile PDF/A formatına dönüştürmek için seçenekleri temsil eder.
type: docs
weight: 8990
url: /tr/net/aspose.pdf.plugins/pdfaconvertoptions/
---
## PdfAConvertOptions Sınıfı

PDF belgelerini [`PdfAConverter`](../pdfaconverter/) eklentisi ile PDF/A formatına dönüştürmek için seçenekleri temsil eder.

```csharp
public sealed class PdfAConvertOptions : PdfAOptionsBase
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PdfAConvertOptions](pdfaconvertoptions/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | PDF/A dönüştürme sürecinde metin hizalamasını korumak için ek araçların gerekli olup olmadığını belirten bir değeri alır veya ayarlar. |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | Dönüştürülemeyen nesneler için alınacak eylemi alır veya ayarlar. |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | PDF/A dönüştürme sürecinde çıktı dosya boyutunu en aza indirmek için fontları kaldırma stratejisini alır veya ayarlar. |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | Belgeye gömülemeyen fontları işlemek için seçenekleri alır. |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | PDF/A dönüştürme için varsayılan profilin yerine kullanılacak ICC (Uluslararası Renk Konsorsiyumu) profilinin dosya adını alır veya ayarlar. |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | Veri kaynakları koleksiyonunu alır. |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | PDF/A dönüştürme sürecinde düşük bellek modunun etkin olup olmadığını belirten bir değeri alır veya ayarlar. |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | Günlük çıktısı için veri kaynağını alır veya ayarlar. |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | Kaynak PDF belgesinin PDF spesifikasyonuna uymadığı durumlarda PDF/A dönüşümünü kontrol eden bayrakları alır. |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | PDF/A dönüştürme sürecinde dosya boyutunu azaltmaya çalışılıp çalışılmayacağını belirten bir değeri alır veya ayarlar. |
| [Outputs](../../aspose.pdf.plugins/pdfaconvertoptions/outputs/) { get; } | İşlem sonuçlarını kaydetmek için eklenen hedeflerin (dosya veya akış veri kaynakları) koleksiyonunu alır. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | Doğrulama veya dönüştürme için kullanılacak PDF/A standardının sürümünü alır veya ayarlar. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | PDF belgesindeki Özel Kullanım Alanı (PUA) sembollerini işleme stratejisini alır veya ayarlar. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | Yumuşak maskelere sahip görüntülerin dönüştürülmesi sırasında alınacak eylemi alır veya ayarlar. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | PDF/A formatına dönüştürme sırasında sembolik fontların kodlanması için stratejiyi alır veya ayarlar. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | PDF/A dönüştürme sürecinde Unicode sembollerine bağlı olmayan ToUnicode CMap tablolarını işleme kurallarını alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | Koleksiyona yeni veri kaynağı ekler. |
| [AddOutput](../../aspose.pdf.plugins/pdfaconvertoptions/addoutput/)(IDataSource) | Yeni sonuç kaydetme hedefi ekler. |

### Ayrıca Bakınız

* sınıf [PdfAOptionsBase](../pdfaoptionsbase/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)