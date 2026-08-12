---
title: "Método System::Drawing::Point::Subtract"
linktitle: "Restar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Drawing::Point::Subtract. Resta los valores de ancho y alto del objeto Size especificado de los valores de coordenadas X e Y del objeto Point especificado de forma correspondiente en C++."
type: docs
weight: 1800
url: /es/cpp/system.drawing/point/subtract/
---
## Point::Subtract method


Resta los valores de ancho y alto del objeto [Size](../../size/) especificado de los valores de coordenadas X e Y del objeto [Point](../) especificado de forma correspondiente.

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| punto | const Point\& | El punto a trasladar |
| size | const Size\& | El objeto [Size](../../size/) que especifica los valores a restar de los valores de coordenadas del **point** |

### ReturnValue

Un nuevo objeto [Point](../) cuyo valor de la coordenada X es igual al resultado de la resta del valor de ancho de **size** al valor de la coordenada X de **point** y cuyo valor de la coordenada Y es igual al resultado de la resta del valor de alto de **size** al valor de la coordenada Y de **point**

## Ver también

* Class [Point](../)
* Class [Size](../../size/)
* Class [Point](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
