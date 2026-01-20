---
title: System::Drawing::Drawing2D::GraphicsPath::Flatten method
linktitle: Flatten
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Drawing2D::GraphicsPath::Flatten method. Flattens each curve in the path by converting them into a series of connected lines. The flatness value of 0.25 is used in C++.'
type: docs
weight: 2100
url: /cpp/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() method


Flattens each curve in the path by converting them into a series of connected lines. The flatness value of 0.25 is used.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## See Also

* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.PDF for C++](../../../)
## GraphicsPath::Flatten(const MatrixPtr\&) method


Flattens each curve in the path by converting them into a series of connected lines. The flatness value of 0.25 is used.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```


| Parameter | Type | Description |
| --- | --- | --- |
| matrix | const MatrixPtr\& | The transform matrix to apply to the path before flattening |

## See Also

* Typedef [MatrixPtr](../../matrixptr/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.PDF for C++](../../../)
## GraphicsPath::Flatten(const MatrixPtr\&, float) method


Flattens each curve in the path by converting them into a series of connected lines.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```


| Parameter | Type | Description |
| --- | --- | --- |
| matrix | const MatrixPtr\& | The transform matrix to apply to the path before flattening |
| flatness | float | Specifies the maximum permitted error between the curve and its flattened approximation |

## See Also

* Typedef [MatrixPtr](../../matrixptr/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.PDF for C++](../../../)
