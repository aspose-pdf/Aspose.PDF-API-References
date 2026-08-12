---
title: "System::Drawing::Drawing2D::CustomLineCap::CustomLineCap constructor"
linktitle: "CustomLineCap"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::Drawing2D::CustomLineCap::CustomLineCap constructor. Construye una nueva instancia de la clase CustomLineCap que representa una tapa de línea definida por el usuario con las propiedades especificadas en C++."
type: docs
weight: 100
url: /es/cpp/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap constructor


Construye una nueva instancia de la clase [CustomLineCap](../) que representa una tapa de línea definida por el usuario con las propiedades especificadas.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillPath | const SharedPtr\<GraphicsPath\>\& | Especifica un relleno para la tapa personalizada |
| strokePath | const SharedPtr\<GraphicsPath\>\& | Especifica un contorno de la tapa personalizada |
| baseCap | LineCap | La tapa de línea base a partir de la cual se crea la tapa personalizada |
| baseInset | float | Especifica la distancia entre la línea y la tapa |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsPath](../../graphicspath/)
* Enum [LineCap](../../linecap/)
* Class [CustomLineCap](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.PDF for C++](../../../)
