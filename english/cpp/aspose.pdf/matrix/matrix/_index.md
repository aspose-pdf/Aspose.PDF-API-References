---
title: Aspose::Pdf::Matrix::Matrix constructor
linktitle: Matrix
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Matrix::Matrix constructor. Constructor creates stanrard 1 to 1 matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf/matrix/matrix/
---
## Matrix::Matrix() constructor


Constructor creates stanrard 1 to 1 matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0].

```cpp
Aspose::Pdf::Matrix::Matrix()
```

## See Also

* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix::Matrix(const System::Details::ArrayView\<float\>\&) constructor


Constructor accepts a matrix with following array representation: [ A B C D E F ].

```cpp
Aspose::Pdf::Matrix::Matrix(const System::Details::ArrayView<float> &matrixArray)
```


| Parameter | Type | Description |
| --- | --- | --- |
| matrixArray | const System::Details::ArrayView\<float\>\& | [Matrix](../) data array. |

## See Also

* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix::Matrix(double, double, double, double, double, double) constructor


Initializes transformation matrix with specified coefficients.

```cpp
Aspose::Pdf::Matrix::Matrix(double a, double b, double c, double d, double e, double f)
```


| Parameter | Type | Description |
| --- | --- | --- |
| a | double | A matrix value. |
| b | double | B matrix value. |
| c | double | C matrix value. |
| d | double | D matrix value. |
| e | double | E matrix value. |
| f | double | F matrix value. |

## See Also

* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix::Matrix(System::ArrayPtr\<double\>) constructor


Constructor accepts a matrix with following array representation: [ A B C D E F ].

```cpp
Aspose::Pdf::Matrix::Matrix(System::ArrayPtr<double> matrixArray)
```


| Parameter | Type | Description |
| --- | --- | --- |
| matrixArray | System::ArrayPtr\<double\> | [Matrix](../) data array. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix::Matrix(System::SharedPtr\<Matrix\>) constructor


Constructor accepts a matrix to create a copy.

```cpp
Aspose::Pdf::Matrix::Matrix(System::SharedPtr<Matrix> matrix)
```


| Parameter | Type | Description |
| --- | --- | --- |
| matrix | System::SharedPtr\<Matrix\> | [Matrix](../) object. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Matrix](../)
* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
