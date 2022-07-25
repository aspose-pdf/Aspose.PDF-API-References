---
title: PdfConverter
second_title: Aspose.PDF for .NET API Referansı
description: Artık BMP JPEG PNG ve TIFFi destekleyen bir pdf dosyasının her sayfasını resimlere dönüştürmek için bir sınıfı temsil eder. PDFlerde desteklenen içerik resimler form yorum.
type: docs
weight: 2450
url: /tr/net/aspose.pdf.facades/pdfconverter/
---
## PdfConverter class

Artık BMP, JPEG, PNG ve TIFF'i destekleyen bir pdf dosyasının her sayfasını resimlere dönüştürmek için bir sınıfı temsil eder. PDF'lerde desteklenen içerik: resimler, form, yorum.

```csharp
public sealed class PdfConverter : Facade
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfConverter](pdfconverter#constructor)() | Yeniyi başlatır[`PdfConverter`](../pdfconverter) nesne. |
| [PdfConverter](pdfconverter#constructor_1)(Document) | Yeniyi başlatır[`PdfConverter`](../pdfconverter) temelinde nesne*document* . |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype) { get; set; } | Sayfa koordinat türünü alır veya ayarlar (Medya/Kırpma kutuları). CropBox değeri varsayılan olarak kullanılır. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Üzerinde çalıştığı belge cephesini alır. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage) { get; set; } | Dönüştürmek istediğiniz son konumu alır veya ayarlar. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode) { get; set; } | Form sunum modunu alır veya ayarlar. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount) { get; } | Sayfa sayısını alır. |
| [Password](../../aspose.pdf.facades/pdfconverter/password) { get; set; } | OwnerPassword belgesini alır veya ayarlar. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions) { get; set; } | Oluşturma seçeneklerini alır veya ayarlar. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution) { get; set; } | Dönüştürme sırasında çözünürlüğü alır veya ayarlar. Daha yüksek çözünürlük, daha yavaş dönüştürme hızı. Varsayılan değer 150. 'dir |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage) { get; set; } | Dönüştürmek istediğiniz başlangıç konumunu alır veya ayarlar. Minimum değer 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword) { get; set; } | UserPassword belgesini alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Cepheyi başlatır. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf#bindpdf_1)(Stream) | convert. için bir Pdf Akışı bağlar |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf#bindpdf_2)(string) | Dönüştürmek için bir Pdf dosyasını bağlar. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close)() | PdfConverter örneğini kapatın ve kaynakları serbest bırakın. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Cepheyi ortadan kaldırır. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert)() | Bir pdf belgesini resimlere dönüştürmek için bazı başlangıç çalışmaları yapın. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage)(Stream) | Görüntüyü varsayılan görüntü biçimiyle akışa kaydeder - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_9)(string) | Görüntüyü varsayılan görüntü biçimiyle dosyaya kaydeder - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_4)(Stream, ImageFormat) | Görüntüyü, verilen görüntü biçimiyle akışa kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_1)(Stream, PageSize) | Görüntüyü verilen sayfa boyutuyla akışa kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_13)(string, ImageFormat) | Görüntüyü verilen görüntü biçimiyle dosyaya kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_10)(string, PageSize) | Görüntüyü belirtilen sayfa boyutu ve varsayılan görüntü biçimiyle dosyaya kaydeder - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_6)(Stream, ImageFormat, int) | Görüntüyü, verilen görüntü formatı ve kalitesiyle akışa kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_2)(Stream, PageSize, ImageFormat) | Görüntüyü verilen sayfa boyutuyla akışa kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_15)(string, ImageFormat, int) | Görüntüyü, verilen görüntü formatı ve kalitesiyle dosyaya kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_11)(string, PageSize, ImageFormat) | Görüntüyü belirtilen sayfa boyutu ve görüntü biçimiyle dosyaya kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_7)(Stream, ImageFormat, int, int) | Görüntü formatı, boyutu ve kalitesi ile akış için görüntüyü kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_3)(Stream, PageSize, ImageFormat, int) | Görüntüyü belirtilen sayfa boyutu, görüntü formatı ve kalitesiyle akışa kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_16)(string, ImageFormat, int, int) | Görüntüyü verilen görüntü formatı ve boyutlarıyla dosyaya kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_12)(string, PageSize, ImageFormat, int) | Görüntüyü belirtilen sayfa boyutu, görüntü formatı ve kalitesiyle dosyaya kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_5)(Stream, ImageFormat, double, double, int) | Görüntü formatı, boyutu ve kalitesi ile akış için görüntüyü kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_8)(Stream, ImageFormat, int, int, int) | Verilen görüntü formatı, boyutları ve kalitesi ile görüntüyü akışa kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_14)(string, ImageFormat, double, double, int) | Görüntüyü, verilen görüntü formatı, görüntü boyutu ve kalitesiyle dosyaya kaydeder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_17)(string, ImageFormat, int, int, int) | Görüntüyü verilen görüntü formatı, boyutları ve kalitesiyle dosyaya kaydeder. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage)() | Pdf dosyasında daha fazla resim olup olmadığını belirtir. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff)(Stream) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_10)(string) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_1)(Stream, CompressionType) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_4)(Stream, PageSize) | Bir pdf belgesinin her sayfasını sayfa boyutuna sahip görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_2)(Stream, TiffSettings) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_11)(string, CompressionType) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_14)(string, PageSize) | Bir pdf belgesinin her sayfasını sayfa boyutuna sahip görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_12)(string, TiffSettings) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_6)(Stream, int, int) | Bir pdf belgesinin her sayfasını boyutlara sahip görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_5)(Stream, PageSize, TiffSettings) | Bir pdf belgesinin her sayfasını sayfa boyutuna sahip görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_16)(string, int, int) | Bir pdf belgesinin her sayfasını boyutlu görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_15)(string, PageSize, TiffSettings) | Bir pdf belgesinin her sayfasını sayfa boyutuna sahip görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_7)(Stream, int, int, CompressionType) | Bir pdf belgesinin her sayfasını boyutlara sahip görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_8)(Stream, int, int, TiffSettings) | Bir pdf belgesinin her sayfasını boyutlara sahip görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_17)(string, int, int, CompressionType) | Bir pdf belgesinin her sayfasını boyutlu görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_18)(string, int, int, TiffSettings) | Bir pdf belgesinin her sayfasını boyutlu görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | Bir pdf belgesinin her sayfasını boyutlara sahip görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | Bir pdf belgesinin her sayfasını boyutlu görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf)(Stream) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_3)(string) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF dosyasına kaydeder. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_1)(Stream, PageSize) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_4)(string, PageSize) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF dosyasına kaydeder. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_2)(Stream, int, int) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_5)(string, int, int) | Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF dosyasına kaydeder. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | Görüntü akışlarının listesini tek bir görüntü akışı olarak birleştirir. Varsayılan olarak Jpeg olarak kodlanmış, desteklenmeyen biçim çıkış akışının kullanılması durumunda, Png/jpg/tiff çıkış biçimleri desteklenir. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff)(List&lt;Stream&gt;) | tiff akışlarının listesini tek bir çoklu çerçeve tiff akışı olarak birleştirir. |

### Ayrıca bakınız

* class [Facade](../facade)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
