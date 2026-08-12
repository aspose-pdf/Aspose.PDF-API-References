---
title: "System::Drawing::Graphics::FillClosedCurve метод"
linktitle: "FillClosedCurve"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Graphics::FillClosedCurve метод. Рисует закрытый сплайн, используя указанную кисть в C++."
type: docs
weight: 3200
url: /ru/cpp/system.drawing/graphics/fillclosedcurve/
---
## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode, float) method


Отрисовывает замкнутый сплайн, используя указанную кисть.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | const SharedPtr\<Brush\>\& | Кисть, используемая при рисовании сплайна |
| points | const ArrayPtr\<Point\>\& | [Array](../../../system/array/) точек, определяющих сплайн |
| fillmode | Drawing2D::FillMode | IGNORED |
| tension | float | Значение, определяющее натяжение сплайна |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Brush](../../brush/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../point/)
* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode, float) method


Отрисовывает замкнутый сплайн, используя указанную кисть.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | const SharedPtr\<Brush\>\& | Кисть, используемая при рисовании сплайна |
| points | const ArrayPtr\<PointF\>\& | [Array](../../../system/array/) точек, определяющих сплайн |
| fillmode | Drawing2D::FillMode | IGNORED |
| tension | float | Значение, определяющее натяжение сплайна |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Brush](../../brush/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PointF](../../pointf/)
* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
