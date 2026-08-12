---
title: "System::Drawing::Graphics::DrawClosedCurve метод"
linktitle: "DrawClosedCurve"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Graphics::DrawClosedCurve метод. Рисует замкнутую сплайн-кривую, используя указанное перо в C++."
type: docs
weight: 1300
url: /ru/cpp/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) method


Рисует замкнутый сплайн с использованием указанного пера.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| перо | const SharedPtr\<Pen\>\& | Pen, используемый при рисовании сплайна |
| points | const ArrayPtr\<Point\>\& | [Array](../../../system/array/) точек, определяющих сплайн |
| tension | float | Значение, определяющее натяжение сплайна |
| fillmode | Drawing2D::FillMode | IGNORED |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../point/)
* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) method


Рисует замкнутый сплайн с использованием указанного пера.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| перо | const SharedPtr\<Pen\>\& | Pen, используемый при рисовании сплайна |
| points | const ArrayPtr\<PointF\>\& | [Array](../../../system/array/) точек, определяющих сплайн |
| tension | float | Значение, определяющее натяжение сплайна |
| fillmode | Drawing2D::FillMode | IGNORED |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PointF](../../pointf/)
* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
