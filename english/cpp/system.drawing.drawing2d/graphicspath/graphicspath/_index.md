---
title: System::Drawing::Drawing2D::GraphicsPath::GraphicsPath constructor
linktitle: GraphicsPath
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Drawing2D::GraphicsPath::GraphicsPath constructor. Constructs a new instance of GraphicsPath object that represents the specified path in C++.'
type: docs
weight: 100
url: /cpp/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) constructor


Constructs a new instance of [GraphicsPath](../) object that represents the specified path.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pts | const ArrayPtr\<Point\>\& | An array containing the points that specify the path to be represented by the object being created |
| types | const ArrayPtr\<uint8_t\>\& | An array containing the values tha specify the types of the corresponding points in **pts** array |
| fillMode | FillMode | Specifies how the interior of the closed path represented by the object being created should be filled |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../../system.drawing/point/)
* Enum [FillMode](../../fillmode/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.PDF for C++](../../../)
## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) constructor


Constructs a new instance of [GraphicsPath](../) object that represents the specified path.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pts | const ArrayPtr\<PointF\>\& | An array containing the points that specify the path to be represented by the object being created |
| types | const ArrayPtr\<uint8_t\>\& | An array containing the values tha specify the types of the corresponding points in **pts** array |
| fillMode | FillMode | Specifies how the interior of the closed path represented by the object being created should be filled |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PointF](../../../system.drawing/pointf/)
* Enum [FillMode](../../fillmode/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.PDF for C++](../../../)
## GraphicsPath::GraphicsPath(const SkPath\&) constructor




```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## See Also

* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.PDF for C++](../../../)
## GraphicsPath::GraphicsPath(FillMode) constructor


Constructs a new instance of [GraphicsPath](../) class with the specified fill mode.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fillMode | FillMode | Specifies how the interior of the closed path represented by the object being created should be filled |

## See Also

* Enum [FillMode](../../fillmode/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.PDF for C++](../../../)
