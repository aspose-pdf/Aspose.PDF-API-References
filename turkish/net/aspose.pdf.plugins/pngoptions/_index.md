---
title: Class PngOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PngOptions sınıfı. Png eklentisi için Pdf'den Png'ye dönüştürücü seçeneklerini temsil eder
type: docs
weight: 9180
url: /tr/net/aspose.pdf.plugins/pngoptions/
---
## PngOptions sınıfı

Png eklentisi için Pdf'den Png'ye dönüştürücü seçeneklerini temsil eder.

```csharp
public sealed class PngOptions : PdfToImageOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PngOptions](pngoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Görüntü dönüştürme modunu alır. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | [`PdfToImage`](../pdftoimage/) eklentisi veri koleksiyonunu döndürür. |
| override [OperationName](../../aspose.pdf.plugins/pngoptions/operationname/) { get; } | İşlemin adını döndürür. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Ortaya çıkan görüntülerin çözünürlük değerini alır veya ayarlar. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | İşlem için bir sayfa listesi alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Yeni veri kaynağını [`PdfToImage`](../pdftoimage/) eklentisi veri koleksiyonuna ekler. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Yeni kaydetme veri kaynağını ayarlar. Sadece bir . olabilir. Eğer görüntüleri bellek akışlarına kaydetmek istiyorsanız, parametre olarak null geçin. |

### Ayrıca Bakınız

* sınıf [PdfToImageOptions](../pdftoimageoptions/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)