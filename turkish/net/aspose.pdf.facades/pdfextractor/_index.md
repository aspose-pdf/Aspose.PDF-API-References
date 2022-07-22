---
title: PdfExtractor
second_title: Aspose.PDF for .NET API Referansı
description: PDF belgesinden resim ve metin çıkarmak için sınıf.
type: docs
weight: 2460
url: /tr/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

PDF belgesinden resim ve metin çıkarmak için sınıf.

```csharp
public sealed class PdfExtractor : Facade
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfExtractor](pdfextractor#constructor)() | Yeniyi başlatır[`PdfExtractor`](../pdfextractor) nesne. |
| [PdfExtractor](pdfextractor#constructor_1)(Document) | Yeniyi başlatır[`PdfExtractor`](../pdfextractor) temelinde nesne*document* . |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Üzerinde çalıştığı belge cephesini alır. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage) { get; set; } | Çıkarma işleminin gerçekleştirileceği sayfa aralığındaki bitiş sayfasını alır veya ayarlar. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode) { get; set; } | Görüntü çıkarma işlemi için modu ayarlar. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode) { get; set; } | Metin çıkarma sonucunun modunu ayarlar. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi) { get; } | Metinde İbranice veya Arapça semboller olduğunda doğrudur. Bu durum özellikle dikkate alınmalıdır, çünkü dize işlevleri davranışlarını değiştirir ve işlem metnini sağdan sola başlatır ( sayıları ve diğer metin olmayan karakterler hariç). |
| [Password](../../aspose.pdf.facades/pdfextractor/password) { get; set; } | Girdi dosyasının parolasını alır veya ayarlar. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution) { get; set; } | Çıkarılan görüntüler için çözünürlüğü ayarlar veya alır. Varsayılan değer 150'dir. Çözünürlük değeri daha yüksek olan görüntüler daha nettir. Ancak çözünürlük değerini artırmak, görüntüleri çıkarmak için gereken süreyi ve belleği artırır. Genellikle net görüntü elde etmek için yeterlidir. çözünürlüğü 150 veya 300. olarak ayarlamak için |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage) { get; set; } | Çıkarma işleminin gerçekleştirileceği sayfa aralığındaki başlangıç sayfasını alır veya ayarlar. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions) { get; set; } | Metin arama seçeneklerini alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Cepheyi başlatır. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf#bindpdf_1)(Stream) | Akıştan PDF belgesini bağlar. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf#bindpdf_2)(string) | Giriş PDF dosyasını bağla. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Aspose.Pdf.Document'ı bir cepheye bağlı olarak imha eder. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Cepheyi ortadan kaldırır. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment#extractattachment)() | Bir Pdf belgesinden ekleri çıkarır. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment#extractattachment_1)(string) | Eki, ek adına göre PDF dosyasına çıkarır. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage)() | PDF dosyasından görüntüleri çıkarın. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext#extracttext)() | Unicode kodlamasını kullanarak bir Pdf belgesinden metin çıkarır. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext#extracttext_1)(Encoding) | Belirtilen kodlamayı kullanarak bir Pdf belgesinden metin çıkarır. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment#getattachment)() | Tüm ek dosyasını akışlara kaydeder. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment#getattachment_1)(string) | Eki dosyada saklar. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo)() | Eklerin listesini alır. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames)() | PDF dosyasındaki eklerin listesini döndürür. Not: Bu yöntemi kullanmadan önce ExtractAttachments çağrılmalıdır. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage)(Stream) | PDF dosyasından sonraki görüntüyü alın ve akışta depolayın. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_2)(string) | PDF belgesinden sonraki görüntüyü alır. Not: Bu yöntem kullanılmadan önce ExtractImage çağrılmalıdır. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_1)(Stream, ImageFormat) | PDF dosyasından sonraki görüntüyü alın ve verilen görüntü formatı ile akışta saklar. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_3)(string, ImageFormat) | Verilen görüntü biçimiyle PDF belgesinden sonraki görüntüyü alır. Not: Bu yöntem kullanılmadan önce ExtractImage çağrılmalıdır. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext#getnextpagetext)(Stream) | Bir sayfanın metnini akışa kaydeder. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext#getnextpagetext_1)(string) | Bir sayfanın metnini dosyaya kaydeder. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext)(Stream) | Metni akışa kaydeder. Ayrıca bakınız:[`ExtractText`](./extracttext) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext_2)(string) | Metni dosyaya kaydeder. Ayrıca bakınız:[`ExtractText`](./extracttext) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext_1)(Stream, bool) | Metni akışa kaydeder. Ayrıca bakınız:[`ExtractText`](./extracttext) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage)() | PDF belgesinde daha fazla görüntünün erişilebilir olup olmadığını kontrol eder. Not: Bu yöntem kullanılmadan önce ExtractImage çağrılmalıdır. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext)() | Daha fazla metin alıp alamayacağını belirtir. |

### Ayrıca bakınız

* class [Facade](../facade)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
