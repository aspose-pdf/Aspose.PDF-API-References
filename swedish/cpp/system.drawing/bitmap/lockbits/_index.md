---
title: "System::Drawing::Bitmap::LockBits method"
linktitle: "LockBits"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Bitmap::LockBits method. Låser en Bitmap i systemminnet i C++."
type: docs
weight: 1500
url: /sv/cpp/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) method


Låser en [Bitmap](../) i systemminnet.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const Rectangle\& | En rektangel som specificerar området av bilden som ska låsas |
| flags | Imaging::ImageLockMode | Anger åtkomstnivån till bitmapen |
| format | Imaging::PixelFormat | Dataformatet för denna bitmap |

### ReturnValue

En delad pekare till ett BitmapData-objekt som innehåller information om den utförda låsoperationen

## Se även

* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) method


Låser en [Bitmap](../) i systemminnet.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const Rectangle\& | En rektangel som specificerar området av bilden som ska låsas |
| flags | Imaging::ImageLockMode | Anger åtkomstnivån till bitmapen |
| format | Imaging::PixelFormat | Dataformatet för denna bitmap |
| bitmap_data | const Imaging::BitmapDataPtr\& | Innehåller information om låsoperationen |

### ReturnValue

En delad pekare till ett BitmapData-objekt som innehåller information om den utförda låsoperationen

## Se även

* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
