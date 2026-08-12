---
title: "Aspose::Pdf::Devices::TiffSettings класс"
linktitle: "TiffSettings"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Devices::TiffSettings класс. Этот класс представляет настройки для импорта pdf в Tiff на C++."
type: docs
weight: 1600
url: /ru/cpp/aspose.pdf.devices/tiffsettings/
---
## TiffSettings class


Этот класс представляет настройки импорта pdf в Tiff.

```cpp
class TiffSettings : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Brightness](./get_brightness/)() const | Получает или задает границу значения преобразования цветов в белый и черный. Этот параметр может быть применен с EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle или [ColorDepth.Format1bpp](../colordepth/) == 1. |
| [get_Compression](./get_compression/)() const | Возвращает тип сжатия. |
| [get_CoordinateType](./get_coordinatetype/)() const | Получает или задает тип координат страницы (Media/Crop коробки). Значение CropBox используется по умолчанию. |
| [get_Depth](./get_depth/)() const | Возвращает глубину цвета. |
| [get_Margins](./get_margins/)() const | Получает поля. |
| [get_Shape](./get_shape/)() const | Получает тип фигуры. |
| [get_SkipBlankPages](./get_skipblankpages/)() const | Получает значение, указывающее, следует ли пропускать пустые страницы. |
| [set_Brightness](./set_brightness/)(float) | Получает или задает границу значения преобразования цветов в белый и черный. Этот параметр может быть применен с EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle или [ColorDepth.Format1bpp](../colordepth/) == 1. |
| [set_Compression](./set_compression/)(CompressionType) | Устанавливает тип сжатия. |
| [set_CoordinateType](./set_coordinatetype/)(PageCoordinateType) | Получает или задает тип координат страницы (Media/Crop коробки). Значение CropBox используется по умолчанию. |
| [set_Depth](./set_depth/)(ColorDepth) | Устанавливает глубину цвета. |
| [set_Shape](./set_shape/)(ShapeType) | Устанавливает тип фигуры. |
| [set_SkipBlankPages](./set_skipblankpages/)(bool) | Устанавливает значение, указывающее, следует ли пропускать пустые страницы. |
| [TiffSettings](./tiffsettings/)() | Инициализирует новый экземпляр класса [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(ShapeType) | Инициализирует новый экземпляр класса [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(CompressionType) | Инициализирует новый экземпляр класса [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(ColorDepth) | Инициализирует новый экземпляр класса [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(const System::SharedPtr\<Aspose::Pdf::Devices::Margins\>\&) | Инициализирует новый экземпляр класса [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(CompressionType, ColorDepth, const System::SharedPtr\<Aspose::Pdf::Devices::Margins\>\&) | Инициализирует новый экземпляр класса [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(CompressionType, ColorDepth, const System::SharedPtr\<Aspose::Pdf::Devices::Margins\>\&, bool) | Инициализирует новый экземпляр класса [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(CompressionType, ColorDepth, const System::SharedPtr\<Aspose::Pdf::Devices::Margins\>\&, bool, ShapeType) | Инициализирует новый экземпляр класса [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(bool) | Инициализирует новый экземпляр класса [TiffSettings](./). |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
