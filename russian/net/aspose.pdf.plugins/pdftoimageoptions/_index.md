---
title: Class PdfToImageOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.PdfToImageOptions. Представляет параметры для плагина PdfToImage
type: docs
weight: 9130
url: /ru/net/aspose.pdf.plugins/pdftoimageoptions/
---
## PdfToImageOptions class

Представляет параметры для плагина [`PdfToImage`](../pdftoimage/).

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## Properties

| Name | Description |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Получает режим конвертации изображений. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Возвращает коллекцию данных плагина [`PdfToImage`](../pdftoimage/). |
| virtual [OperationName](../../aspose.pdf.plugins/pdftoimageoptions/operationname/) { get; } | Возвращает имя операции. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Получает или устанавливает значение разрешения полученных изображений. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Получает или устанавливает список страниц для процесса. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Добавляет новый источник данных в коллекцию данных плагина [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Устанавливает новый источник данных для сохранения. Может быть только . Если вы хотите сохранить изображения в потоках памяти, передайте null в качестве параметра. |

## Other Members

| Name | Description |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.plugins/pdftoimageoptions.imageconversionmode) | Определяет различные режимы, которые могут быть использованы при конвертации из PDF-документа в изображение Jpeg. См. класс [`JpegOptions`](../jpegoptions/). |

## Remarks

Класс PdfImageOptions содержит базовые функции для добавления данных (файлов, потоков), представляющих входные PDF-документы.

### See Also

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)