---
title: Class TiffOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TiffOptions sınıfı. Tiff eklentisi için Pdf'den Tiff dönüştürücü seçeneklerini temsil eder
type: docs
weight: 9420
url: /tr/net/aspose.pdf.plugins/tiffoptions/
---
## TiffOptions sınıfı

Tiff eklentisi için Pdf'den Tiff dönüştürücü seçeneklerini temsil eder.

```csharp
public sealed class TiffOptions : PdfToImageOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [TiffOptions](tiffoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Brightness](../../aspose.pdf.plugins/tiffoptions/brightness/) { get; set; } | Beyaz ve siyah renklerin dönüşümünde bir değer sınırını alır veya ayarlar. Bu parametre EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle veya ColorDepth.Format1bpp == 1 ile uygulanabilir. |
| [Compression](../../aspose.pdf.plugins/tiffoptions/compression/) { get; set; } | Sıkıştırma türünü alır veya ayarlar. |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Görüntü dönüştürme modunu alır. |
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | Sayfa koordinat türünü alır veya ayarlar (Medya/Kırpma kutuları). Varsayılan olarak CropBox değeri kullanılır. |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | Renk derinliğini alır veya ayarlar. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | [`PdfToImage`](../pdftoimage/) eklentisi veri koleksiyonunu döndürür. |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | İşlemin adını döndürür. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Elde edilen görüntülerin çözünürlük değerini alır veya ayarlar. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | İşlem için bir sayfa listesi alır veya ayarlar. |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | Tüm sayfaları tek bir çok sayfalı tiff olarak kaydetmeye izin veren bayrağı alır ve ayarlar. |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | Şekil türünü alır veya ayarlar. |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | Boş sayfaların atılıp atılmayacağını belirten bir değeri alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | [`PdfToImage`](../pdftoimage/) eklentisi veri koleksiyonuna yeni bir veri kaynağı ekler. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Yeni kaydetme veri kaynağını ayarlar. Sadece bir . olabilir. Eğer görüntüleri bellek akışlarına kaydetmek istiyorsanız, parametre olarak null geçin. |

### Ayrıca Bakınız

* sınıf [PdfToImageOptions](../pdftoimageoptions/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)