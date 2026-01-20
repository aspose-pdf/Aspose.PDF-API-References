---
title: Aspose::Pdf::Matrix3D::Matrix3D constructor
linktitle: Matrix3D
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Matrix3D::Matrix3D constructor. Constructor creates standard 1 to 1 matrix: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D::Matrix3D() constructor


Constructor creates standard 1 to 1 matrix: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0].

```cpp
Aspose::Pdf::Matrix3D::Matrix3D()
```

## See Also

* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix3D::Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) constructor


Initializes transformation matrix with specified coefficients.

```cpp
Aspose::Pdf::Matrix3D::Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
```


| Parameter | Type | Description |
| --- | --- | --- |
| a | double | A matrix value. |
| b | double | B matrix value. |
| c | double | C matrix value. |
| d | double | D matrix value. |
| e | double | E matrix value. |
| f | double | F matrix value. |
| g | double | G matrix value. |
| h | double | H matrix value. |
| i | double | I matrix value. |
| tx | double | TX matrix value. |
| ty | double | TY matrix value. |
| tz | double | TZ matrix value. |

## See Also

* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix3D::Matrix3D(System::ArrayPtr\<double\>) constructor


Constructor accepts a matrix with following array representation: [ A B C D E F G H I Tx Ty Tz].

```cpp
Aspose::Pdf::Matrix3D::Matrix3D(System::ArrayPtr<double> matrix3DArray)
```


| Parameter | Type | Description |
| --- | --- | --- |
| matrix3DArray | System::ArrayPtr\<double\> | [Matrix](../../matrix/) data array. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix3D::Matrix3D(System::SharedPtr\<Matrix3D\>) constructor


Constructor accepts a matrix to create a copy.

```cpp
Aspose::Pdf::Matrix3D::Matrix3D(System::SharedPtr<Matrix3D> matrix)
```


| Parameter | Type | Description |
| --- | --- | --- |
| matrix | System::SharedPtr\<Matrix3D\> | [Matrix3D](../) object. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Matrix3D](../)
* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
