---
title: "Aspose::Pdf::Matrix3D::Matrix3D constructor"
linktitle: "Matrix3D"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Matrix3D::Matrix3D constructor. El constructor crea una matriz estándar 1 a 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D::Matrix3D() constructor


El constructor crea una matriz estándar 1 a 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0].

```cpp
Aspose::Pdf::Matrix3D::Matrix3D()
```

## Ver también

* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix3D::Matrix3D(const System::ArrayPtr\<double\>\&) constructor


El constructor acepta una matriz con la siguiente representación de arreglo: [ A B C D E F G H I Tx Ty Tz].

```cpp
Aspose::Pdf::Matrix3D::Matrix3D(const System::ArrayPtr<double> &matrix3DArray)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix3DArray | const System::ArrayPtr\<double\>\& | [Matrix](../../matrix/) matriz de datos. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix3D::Matrix3D(const System::SharedPtr\<Matrix3D\>\&) constructor


El constructor acepta una matriz para crear una copia.

```cpp
Aspose::Pdf::Matrix3D::Matrix3D(const System::SharedPtr<Matrix3D> &matrix)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | const System::SharedPtr\<Matrix3D\>\& | [Matrix3D](../) objeto. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Matrix3D](../)
* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix3D::Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) constructor


Inicializa la matriz de transformación con los coeficientes especificados.

```cpp
Aspose::Pdf::Matrix3D::Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | double | Un valor de matriz. |
| b | double | Valor de matriz B. |
| c | double | Valor de matriz C. |
| d | double | Valor de matriz D. |
| e | double | Valor de matriz E. |
| f | double | Valor de matriz F. |
| g | double | Valor de la matriz G. |
| h | double | Valor de la matriz H. |
| i | double | Valor de la matriz I. |
| tx | double | Valor de la matriz TX. |
| ty | double | Valor de la matriz TY. |
| tz | double | Valor de la matriz TZ. |

## Ver también

* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
