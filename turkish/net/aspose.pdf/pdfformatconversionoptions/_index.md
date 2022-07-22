---
title: PdfFormatConversionOptions
second_title: Aspose.PDF for .NET API Referansı
description:  PDF belgesini dönüştürmek için bir dizi seçeneği temsil eder
type: docs
weight: 6030
url: /tr/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class

, PDF belgesini dönüştürmek için bir dizi seçeneği temsil eder

```csharp
public class PdfFormatConversionOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor)(PdfFormat) | Yapıcı |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_1)(PdfFormat, ConvertErrorAction) | Yapıcı |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_3)(string, PdfFormat) | Yapıcı |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | Yapıcı |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_4)(string, PdfFormat, ConvertErrorAction) | Yapıcı |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Yapıcı |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default) { get; } | Varsayılan parametrelerle PdfFormatConversionOptions nesnesini alır |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext) { get; set; } | Bu işaret, dönüştürülmüş belgedeki metin hizalamasını kontrol eder. Varsayılan olarak belge dönüştürme metin hizalamasını etkilemez ve metni olduğu gibi bırakır. Ancak bazı durumlarda font ikamesi , dönüştürülen belgede metnin çakışmasına veya fazladan boşluklara neden olur. Bu bayrak set olduğunda özel hizalama işlemleri gerçekleştirilecektir. Bu bayrak yalnızca, çakışan metin veya fazladan metin boşlukları ile ilgili sorunları olan ve bu bayrağın kullanılmasının performans azalmasına neden olan ve bazı durumlarda metin içeriğini bozabilecek olan belgeler için ayarlanmalıdır. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction) { get; set; } | Yumuşak maskeli görüntüler için eylem. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction) { get; set; } | Dönüştürülemeyen nesneler için eylem |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy) { get; set; } | Gereksiz yazı tiplerini hariç tutmak ve belge dosya boyutunu küçültmek için strateji(ler). Bu parametre yalnızca bayrak[`OptimizeFileSize`](./optimizefilesize) true olarak ayarlanır. Varsayılan olarak strateji kombinasyonuSubsetFonts and RemoveDuplicatedFonts kullanılır. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions) { get; } | Bazı yazı tiplerini PDF belgesine yerleştirmenin mümkün olmadığı durumlar için seçenekler. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format) { get; set; } | PDF biçimi. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename) { get; set; } | icc profil adının dosya adını alır veya ayarlar. Boş olması durumunda, kullanılan varsayılan icc profili. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode) { get; set; } | Zaman uyumsuz modda görüntü akışlarının çalışmasını alır/ayarlar. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode) { get; set; } | Düşük bellek dönüştürme modu etkin mi |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo) { get; set; } | PDF 2.0'a dönüştürüldüğünde Bilgi'den Meta Verilere veri aktarılıp aktarılmayacağını alır veya ayarlar. Varsayılan olarak doğru. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename) { get; set; } | Yorumların depolanacağı dosyanın yolu. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream) { get; set; } | Yorumların depolanacağı akış. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases) { get; } | Kaynak belgenin PDF/A belirtimine karşılık gelmediği durumlar için PDF/A dönüştürme sürecini kontrol etmek için bayrakları tutar. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts) { get; } | Bu özellik, mülk dışı. Son PDF/A dönüşümünde bilgisayarında bulunmayan tüm yazı tiplerini (yazı tipi adlarını) tutar. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize) { get; set; } | Dosya boyutu küçültülmüş PDF/A belgesi almak için özel dönüştürme modunu etkinleştiren/devre dışı bırakan bir bayrak alır veya ayarlar. Şimdi bu işaret PDF belgesinde kullanılan yazı tiplerinin optimizasyonunu etkiler, muhtemelen gelecekte bu bayrak de kullanılacaktır grafik gibi başka veri yapıları için optimizasyonu açmak için. Bu işaret ve mod kümesi dosya boyutunu önemli ölçüde azaltabilir, ancak aynı zamanda dönüştürme performansını önemli ölçüde azaltabilir. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy) { get; set; } | Unicode Özel Kullanım Alanından (PUA) gelen sembolleri işleme stratejisi. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy) { get; set; } | Sembolik TrueType font 'nin birden fazla kodlama alt tablosu varsa, sembolik fontlar için kodlama verilerini kopyalama stratejisi. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction) { get; set; } | Görüntü maskeli nesneler için eylem |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules) { get; set; } | Unicode eşlemeyle ilgili sorunları çözme kuralları. null. olabilir |

## Alanlar

| İsim | Tanım |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy) | Metni hizalama stratejisi. Bu parametre yalnızca bayrak olduğunda anlamlıdır.[`AlignText`](./aligntext) true. olarak ayarlandı |

### Ayrıca bakınız

* ad alanı [Aspose.Pdf](../../aspose.pdf)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
