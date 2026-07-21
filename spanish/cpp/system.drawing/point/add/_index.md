---
title: "System::Drawing::Point::Add method"
linktitle: "Add"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::Point::Add method. Añade los valores de ancho y alto del objeto Size especificado a los valores de coordenadas X y Y del objeto Point especificado correspondientemente en C++."
type: docs
weight: 1500
url: /es/cpp/system.drawing/point/add/
---
## Point::Add method


Añade los valores de ancho y alto del objeto [Size](../../size/) especificado a los valores de coordenadas X y Y del objeto [Point](../) especificado correspondientemente.

```cpp
static Point System::Drawing::Point::Add(const Point &point, const Size &size)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| punto | const Point\& | El punto a trasladar |
| size | const Size\& | El objeto [Size](../../size/) que especifica los valores a añadir a los valores de coordenadas del **point** |

### ReturnValue

Un nuevo objeto [Point](../) cuyo valor de coordenada X es igual a la suma del valor de coordenada X de **point** y el valor de ancho de **size**, y cuyo valor de coordenada Y es igual a la suma del valor de coordenada Y de **point** y el valor de alto de **size**

## Ver también

* Class [Point](../)
* Class [Size](../../size/)
* Class [Point](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
