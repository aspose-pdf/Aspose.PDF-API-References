---
title: Class PdfAOptionsBase
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfAOptionsBase sınıfı. PdfAConverter eklentisi seçenekleri için temel sınıfı temsil eder. Bu sınıf, PDF/A dönüşüm ve doğrulama sürecini yapılandırmak için özellikler ve yöntemler sağlar.
type: docs
weight: 9010
url: /tr/net/aspose.pdf.plugins/pdfaoptionsbase/
---
## PdfAOptionsBase Sınıfı

[`PdfAConverter`](../pdfaconverter/) eklentisi seçenekleri için temel sınıfı temsil eder. Bu sınıf, PDF/A dönüşüm ve doğrulama sürecini yapılandırmak için özellikler ve yöntemler sağlar.

```csharp
public abstract class PdfAOptionsBase : IPluginOptions
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | PDF/A dönüşüm süreci sırasında metin hizalamasını korumak için ek araçların gerekli olup olmadığını belirten bir değeri alır veya ayarlar. |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | Dönüştürülemeyen nesneler için alınacak eylemi alır veya ayarlar. |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | PDF/A dönüşüm süreci sırasında çıktı dosyası boyutunu en aza indirmek için fontları kaldırma stratejisini alır veya ayarlar. |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | Belgeye gömülemeyen fontları işlemek için seçenekleri alır. |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | PDF/A dönüşümünde kullanılacak ICC (Uluslararası Renk Konsorsiyumu) profilinin dosya adını alır veya ayarlar. |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | Veri kaynakları koleksiyonunu alır |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | PDF/A dönüşüm süreci sırasında düşük bellek modunun etkin olup olmadığını belirten bir değeri alır veya ayarlar. |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | Günlük çıktısı için veri kaynağını alır veya ayarlar. |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | Kaynak PDF belgesinin PDF spesifikasyonuna uymadığı durumlarda PDF/A dönüşümünü kontrol eden bayrakları alır. |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | PDF/A dönüşüm süreci sırasında dosya boyutunu azaltmaya çalışılıp çalışılmayacağını belirten bir değeri alır veya ayarlar. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | Doğrulama veya dönüşüm için kullanılacak PDF/A standardının sürümünü alır veya ayarlar. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | PDF belgesindeki Özel Kullanım Alanı (PUA) sembollerini işleme stratejisini alır veya ayarlar. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | Yumuşak maskelere sahip görüntülerin dönüşümü sırasında alınacak eylemi alır veya ayarlar. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | PDF/A formatına dönüştürme sırasında sembolik fontların kodlanması için stratejiyi alır veya ayarlar. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | PDF/A dönüşüm süreci sırasında Unicode sembollerine bağlı olmayan ToUnicode CMap tablolarını işleme kurallarını alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | Koleksiyona yeni bir veri kaynağı ekler |

### Ayrıca Bakınız

* arayüz [IPluginOptions](../ipluginoptions/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)