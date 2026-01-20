---
title: System::Drawing::Graphics::SetClip method
linktitle: SetClip
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Graphics::SetClip method. Sets the clipping region of drawing surface represented by the current Graphics object to the result of the specified operation that combines the current clip region and the region specified by a graphics path in C++.'
type: docs
weight: 8600
url: /cpp/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) method


Sets the clipping region of drawing surface represented by the current [Graphics](../) object to the result of the specified operation that combines the current clip region and the region specified by a graphics path.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const SharedPtr\<Drawing2D::GraphicsPath\>\& | Specifies a region to combine |
| combineMode | Drawing2D::CombineMode | Specifies the combining operation |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) method


NOT IMPLEMENTED.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Graphics](../)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) method


Sets the clipping region of drawing surface represented by the current [Graphics](../) object to the result of the specified operation that combines the current clip region and the specified region.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


| Parameter | Type | Description |
| --- | --- | --- |
| region | const SharedPtr\<Region\>\& | Specifies a region to combine |
| combineMode | Drawing2D::CombineMode | Specifies the combining operation |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../../region/)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) method


Sets the clipping region of drawing surface represented by the current [Graphics](../) object to the result of the specified operation that combines the current clip region and the specified region.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Specifies a region to combine |
| combineMode | Drawing2D::CombineMode | Specifies the combining operation |

## See Also

* Class [Rectangle](../../rectangle/)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) method


Sets the clipping region of drawing surface represented by the current [Graphics](../) object to the result of the specified operation that combines the current clip region and the specified region.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | RectangleF | Specifies a region to combine |
| combineMode | Drawing2D::CombineMode | Specifies the combining operation |

## See Also

* Class [RectangleF](../../rectanglef/)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
