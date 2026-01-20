---
title: Aspose::Pdf::Matrix::Scale method
linktitle: Scale
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Matrix::Scale method. Scales x and y with the matrix using the following formula: x1 = A*x + C*y; y1 = B*x + D*y; in C++.'
type: docs
weight: 1600
url: /cpp/aspose.pdf/matrix/scale/
---
## Matrix::Scale(double, double, double\&, double\&) method


Scales x and y with the matrix using the following formula: x1 = A*x + C*y; y1 = B*x + D*y;.

```cpp
void Aspose::Pdf::Matrix::Scale(double x, double y, double &x1, double &y1)
```


| Parameter | Type | Description |
| --- | --- | --- |
| x | double | Input X coordinate |
| y | double | Input Y coordinate |
| x1 | double\& | Output X coordinate |
| y1 | double\& | Output Y coordinate |

## See Also

* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix::Scale(double, double, System::SharedPtr\<Matrix\>) method


Applies scaling to the given matrix.

```cpp
static System::SharedPtr<Matrix> Aspose::Pdf::Matrix::Scale(double sx, double sy, System::SharedPtr<Matrix> source)
```


| Parameter | Type | Description |
| --- | --- | --- |
| sx | double | The scaling factor for the X-axis. |
| sy | double | The scaling factor for the Y-axis. |
| source | System::SharedPtr\<Matrix\> | The matrix to scale. |

### ReturnValue

A new matrix that is the result of scaling the source matrix.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Matrix](../)
* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
