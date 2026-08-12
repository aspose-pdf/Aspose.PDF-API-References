---
title: "System::Drawing::Imaging::ImageFlags enum"
linktitle: "ImageFlags"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::Imaging::ImageFlags enum. Representa los atributos de los datos de píxel representados por un objeto Image en C++."
type: docs
weight: 2200
url: /es/cpp/system.drawing.imaging/imageflags/
---
## ImageFlags enum


Representa los atributos de los datos de píxel representados por un objeto [Image](../../system.drawing/image/).

```cpp
enum class ImageFlags
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Ninguno | 0 |  |
| Escalable | 1 | Escalable. |
| HasAlpha | 2 | Contiene información alfa. |
| HasTranslucent | 4 | Hay valores alfa mayores que 0 y menores que 255. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | Los datos de píxel se representan en el espacio de color RGB. |
| ColorSpaceCmyk | 32 | Los datos de píxel se representan en el espacio de color CMYK. |
| ColorSpaceGray | 64 | Los datos de píxel son en escala de grises. |
| ColorSpaceYcbcr | 128 | Los datos de píxel se representan en el espacio de color YCBCR. |
| ColorSpaceYcck | 256 | Los datos de píxel se representan en el espacio de color YCCK. |
| HasRealDpi | 4096 | La información DPI se almacena en la imagen. |
| HasRealPixelSize | 8192 | El tamaño de un píxel se almacena en la imagen. |
| ReadOnly | 65536 | Los datos de píxel son de solo lectura. |
| Caching | 131072 | Puede almacenarse en caché para un acceso más rápido. |

## Ver también

* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
