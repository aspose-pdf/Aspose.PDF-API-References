---
title: "Класс Aspose::Pdf::Devices::ImageDevice"
linktitle: "ImageDevice"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Devices::ImageDevice. Абстрактный класс для графических устройств в C++."
type: docs
weight: 700
url: /ru/cpp/aspose.pdf.devices/imagedevice/
---
## ImageDevice class


Абстрактный класс для устройств изображения.

```cpp
class ImageDevice : public Aspose::Pdf::Devices::PageDevice
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_CoordinateType](./get_coordinatetype/)() const | Получает тип координат страницы (Media/Crop‑коробки). Значение CropBox используется по умолчанию. |
| [get_FormPresentationMode](./get_formpresentationmode/)() const | Получает режим отображения формы. |
| [get_Height](./get_height/)() const | Получает высоту выходного изображения. |
| [get_RenderingOptions](./get_renderingoptions/)() const | Получает параметры рендеринга. |
| [get_Resolution](./get_resolution/)() const | Получает разрешение изображения. |
| [get_Width](./get_width/)() const | Получает ширину выходного изображения. |
| [GetBitmap](./getbitmap/)(const System::SharedPtr\<Page\>\&) | Преобразует страницу в [Bitmap](../). |
| [ImageDevice](./imagedevice/)() | Абстрактный инициализатор для потомков [ImageDevice](./), устанавливающий разрешение 150x150. |
| [ImageDevice](./imagedevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Абстрактный инициализатор для потомков [ImageDevice](./). |
| [ImageDevice](./imagedevice/)(int32_t, int32_t) | Инициализирует новый экземпляр класса [JpegDevice](../jpegdevice/) с заданными размерами изображения и разрешением по умолчанию (=150). |
| [ImageDevice](./imagedevice/)(const System::SharedPtr\<PageSize\>\&) | Инициализирует новый экземпляр класса [JpegDevice](../jpegdevice/) с заданными размерами изображения и разрешением по умолчанию (=150). |
| [ImageDevice](./imagedevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [JpegDevice](../jpegdevice/) с заданными размерами изображения и разрешением. |
| [ImageDevice](./imagedevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [JpegDevice](../jpegdevice/) с заданными размерами изображения и разрешением. |
| [set_CoordinateType](./set_coordinatetype/)(PageCoordinateType) | Устанавливает тип координат страницы (Media/Crop‑коробки). Значение CropBox используется по умолчанию. |
| [set_FormPresentationMode](./set_formpresentationmode/)(Aspose::Pdf::Devices::FormPresentationMode) | Устанавливает режим отображения формы. |
| [set_RenderingOptions](./set_renderingoptions/)(const System::SharedPtr\<Aspose::Pdf::RenderingOptions\>\&) | Устанавливает параметры рендеринга. |
## См. также

* Class [PageDevice](../pagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
