---
title: System::Drawing::Graphics::DrawClosedCurve method
linktitle: DrawClosedCurve
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Graphics::DrawClosedCurve method. Draws a closed spline using the specified pen in C++.'
type: docs
weight: 1300
url: /cpp/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) method


Draws a closed spline using the specified pen.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pen | const SharedPtr\<Pen\>\& | A pen to use when drawing the spline |
| points | const ArrayPtr\<Point\>\& | [Array](../../../system/array/) of points that determines the spline |
| tension | float | Value that specifies the tension of the spline |
| fillmode | Drawing2D::FillMode | IGNORED |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../point/)
* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) method


Draws a closed spline using the specified pen.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pen | const SharedPtr\<Pen\>\& | A pen to use when drawing the spline |
| points | const ArrayPtr\<PointF\>\& | [Array](../../../system/array/) of points that determines the spline |
| tension | float | Value that specifies the tension of the spline |
| fillmode | Drawing2D::FillMode | IGNORED |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PointF](../../pointf/)
* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
