---
title: "Класс PdfToImageOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Plugins.PdfToImageOptions. Представляет параметры для плагина PdfToImage"
type: docs
weight: 9280
url: /ru/net/aspose.pdf.plugins/pdftoimageoptions/
---
## PdfToImageOptions class

Представляет параметры для плагина [`PdfToImage`](../pdftoimage/).

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Получает режим конвертации изображения. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Возвращает коллекцию данных плагина [`PdfToImage`](../pdftoimage/). |
| virtual [OperationName](../../aspose.pdf.plugins/pdftoimageoptions/operationname/) { get; } | Возвращает имя операции. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Получает или задает значение разрешения полученных изображений. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Получает или задает список страниц для процесса. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Добавляет новый источник данных в коллекцию данных плагина [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Устанавливает новый источник данных для сохранения. Может быть только . Если вы хотите сохранять изображения в потоки памяти, передайте null в качестве параметра. |

## Другие члены

| Имя | Описание |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.plugins/pdftoimageoptions.imageconversionmode) | Определяет различные режимы, которые могут использоваться при конвертации PDF‑документа в изображение Jpeg. Смотрите класс [`JpegOptions`](../jpegoptions/). |

## Примечания

Класс PdfImageOptions содержит базовые функции для добавления данных (файлов, потоков), представляющих входные PDF‑документы.

### См. также

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


