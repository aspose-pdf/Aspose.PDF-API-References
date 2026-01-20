---
title: System::Drawing::Point::Add method
linktitle: Add
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Point::Add method. Adds the width and height values of the specified Size object to the X and Y coordinates values of the specified Point object correspondingly in C++.'
type: docs
weight: 1500
url: /cpp/system.drawing/point/add/
---
## Point::Add method


Adds the width and height values of the specified [Size](../../size/) object to the X and Y coordinates values of the specified [Point](../) object correspondingly.

```cpp
static Point System::Drawing::Point::Add(const Point &point, const Size &size)
```


| Parameter | Type | Description |
| --- | --- | --- |
| point | const Point\& | The point to translate |
| size | const Size\& | The [Size](../../size/) object that specifies the values to add to the coordinates values of the **point** |

### ReturnValue

A new [Point](../) object whose X coordinate value is equal to the sum of X coordinate value of **point** and the width value of **size** and Y coordinate value is equal to the sum of Y coordinate value of **point** and the height value of **size**

## See Also

* Class [Point](../)
* Class [Size](../../size/)
* Class [Point](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
