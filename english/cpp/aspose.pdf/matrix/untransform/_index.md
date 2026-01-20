---
title: Aspose::Pdf::Matrix::UnTransform method
linktitle: UnTransform
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Matrix::UnTransform method. Transforms back x1 and y1 and returns x and y before the matrix transformation using the following formula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B) in C++.'
type: docs
weight: 2600
url: /cpp/aspose.pdf/matrix/untransform/
---
## Matrix::UnTransform method


Transforms back x1 and y1 and returns x and y before the matrix transformation using the following formula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

```cpp
void Aspose::Pdf::Matrix::UnTransform(double x1, double y1, double &x, double &y)
```


| Parameter | Type | Description |
| --- | --- | --- |
| x1 | double | Input X coordinate |
| y1 | double | Input Y coordinate |
| x | double\& | Output X coordinate |
| y | double\& | Output Y coordinate |

## See Also

* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
