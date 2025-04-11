---
title: Class PdfFormatConversionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfFormatConversionOptions sınıfı. PDF belgesini dönüştürmek için seçenekler kümesini temsil eder
type: docs
weight: 8380
url: /tr/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions Sınıfı

PDF belgesini dönüştürmek için seçenekler kümesini temsil eder

```csharp
public class PdfFormatConversionOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor)(PdfFormat) | Yapıcı |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_1)(PdfFormat, ConvertErrorAction) | Yapıcı |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_3)(string, PdfFormat) | Yapıcı |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | Yapıcı |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_4)(string, PdfFormat, ConvertErrorAction) | Yapıcı |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Yapıcı |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default/) { get; } | Varsayılan parametrelerle PdfFormatConversionOptions nesnesini alır |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | Bu bayrak, dönüştürülen belgede metin hizalamasını kontrol eder. Varsayılan olarak belge dönüşümü metin hizalamasını etkilemez ve metni olduğu gibi bırakır. Ancak bazı durumlarda yazı tipi değiştirme, dönüştürülen belgede metin üst üste binmesine veya ekstra boşluklara neden olabilir. Bu bayrak ayarlandığında özel hizalama işlemleri gerçekleştirilecektir. Bu bayrak, üst üste binen metin veya ekstra metin boşlukları olan belgeler için yalnızca ayarlanmalıdır çünkü bu bayrağın kullanılması performansı düşürebilir ve bazı durumlarda metin içeriğini bozabilir. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | Yumuşak maske ile görüntüler için eylem. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | Dönüştürülemeyen nesneler için eylem |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | Gereksiz yazı tiplerini hariç tutma ve belge dosya boyutunu azaltma stratejisi(leri). Bu parametre yalnızca [`OptimizeFileSize`](./optimizefilesize/) bayrağı true olarak ayarlandığında anlam kazanır. Varsayılan olarak SubsetFonts ve RemoveDuplicatedFonts stratejilerinin kombinasyonu kullanılır. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | PDF belgesine bazı yazı tiplerini gömmenin mümkün olmadığı durumlar için seçenekler. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | PDF formatı. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | ICC profil adının dosya adını alır veya ayarlar. Null durumunda varsayılan ICC profili kullanılır. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | Görüntü akışlarının asenkron modda çalıştırılmasını alır/ayarlar. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | Düşük bellek dönüşüm modu etkin mi |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | PDF 2.0'a dönüştürüldüğünde Info'dan Metadata'ya veri geçip geçmeyeceğini alır veya ayarlar. Varsayılan olarak true. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | Yorumların saklanacağı dosyanın yolu. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | Yorumların saklanacağı akış. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | Kaynak belgenin PDF/A spesifikasyonuna uymadığı durumlar için PDF/A dönüşüm sürecini kontrol etmek için bayrakları tutar. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | Bu özellik dış özellik. Son PDF/A dönüşümünde bilgisayarda bulunmayan tüm yazı tiplerini (yazı tipi adlarını) tutar. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | PDF/A belgesinin azaltılmış dosya boyutuyla elde edilmesini sağlayan özel dönüşüm modunu etkinleştiren/devre dışı bırakan bir bayrağı alır veya ayarlar. Şu anda bu bayrak, PDF belgesinde kullanılan yazı tiplerinin optimizasyonunu etkiler, muhtemelen gelecekte bu bayrak, grafik gibi diğer veri yapıları için optimizasyonu açmak için de kullanılacaktır. Bu bayrağın ve modun seti dosya boyutunu önemli ölçüde azaltabilir ancak aynı zamanda dönüşüm performansını da önemli ölçüde düşürebilir. |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | PDF format dönüşümü için [`OutputIntent`](../outputintent/) alır veya ayarlar. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | Unicode Özel Kullanım Alanından (PUA) sembolleri işlemek için strateji. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | Sembolik TrueType yazı tipinin birden fazla kodlama alt tablosu varsa sembolik yazı tipleri için kodlama verilerini kopyalamak için strateji. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | Maske ile görüntü nesneleri için eylem |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | Unicode eşleştirme ile ilgili sorunları çözmek için kurallar. Null olabilir. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | Metni hizalamak için strateji. Bu parametre yalnızca [`AlignText`](./aligntext/) bayrağı true olarak ayarlandığında anlam kazanır. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)