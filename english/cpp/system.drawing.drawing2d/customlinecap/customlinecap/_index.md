---
title: System::Drawing::Drawing2D::CustomLineCap::CustomLineCap constructor
linktitle: CustomLineCap
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Drawing2D::CustomLineCap::CustomLineCap constructor. Constructs a new instance of CustomLineCap class that represents a user-defined line cap with the specified properties in C++.'
type: docs
weight: 100
url: /cpp/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap constructor


Constructs a new instance of [CustomLineCap](../) class that represents a user-defined line cap with the specified properties.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fillPath | const SharedPtr\<GraphicsPath\>\& | Specifies a fill for the custom cap |
| strokePath | const SharedPtr\<GraphicsPath\>\& | Specifies an outline of the custom cap |
| baseCap | LineCap | The base line cap from which the custom cap is created |
| baseInset | float | Specifies the distance between the line and the cap |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsPath](../../graphicspath/)
* Enum [LineCap](../../linecap/)
* Class [CustomLineCap](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.PDF for C++](../../../)
