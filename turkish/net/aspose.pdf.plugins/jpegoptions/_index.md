---
title: Class JpegOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.JpegOptions sınıfı. Jpeg eklentisi için Pdf'den Jpeg'e dönüştürücü seçeneklerini temsil eder
type: docs
weight: 8920
url: /tr/net/aspose.pdf.plugins/jpegoptions/
---
## JpegOptions sınıfı

Jpeg eklentisi için Pdf'den Jpeg'e dönüştürücü seçeneklerini temsil eder.

```csharp
public sealed class JpegOptions : PdfToImageOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [JpegOptions](jpegoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Görüntü dönüştürme modunu alır. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | [`PdfToImage`](../pdftoimage/) eklentisi veri koleksiyonunu döndürür. |
| override [OperationName](../../aspose.pdf.plugins/jpegoptions/operationname/) { get; } | İşlemin adını döndürür. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Ortaya çıkan görüntülerin çözünürlük değerini alır veya ayarlar. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | İşlem için sayfa listesini alır veya ayarlar. |
| [Quality](../../aspose.pdf.plugins/jpegoptions/quality/) { get; set; } | Jpeg kalitesini alır ve ayarlar |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Yeni veri kaynağını [`PdfToImage`](../pdftoimage/) eklentisi veri koleksiyonuna ekler. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Yeni kaydetme veri kaynağını ayarlar. Sadece bir . olabilir. Eğer görüntüleri bellek akışlarına kaydetmek istiyorsanız, parametre olarak null geçin. |

### Ayrıca Bakınız

* sınıf [PdfToImageOptions](../pdftoimageoptions/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)