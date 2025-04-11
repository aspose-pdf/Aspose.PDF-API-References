---
title: Class JpegOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.JpegOptions. Представляет параметры конвертера Pdf в Jpeg для плагина Jpeg
type: docs
weight: 8920
url: /ru/net/aspose.pdf.plugins/jpegoptions/
---
## Класс JpegOptions

Представляет параметры конвертера Pdf в Jpeg для плагина [`Jpeg`](../jpeg/).

```csharp
public sealed class JpegOptions : PdfToImageOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [JpegOptions](jpegoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Получает режим конвертации изображения. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Возвращает коллекцию данных плагина [`PdfToImage`](../pdftoimage/). |
| override [OperationName](../../aspose.pdf.plugins/jpegoptions/operationname/) { get; } | Возвращает имя операции. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Получает или устанавливает значение разрешения результирующих изображений. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Получает или устанавливает список страниц для процесса. |
| [Quality](../../aspose.pdf.plugins/jpegoptions/quality/) { get; set; } | Получает и устанавливает качество Jpeg |

## Методы

| Имя | Описание |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Добавляет новый источник данных в коллекцию данных плагина [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Устанавливает новый источник данных для сохранения. Может быть только . Если вы хотите сохранить изображения в потоках памяти, передайте null в качестве параметра. |

### См. также

* класс [PdfToImageOptions](../pdftoimageoptions/)
* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)