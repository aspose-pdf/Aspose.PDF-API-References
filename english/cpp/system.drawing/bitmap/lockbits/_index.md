---
title: System::Drawing::Bitmap::LockBits method
linktitle: LockBits
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Bitmap::LockBits method. Locks a Bitmap into system memory in C++.'
type: docs
weight: 1500
url: /cpp/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) method


Locks a [Bitmap](../) into system memory.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | const Rectangle\& | A rectangle that specifies the region of the image to lock |
| flags | Imaging::ImageLockMode | Specifies the access level to the bitmap |
| format | Imaging::PixelFormat | The data format of this bitmap |

### ReturnValue

A shared pointer to a BitmapData object that contains information about the performed lock operation

## See Also

* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) method


Locks a [Bitmap](../) into system memory.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | const Rectangle\& | A rectangle that specifies the region of the image to lock |
| flags | Imaging::ImageLockMode | Specifies the access level to the bitmap |
| format | Imaging::PixelFormat | The data format of this bitmap |
| bitmap_data | const Imaging::BitmapDataPtr\& | Contains information about the lock operation |

### ReturnValue

A shared pointer to a BitmapData object that contains information about the performed lock operation

## See Also

* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
