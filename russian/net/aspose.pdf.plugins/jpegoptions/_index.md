---
title: "Класс JpegOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Plugins.JpegOptions class. Представляет параметры конвертера Pdf в Jpeg для плагина Jpeg"
type: docs
weight: 9050
url: /ru/net/aspose.pdf.plugins/jpegoptions/
---
## JpegOptions class

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
| override [OperationName](../../aspose.pdf.plugins/jpegoptions/operationname/) { get; } | Возвращает название операции. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Получает или задает значение разрешения полученных изображений. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Получает или задает список страниц для процесса. |
| [Quality](../../aspose.pdf.plugins/jpegoptions/quality/) { get; set; } | Получает и задает качество Jpeg |

## Методы

| Имя | Описание |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Добавляет новый источник данных в коллекцию данных плагина [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Устанавливает новый источник данных для сохранения. Может быть только . Если вы хотите сохранять изображения в потоки памяти, передайте null в качестве параметра. |

### См. также

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


