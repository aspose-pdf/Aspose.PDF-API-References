---
title: "System::Drawing::Imaging::ImageFlags enum"
linktitle: "ImageFlags"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Imaging::ImageFlags enum. Представляет атрибуты пиксельных данных, представленных объектом Image в C++."
type: docs
weight: 2200
url: /ru/cpp/system.drawing.imaging/imageflags/
---
## ImageFlags enum


Представляет атрибуты пиксельных данных, представленных объектом [Image](../../system.drawing/image/).

```cpp
enum class ImageFlags
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 |  |
| Масштабируемый | 1 | Масштабируемый. |
| HasAlpha | 2 | Содержит информацию об альфа-канале. |
| HasTranslucent | 4 | Есть альфа‑значения, большие 0 и меньшие 255. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | Пиксельные данные представлены в цветовом пространстве RGB. |
| ColorSpaceCmyk | 32 | Пиксельные данные представлены в цветовом пространстве CMYK. |
| ColorSpaceGray | 64 | Пиксельные данные в градациях серого. |
| ColorSpaceYcbcr | 128 | Пиксельные данные представлены в цветовом пространстве YCBCR. |
| ColorSpaceYcck | 256 | Пиксельные данные представлены в цветовом пространстве YCCK. |
| HasRealDpi | 4096 | Информация о DPI хранится в изображении. |
| HasRealPixelSize | 8192 | Размер пикселя хранится в изображении. |
| ReadOnly | 65536 | Данные пикселя доступны только для чтения. |
| Кеширование | 131072 | Можно кэшировать для более быстрого доступа. |

## См. также

* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
