---
title: "Класс TiffOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Plugins.TiffOptions класс. Представляет параметры конвертера Pdf в Tiff для плагина Tiff"
type: docs
weight: 9570
url: /ru/net/aspose.pdf.plugins/tiffoptions/
---
## TiffOptions class

Представляет параметры конвертера Pdf в Tiff для плагина [`Tiff`](../tiff/).

```csharp
public sealed class TiffOptions : PdfToImageOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TiffOptions](tiffoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Brightness](../../aspose.pdf.plugins/tiffoptions/brightness/) { get; set; } | Получает или задает границу значения преобразования цветов в белый и черный. Этот параметр может быть применён с EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle или ColorDepth.Format1bpp == 1 |
| [Compression](../../aspose.pdf.plugins/tiffoptions/compression/) { get; set; } | Получает или задает тип сжатия. |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Получает режим конвертации изображения. |
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | Получает или задает тип координат страницы (Media/Crop‑коробки). Значение CropBox используется по умолчанию. |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | Получает или задает глубину цвета. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Возвращает коллекцию данных плагина [`PdfToImage`](../pdftoimage/). |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | Возвращает название операции. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Получает или задает значение разрешения полученных изображений. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Получает или задает список страниц для процесса. |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | Получает и задает флаг, позволяющий сохранять все страницы в один многостраничный tiff. |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | Получает или задает тип формы. |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | Получает или задает значение, указывающее, следует ли пропускать пустые страницы. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Добавляет новый источник данных в коллекцию данных плагина [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Устанавливает новый источник данных для сохранения. Может быть только . Если вы хотите сохранять изображения в потоки памяти, передайте null в качестве параметра. |

### См. также

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


