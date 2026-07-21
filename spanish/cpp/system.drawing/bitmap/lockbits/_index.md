---
title: "System::Drawing::Bitmap::LockBits método"
linktitle: "LockBits"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::Bitmap::LockBits método. Bloquea un Bitmap en la memoria del sistema en C++."
type: docs
weight: 1500
url: /es/cpp/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) method


Bloquea un [Bitmap](../) en la memoria del sistema.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | const Rectangle\& | Un rectángulo que especifica la región de la imagen a bloquear |
| flags | Imaging::ImageLockMode | Especifica el nivel de acceso al bitmap |
| formato | Imaging::PixelFormat | El formato de datos de este bitmap |

### ReturnValue

Un puntero compartido a un objeto BitmapData que contiene información sobre la operación de bloqueo realizada

## Ver también

* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) method


Bloquea un [Bitmap](../) en la memoria del sistema.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | const Rectangle\& | Un rectángulo que especifica la región de la imagen a bloquear |
| flags | Imaging::ImageLockMode | Especifica el nivel de acceso al bitmap |
| formato | Imaging::PixelFormat | El formato de datos de este bitmap |
| bitmap_data | const Imaging::BitmapDataPtr\& | Contiene información sobre la operación de bloqueo |

### ReturnValue

Un puntero compartido a un objeto BitmapData que contiene información sobre la operación de bloqueo realizada

## Ver también

* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
