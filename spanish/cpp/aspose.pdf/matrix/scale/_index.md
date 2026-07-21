---
title: "Aspose::Pdf::Matrix::Scale método"
linktitle: "Escalar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Matrix::Scale método. Escala x e y con la matriz usando la siguiente fórmula: x1 = A*x + C*y; y1 = B*x + D*y; en C++."
type: docs
weight: 1600
url: /es/cpp/aspose.pdf/matrix/scale/
---
## Matrix::Scale(double, double, double\&, double\&) method


Escala x e y con la matriz usando la siguiente fórmula: x1 = A*x + C*y; y1 = B*x + D*y;.

```cpp
void Aspose::Pdf::Matrix::Scale(double x, double y, double &x1, double &y1)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | double | Coordenada X de entrada |
| y | double | Coordenada Y de entrada |
| x1 | double\& | Coordenada X de salida |
| y1 | double\& | Coordenada Y de salida |

## Ver también

* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix::Scale(double, double, const System::SharedPtr\<Matrix\>\&) method


Aplica escalado a la matriz dada.

```cpp
static System::SharedPtr<Matrix> Aspose::Pdf::Matrix::Scale(double sx, double sy, const System::SharedPtr<Matrix> &source)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | double | El factor de escala para el eje X. |
| sy | double | El factor de escala para el eje Y. |
| origen | const System::SharedPtr\<Matrix\>\& | La matriz a escalar. |

### ReturnValue

Una nueva matriz que es el resultado de escalar la matriz origen.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Matrix](../)
* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
