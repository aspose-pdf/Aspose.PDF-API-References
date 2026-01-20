---
title: System::Drawing::Graphics::BeginContainer method
linktitle: BeginContainer
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Graphics::BeginContainer method. Saves a container with the current state of this object, opens and uses a new container and returns the saved container in C++.'
type: docs
weight: 600
url: /cpp/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() method


Saves a container with the current state of this object, opens and uses a new container and returns the saved container.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) method


Saves a container with the current state of this object, opens and uses a new container and returns the saved container.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```


| Parameter | Type | Description |
| --- | --- | --- |
| dstrect | Rectangle | The rectangle that specifies a scale transformation of the new container. Used together with **srcrect** |
| srcrect | Rectangle | The rectangle that specifies a scale transformation of the new container. Used together with **dstrect** |
| unit | GraphicsUnit | The value that specifies the unit of measure of the new container |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Class [Rectangle](../../rectangle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) method


Saves a container with the current state of this object, opens and uses a new container and returns the saved container.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```


| Parameter | Type | Description |
| --- | --- | --- |
| dstrect | RectangleF | The rectangle that specifies a scale transformation of the new container. Used together with **srcrect** |
| srcrect | RectangleF | The rectangle that specifies a scale transformation of the new container. Used together with **dstrect** |
| unit | GraphicsUnit | The value that specifies the unit of measure of the new container |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Class [RectangleF](../../rectanglef/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
