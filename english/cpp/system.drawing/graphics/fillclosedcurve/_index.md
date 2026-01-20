---
title: System::Drawing::Graphics::FillClosedCurve method
linktitle: FillClosedCurve
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Graphics::FillClosedCurve method. Draws a closed spline using the specified brush in C++.'
type: docs
weight: 3200
url: /cpp/system.drawing/graphics/fillclosedcurve/
---
## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode, float) method


Draws a closed spline using the specified brush.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```


| Parameter | Type | Description |
| --- | --- | --- |
| brush | const SharedPtr\<Brush\>\& | A brush to use when drawing the spline |
| points | const ArrayPtr\<Point\>\& | [Array](../../../system/array/) of points that determines the spline |
| fillmode | Drawing2D::FillMode | IGNORED |
| tension | float | Value that specifies the tension of the spline |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Brush](../../brush/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../point/)
* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode, float) method


Draws a closed spline using the specified brush.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```


| Parameter | Type | Description |
| --- | --- | --- |
| brush | const SharedPtr\<Brush\>\& | A brush to use when drawing the spline |
| points | const ArrayPtr\<PointF\>\& | [Array](../../../system/array/) of points that determines the spline |
| fillmode | Drawing2D::FillMode | IGNORED |
| tension | float | Value that specifies the tension of the spline |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Brush](../../brush/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PointF](../../pointf/)
* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
