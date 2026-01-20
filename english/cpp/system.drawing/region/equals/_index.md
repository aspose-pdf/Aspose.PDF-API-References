---
title: System::Drawing::Region::Equals method
linktitle: Equals
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Region::Equals method. Determines whether the specified region is identical to the region represented by the current object on the specified drawing surface in C++.'
type: docs
weight: 600
url: /cpp/system.drawing/region/equals/
---
## Region::Equals method


Determines whether the specified region is identical to the region represented by the current object on the specified drawing surface.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```


| Parameter | Type | Description |
| --- | --- | --- |
| r | const SharedPtr\<Region\>\& | The region to compare this region with |
| g | const SharedPtr\<Graphics\>\& | A drawing surface |

### ReturnValue

True if the interior of the specified region is identical to the interior of the region represented by the current objcet when the transformation associated with the **g** parameter is applied; otherwise - false

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../)
* Class [Graphics](../../graphics/)
* Class [Region](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
