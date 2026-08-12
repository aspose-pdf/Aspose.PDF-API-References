---
title: "Aspose::Pdf::Comparison::ImagesDifference::DifferenceToImage method"
linktitle: "DifferenceToImage"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Comparison::ImagesDifference::DifferenceToImage method. Convierte la matriz de diferencias a una imagen bitmap usando los colores especificados en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.comparison/imagesdifference/differencetoimage/
---
## ImagesDifference::DifferenceToImage method


Convierte la matriz de diferencias a una imagen bitmap usando los colores especificados.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::Pdf::Comparison::ImagesDifference::DifferenceToImage(const System::SharedPtr<Color> &color, const System::SharedPtr<Color> &backgroundColor)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | const System::SharedPtr\<Color\>\& | El color para diferencias distintas de cero. |
| backgroundColor | const System::SharedPtr\<Color\>\& | El color de fondo para diferencias iguales a cero. |

### ReturnValue

Una imagen bitmap que representa la matriz de diferencias.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bitmap](../../../system.drawing/bitmap/)
* Class [Color](../../../aspose.pdf/color/)
* Class [ImagesDifference](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
