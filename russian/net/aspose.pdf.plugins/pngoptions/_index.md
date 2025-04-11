---
title: Class PngOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.PngOptions. Представляет параметры конвертации Pdf в Png для плагина Png
type: docs
weight: 9180
url: /ru/net/aspose.pdf.plugins/pngoptions/
---
## Класс PngOptions

Представляет параметры конвертации Pdf в Png для плагина [`Png`](../png/).

```csharp
public sealed class PngOptions : PdfToImageOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PngOptions](pngoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Получает режим конвертации изображения. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Возвращает коллекцию данных плагина [`PdfToImage`](../pdftoimage/). |
| override [OperationName](../../aspose.pdf.plugins/pngoptions/operationname/) { get; } | Возвращает имя операции. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Получает или устанавливает значение разрешения результирующих изображений. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Получает или устанавливает список страниц для процесса. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Добавляет новый источник данных в коллекцию данных плагина [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Устанавливает новый источник данных для сохранения. Может быть только . Если вы хотите сохранить изображения в потоках памяти, передайте null в качестве параметра. |

### См. также

* класс [PdfToImageOptions](../pdftoimageoptions/)
* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)