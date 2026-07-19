---
title: "System::Drawing::Imaging::ImageFormat class"
linktitle: "ImageFormat"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Imaging::ImageFormat class. Представляет формат файла изображения. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1100
url: /ru/cpp/system.drawing.imaging/imageformat/
---
## ImageFormat class


Представляет формат файла изображения. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ImageFormat : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Equals](./equals/)(ImageFormatPtr) const | Определяет, равны ли форматы изображений, представленные текущим и указанным объектами. |
| static [get_Bmp](./get_bmp/)() | Возвращает умный указатель на объект [ImageFormat](./), представляющий формат растрового изображения. |
| static [get_Emf](./get_emf/)() | Возвращает умный указатель на объект [ImageFormat](./), представляющий формат расширенного метафайла. |
| static [get_Exif](./get_exif/)() | Возвращает умный указатель на объект [ImageFormat](./), представляющий формат обменного файла [Image](../../system.drawing/image/) (Exif). |
| static [get_Gif](./get_gif/)() | Возвращает умный указатель на объект [ImageFormat](./), представляющий формат изображения [Graphics](../../system.drawing/graphics/) Interchange Format (GIF). |
| [get_Guid](./get_guid/)() const | Возвращает GUID, связанный с форматом изображения, представленного текущим объектом. |
| static [get_Icon](./get_icon/)() | Возвращает умный указатель на объект [ImageFormat](./), представляющий формат значка [Windows](../../system.windows/). |
| static [get_Jpeg](./get_jpeg/)() | Возвращает умный указатель на объект [ImageFormat](./), представляющий формат изображения Joint Photographic Experts Group (JPEG). |
| static [get_MemoryBmp](./get_memorybmp/)() | Возвращает умный указатель на объект [ImageFormat](./), представляющий формат растрового изображения в памяти. |
| static [get_Png](./get_png/)() | Возвращает умный указатель на объект [ImageFormat](./), представляющий формат W3C Portable Network [Graphics](../../system.drawing/graphics/) (PNG). |
| static [get_Tiff](./get_tiff/)() | Возвращает умный указатель на объект [ImageFormat](./), представляющий Tagged [Image](../../system.drawing/image/) File Format (TIFF) формат изображения. |
| static [get_Wmf](./get_wmf/)() | Возвращает умный указатель на объект [ImageFormat](./), представляющий [Windows](../../system.windows/) metafile (WMF) формат изображения. |
| [ImageFormat](./imageformat/)(const System::Guid\&) | Создаёт экземпляр класса [ImageFormat](./), представляющий формат изображения, связанный с указанным GUID. |
| virtual [ToString](./tostring/)() const | Преобразует этот объект [ImageFormat](./) в человекочитаемую строку. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
