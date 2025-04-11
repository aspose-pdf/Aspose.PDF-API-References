---
title: Class PdfToImageOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfToImageOptions sınıfı. PdfToImage eklentisi için seçenekleri temsil eder
type: docs
weight: 9130
url: /tr/net/aspose.pdf.plugins/pdftoimageoptions/
---
## PdfToImageOptions Sınıfı

[`PdfToImage`](../pdftoimage/) eklentisi için seçenekleri temsil eder.

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Görüntü dönüştürme modunu alır. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | [`PdfToImage`](../pdftoimage/) eklentisi veri koleksiyonunu döndürür. |
| virtual [OperationName](../../aspose.pdf.plugins/pdftoimageoptions/operationname/) { get; } | İşlem adını döndürür. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Elde edilen görüntülerin çözünürlük değerini alır veya ayarlar. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | İşlem için sayfa listesini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Yeni veri kaynağını [`PdfToImage`](../pdftoimage/) eklentisi veri koleksiyonuna ekler. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Yeni kaydetme veri kaynağını ayarlar. Sadece bir . olabilir. Görüntüleri bellek akışlarına kaydetmek istiyorsanız, parametre olarak null geçin. |

## Diğer Üyeler

| Ad | Açıklama |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.plugins/pdftoimageoptions.imageconversionmode) | PDF belgesinden Jpeg görüntüsüne dönüştürme sırasında kullanılabilecek farklı modları tanımlar. [`JpegOptions`](../jpegoptions/) sınıfına bakın. |

## Notlar

PdfImageOptions sınıfı, giriş PDF belgelerini temsil eden veri (dosyalar, akışlar) eklemek için temel işlevler içerir.

### Ayrıca Bakınız

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)