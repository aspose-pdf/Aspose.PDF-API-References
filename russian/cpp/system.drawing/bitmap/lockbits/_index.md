---
title: "System::Drawing::Bitmap::LockBits метод"
linktitle: "LockBits"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Bitmap::LockBits метод. Блокирует Bitmap в системной памяти в C++."
type: docs
weight: 1500
url: /ru/cpp/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) method


Блокирует [Bitmap](../) в системной памяти.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const Rectangle\& | Прямоугольник, определяющий область изображения для блокировки |
| flags | Imaging::ImageLockMode | Указывает уровень доступа к bitmap |
| формат | Imaging::PixelFormat | Формат данных этого битмапа |

### ReturnValue

Указатель shared pointer на объект BitmapData, содержащий информацию о выполненной операции блокировки

## См. также

* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) method


Блокирует [Bitmap](../) в системной памяти.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const Rectangle\& | Прямоугольник, определяющий область изображения для блокировки |
| flags | Imaging::ImageLockMode | Указывает уровень доступа к bitmap |
| формат | Imaging::PixelFormat | Формат данных этого битмапа |
| bitmap_data | const Imaging::BitmapDataPtr\& | Содержит информацию об операции блокировки |

### ReturnValue

Указатель shared pointer на объект BitmapData, содержащий информацию о выполненной операции блокировки

## См. также

* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
