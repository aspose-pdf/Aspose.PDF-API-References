---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfExtractor sınıfı. PDF belgesinden resim ve metin çıkarmak için sınıf
type: docs
weight: 4450
url: /tr/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor sınıfı

PDF belgesinden resim ve metin çıkarmak için sınıf.

```csharp
public sealed class PdfExtractor : Facade
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PdfExtractor](pdfextractor/#constructor)() | Yeni bir `PdfExtractor` nesnesi başlatır. |
| [PdfExtractor](pdfextractor/#constructor_1)(Document) | *belge* temelinde yeni bir `PdfExtractor` nesnesi başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Üzerinde çalışılan belge yüzeyini alır. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | Çıkarma işleminin gerçekleştirileceği sayfa aralığında son sayfayı alır veya ayarlar. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | Resim çıkarma işlemi için modu ayarlar. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | Metin çıkarma sonucunun modunu ayarlar. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | Metin İbranice veya Arapça semboller içeriyorsa doğrudur. Bu durum özel olarak dikkate alınmalıdır çünkü dize işlevleri davranışlarını değiştirir ve metni sağdan sola işlemeye başlar (sayılar ve diğer metin olmayan karakterler hariç). |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | Giriş dosyasının şifresini alır veya ayarlar. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | Çıkarılan resimler için çözünürlüğü ayarlar veya alır. Varsayılan değer 150'dir. Daha yüksek çözünürlük değerine sahip resimler daha nettir. Ancak çözünürlük değerinin artırılması, resimlerin çıkarılması için gereken zaman ve belleği artırır. Genellikle net bir resim elde etmek için çözünürlüğü 150 veya 300 olarak ayarlamak yeterlidir. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | Çıkarma işleminin gerçekleştirileceği sayfa aralığında başlangıç sayfasını alır veya ayarlar. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | Metin arama seçeneklerini alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Yüzeyi başlatır. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | Akıştan PDF belgesini bağlar. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | Giriş PDF dosyasını bağlar. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Bir yüzeye bağlı Aspose.Pdf.Document'ı yok eder. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Yüzeyi yok eder. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | Bir PDF belgesinden ekleri çıkarır. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | Ek adıyla PDF dosyasına eki çıkarır. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | PDF dosyasından resimleri çıkarır. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | Unicode kodlaması kullanarak bir PDF belgesinden metin çıkarır. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | Belirtilen kodlama kullanarak bir PDF belgesinden metin çıkarır. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | Tüm ek dosyalarını akışlara kaydeder. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | Eki dosyaya kaydeder. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | Eklerin listesini alır. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | PDF dosyasındaki eklerin listesini döndürür. Not: Bu yöntemi kullanmadan önce ExtractAttachments çağrılmalıdır. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | PDF dosyasından bir sonraki resmi alır ve akışa kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | PDF belgesinden bir sonraki resmi alır. Not: Bu yöntemi kullanmadan önce ExtractImage çağrılmalıdır. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | PDF dosyasından bir sonraki resmi alır ve belirtilen resim formatında akışa kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | Belirtilen resim formatında PDF belgesinden bir sonraki resmi alır. Not: Bu yöntemi kullanmadan önce ExtractImage çağrılmalıdır. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | Bir sayfanın metnini akışa kaydeder. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | Bir sayfanın metnini dosyaya kaydeder. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | Metni akışa kaydeder. ayrıca bkz: [`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | Metni dosyaya kaydeder. ayrıca bkz: [`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | Metni akışa kaydeder. ayrıca bkz: [`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | PDF belgesinde daha fazla resim olup olmadığını kontrol eder. Not: Bu yöntemi kullanmadan önce ExtractImage çağrılmalıdır. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | Daha fazla metin alınıp alınamayacağını gösterir. |

### Ayrıca Bakınız

* sınıf [Facade](../facade/)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../)