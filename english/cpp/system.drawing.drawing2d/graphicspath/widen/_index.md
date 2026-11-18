---
title: System::Drawing::Drawing2D::GraphicsPath::Widen method
linktitle: Widen
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Drawing2D::GraphicsPath::Widen method. Replaces this path with an outline around the original path in C++.'
type: docs
weight: 3800
url: /cpp/system.drawing.drawing2d/graphicspath/widen/
---
## GraphicsPath::Widen(const SharedPtr\<Pen\>\&) method


Replaces this path with an outline around the original path.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Widen(const SharedPtr<Pen> &pen)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pen | const SharedPtr\<Pen\>\& | A [Pen](../../../system.drawing/pen/) object that specifies the width between the original and the new outlines |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../../system.drawing/pen/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.PDF for C++](../../../)
## GraphicsPath::Widen(const SharedPtr\<Pen\>\&, const MatrixPtr\&) method


Replaces this path with an outline around the original path and then applies the specified transform matrix to it.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Widen(const SharedPtr<Pen> &pen, const MatrixPtr &matrix)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pen | const SharedPtr\<Pen\>\& | A [Pen](../../../system.drawing/pen/) object that specifies the width between the original and the new outlines |
| matrix | const MatrixPtr\& | The transform matrix to apply to the path after widening; if null, no transformation is applied |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../../system.drawing/pen/)
* Typedef [MatrixPtr](../../matrixptr/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.PDF for C++](../../../)
