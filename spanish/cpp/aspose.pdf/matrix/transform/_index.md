---
title: "Aspose::Pdf::Matrix::Transform método"
linktitle: "Transform"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Matrix::Transform método. Transforma un rectángulo. Si el ángulo no es 90 * N grados, entonces se devuelve el rectángulo delimitador en C++."
type: docs
weight: 2400
url: /es/cpp/aspose.pdf/matrix/transform/
---
## Matrix::Transform(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) method


Transforma el rectángulo. Si el ángulo no es 90 * N grados, se devuelve el rectángulo delimitador.

```cpp
System::SharedPtr<Aspose::Pdf::Rectangle> Aspose::Pdf::Matrix::Transform(const System::SharedPtr<Aspose::Pdf::Rectangle> &rect)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | [Rectangle](../../rectangle/) para ser transformado. |

### ReturnValue

Rectángulo transformado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Rectangle](../../rectangle/)
* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix::Transform(const System::SharedPtr\<Point\>\&) method


Transforma el punto usando esta matriz.

```cpp
System::SharedPtr<Point> Aspose::Pdf::Matrix::Transform(const System::SharedPtr<Point> &p)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| p | const System::SharedPtr\<Point\>\& | [Point](../../point/) que será transformado. |

### ReturnValue

Resultado de la transformación.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Point](../../point/)
* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix::Transform(double, double, double\&, double\&) method


Transforma las coordenadas usando esta matriz.

```cpp
void Aspose::Pdf::Matrix::Transform(double x, double y, double &x1, double &y1)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | double | Coordenada X. |
| y | double | Coordenada Y. |
| x1 | double\& | Coordenada X transformada. |
| y1 | double\& | Coordenada Y transformada. |

## Ver también

* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
