---
title: "Aspose::Pdf::Matrix::UnTransform método"
linktitle: "UnTransform"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Matrix::UnTransform método. Transforma de regreso x1 y y1 y devuelve x e y antes de la transformación de la matriz usando la siguiente fórmula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B) en C++."
type: docs
weight: 2600
url: /es/cpp/aspose.pdf/matrix/untransform/
---
## Matrix::UnTransform method


Transforma de vuelta x1 y y1 y devuelve x e y antes de la transformación de la matriz usando la siguiente fórmula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

```cpp
void Aspose::Pdf::Matrix::UnTransform(double x1, double y1, double &x, double &y)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x1 | double | Coordenada X de entrada |
| y1 | double | Coordenada Y de entrada |
| x | double\& | Coordenada X de salida |
| y | double\& | Coordenada Y de salida |

## Ver también

* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
