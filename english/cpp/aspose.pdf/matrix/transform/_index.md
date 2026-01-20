---
title: Aspose::Pdf::Matrix::Transform method
linktitle: Transform
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Matrix::Transform method. Transforms coordinates using this matrix in C++.'
type: docs
weight: 2400
url: /cpp/aspose.pdf/matrix/transform/
---
## Matrix::Transform(double, double, double\&, double\&) method


Transforms coordinates using this matrix.

```cpp
void Aspose::Pdf::Matrix::Transform(double x, double y, double &x1, double &y1)
```


| Parameter | Type | Description |
| --- | --- | --- |
| x | double | X coordinate. |
| y | double | Y coordinate. |
| x1 | double\& | Transformed X coordinate. |
| y1 | double\& | Transformed Y coordinate. |

## See Also

* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix::Transform(System::SharedPtr\<Aspose::Pdf::Rectangle\>) method


Transformes rectangle. If angle is not 90 * N degrees then bounding rectangle is returned.

```cpp
System::SharedPtr<Aspose::Pdf::Rectangle> Aspose::Pdf::Matrix::Transform(System::SharedPtr<Aspose::Pdf::Rectangle> rect)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::SharedPtr\<Aspose::Pdf::Rectangle\> | [Rectangle](../../rectangle/) to be transformed. |

### ReturnValue

Transformed rectangle.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Rectangle](../../rectangle/)
* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix::Transform(System::SharedPtr\<Point\>) method


Transforms point using this matrix.

```cpp
System::SharedPtr<Point> Aspose::Pdf::Matrix::Transform(System::SharedPtr<Point> p)
```


| Parameter | Type | Description |
| --- | --- | --- |
| p | System::SharedPtr\<Point\> | [Point](../../point/) which will be transformed. |

### ReturnValue

Transformation result.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Point](../../point/)
* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
