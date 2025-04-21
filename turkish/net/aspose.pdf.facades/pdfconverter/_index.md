---
title: Class PdfConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfConverter sınıfı. Her sayfayı BMP, JPEG, PNG ve TIFF formatında görüntülere dönüştüren bir sınıfı temsil eder. PDF'lerde desteklenen içerik resimler, form, yorum.
type: docs
weight: 4440
url: /tr/net/aspose.pdf.facades/pdfconverter/
---
## PdfConverter Sınıfı

Her sayfayı BMP, JPEG, PNG ve TIFF formatında görüntülere dönüştüren bir sınıfı temsil eder. PDF'lerde desteklenen içerik: resimler, form, yorum.

```csharp
public sealed class PdfConverter : Facade
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PdfConverter](pdfconverter/#constructor)() | Yeni bir `PdfConverter` nesnesi başlatır. |
| [PdfConverter](pdfconverter/#constructor_1)(Document) | *belge* temelinde yeni bir `PdfConverter` nesnesi başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype/) { get; set; } | Sayfa koordinat türünü alır veya ayarlar (Medya/Kırpma kutuları). Varsayılan olarak CropBox değeri kullanılır. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Üzerinde çalışılan belge yüzeyini alır. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage/) { get; set; } | Dönüştürmek istediğiniz son konumu alır veya ayarlar. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode/) { get; set; } | Form sunum modunu alır veya ayarlar. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount/) { get; } | Sayfa sayısını alır. |
| [Password](../../aspose.pdf.facades/pdfconverter/password/) { get; set; } | Belge OwnerPassword'ını alır veya ayarlar. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions/) { get; set; } | İşleme seçeneklerini alır veya ayarlar. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution/) { get; set; } | Dönüştürme sırasında çözünürlüğü alır veya ayarlar. Daha yüksek çözünürlük, daha yavaş dönüştürme hızı anlamına gelir. Varsayılan değer 150'dir. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage/) { get; set; } | Dönüştürmek istediğiniz başlangıç konumunu alır veya ayarlar. Minimum değer 1'dir. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword/) { get; set; } | Belge UserPassword'ını alır veya ayarlar. |

## Metotlar

| İsim | Açıklama |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Yüzeyi başlatır. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_1)(Stream) | Dönüştürmek için bir Pdf Akışı bağlar. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_2)(string) | Dönüştürmek için bir Pdf dosyası bağlar. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close/)() | PdfConverter örneğini kapatır ve kaynakları serbest bırakır. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Yüzeyi yok eder. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert/)() | Bir pdf belgesini görüntülere dönüştürmek için bazı başlangıç işlemleri yapar. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage)(Stream) | Varsayılan görüntü formatı - jpeg ile akışa görüntü kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_9)(string) | Varsayılan görüntü formatı - jpeg ile dosyaya görüntü kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_4)(Stream, ImageFormat) | Verilen görüntü formatı ile akışa görüntü kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_1)(Stream, PageSize) | Verilen sayfa boyutu ile akışa görüntü kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_13)(string, ImageFormat) | Verilen görüntü formatı ile dosyaya görüntü kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_10)(string, PageSize) | Verilen sayfa boyutu ve varsayılan görüntü formatı - jpeg ile dosyaya görüntü kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_6)(Stream, ImageFormat, int) | Verilen görüntü formatı ve kalite ile akışa görüntü kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_2)(Stream, PageSize, ImageFormat) | Verilen sayfa boyutu ile akışa görüntü kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_15)(string, ImageFormat, int) | Verilen görüntü formatı ve kalite ile dosyaya görüntü kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_11)(string, PageSize, ImageFormat) | Verilen sayfa boyutu ve görüntü formatı ile dosyaya görüntü kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_7)(Stream, ImageFormat, int, int) | Verilen görüntü formatı, boyut ve kalite ile akışa görüntü kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_3)(Stream, PageSize, ImageFormat, int) | Verilen sayfa boyutu, görüntü formatı ve kalite ile akışa görüntü kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_16)(string, ImageFormat, int, int) | Verilen görüntü formatı ve boyutları ile dosyaya görüntü kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_12)(string, PageSize, ImageFormat, int) | Verilen sayfa boyutu, görüntü formatı ve kalite ile dosyaya görüntü kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_5)(Stream, ImageFormat, double, double, int) | Verilen görüntü formatı, boyut ve kalite ile akışa görüntü kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_8)(Stream, ImageFormat, int, int, int) | Verilen görüntü formatı, boyut ve kalite ile akışa görüntü kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_14)(string, ImageFormat, double, double, int) | Verilen görüntü formatı, görüntü boyutu ve kalite ile dosyaya görüntü kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_17)(string, ImageFormat, int, int, int) | Verilen görüntü formatı, boyutları ve kalite ile dosyaya görüntü kaydeder. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage/)() | PDF dosyasının daha fazla görüntüsü olup olmadığını gösterir. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff)(Stream) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_10)(string) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_1)(Stream, CompressionType) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_4)(Stream, PageSize) | Bir pdf belgesinin her sayfasını sayfa boyutu ile görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_2)(Stream, TiffSettings) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_11)(string, CompressionType) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_14)(string, PageSize) | Bir pdf belgesinin her sayfasını sayfa boyutu ile görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_12)(string, TiffSettings) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_6)(Stream, int, int) | Bir pdf belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_5)(Stream, PageSize, TiffSettings) | Bir pdf belgesinin her sayfasını sayfa boyutu ile görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_16)(string, int, int) | Bir pdf belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_15)(string, PageSize, TiffSettings) | Bir pdf belgesinin her sayfasını sayfa boyutu ile görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_7)(Stream, int, int, CompressionType) | Bir pdf belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_8)(Stream, int, int, TiffSettings) | Bir pdf belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_17)(string, int, int, CompressionType) | Bir pdf belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_18)(string, int, int, TiffSettings) | Bir pdf belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | Bir pdf belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | Bir pdf belgesinin her sayfasını boyutlarla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf)(Stream) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_3)(string) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF dosyasına kaydeder. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_1)(Stream, PageSize) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_4)(string, PageSize) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF dosyasına kaydeder. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_2)(Stream, int, int) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_5)(string, int, int) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF dosyasına kaydeder. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages/)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | Bir dizi görüntü akışını tek bir görüntü akışı olarak birleştirir. Png/jpg/tiff çıktı formatları desteklenmektedir, desteklenmeyen format kullanıldığında çıktı akışı varsayılan olarak Jpeg olarak kodlanır. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff/)(List&lt;Stream&gt;) | Bir dizi tiff akışını tek bir çoklu çerçeve tiff akışı olarak birleştirir. |

### Ayrıca Bakınız

* sınıf [Facade](../facade/)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../)