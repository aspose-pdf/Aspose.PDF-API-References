---
title: "Класс Aspose::Pdf::LowCode::TiffOptions"
linktitle: "TiffOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::LowCode::TiffOptions. Представляет параметры конвертера Pdf в Tiff для плагина Tiff на C++."
type: docs
weight: 8900
url: /ru/cpp/aspose.pdf.lowcode/tiffoptions/
---
## TiffOptions class


Представляет параметры конвертера [Pdf](../../aspose.pdf/) в [Tiff](../tiff/) для плагина [Tiff](../tiff/).

```cpp
class TiffOptions : public Aspose::Pdf::LowCode::PdfToImageOptions
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Brightness](./get_brightness/)() | Получает или задает границу значений преобразования цветов в белый и черный. Этот параметр может использоваться с EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle или ColorDepth.Format1bpp == 1. |
| [get_Compression](./get_compression/)() | Возвращает тип сжатия. |
| [get_CoordinateType](./get_coordinatetype/)() | Получает или задает тип координат страницы (Media/Crop коробки). Значение CropBox используется по умолчанию. |
| [get_Depth](./get_depth/)() | Возвращает глубину цвета. |
| [get_OperationName](./get_operationname/)() override | Возвращает имя операции. |
| [get_SaveAsMultiPageTiff](./get_saveasmultipagetiff/)() const | Получает и задает флаг, позволяющий сохранять все страницы в один многостраничный tiff. |
| [get_Shape](./get_shape/)() | Получает тип фигуры. |
| [get_SkipBlankPages](./get_skipblankpages/)() | Получает значение, указывающее, следует ли пропускать пустые страницы. |
| [set_Brightness](./set_brightness/)(float) | Получает или задает границу значений преобразования цветов в белый и черный. Этот параметр может использоваться с EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle или ColorDepth.Format1bpp == 1. |
| [set_Compression](./set_compression/)(Devices::CompressionType) | Устанавливает тип сжатия. |
| [set_CoordinateType](./set_coordinatetype/)(PageCoordinateType) | Получает или задает тип координат страницы (Media/Crop коробки). Значение CropBox используется по умолчанию. |
| [set_Depth](./set_depth/)(Devices::ColorDepth) | Устанавливает глубину цвета. |
| [set_SaveAsMultiPageTiff](./set_saveasmultipagetiff/)(bool) | Получает и задает флаг, позволяющий сохранять все страницы в один многостраничный tiff. |
| [set_Shape](./set_shape/)(Devices::ShapeType) | Устанавливает тип фигуры. |
| [set_SkipBlankPages](./set_skipblankpages/)(bool) | Устанавливает значение, указывающее, следует ли пропускать пустые страницы. |
| [TiffOptions](./tiffoptions/)() | Инициализирует новый экземпляр объекта [TiffOptions](./). |
## См. также

* Class [PdfToImageOptions](../pdftoimageoptions/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
