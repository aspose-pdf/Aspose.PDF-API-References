---
title: System::Drawing::Drawing2D::CombineMode enum
linktitle: CombineMode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Drawing2D::CombineMode enum. Specifies how clipping regions are combined in C++.'
type: docs
weight: 1400
url: /cpp/system.drawing.drawing2d/combinemode/
---
## CombineMode enum


Specifies how clipping regions are combined.

```cpp
enum class CombineMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Replace | 0 | One clipping region is replaced by another. |
| Intersect | 1 | The two clipping regions are combined by taking their intersection. |
| Union | 2 | The two clipping regions are combined by taking the union of both. |
| Xor | 3 | The two clipping regions are combined by taking only the area enclosed by one or the other regions, but not both. |
| Exclude | 4 | Two clipping regions are combined by taking the area of the first region that does not intersect with the second. |
| Complement | 5 | Two clipping regions are combined by taking the area of the second region that does not intersect with the first. |

## See Also

* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
