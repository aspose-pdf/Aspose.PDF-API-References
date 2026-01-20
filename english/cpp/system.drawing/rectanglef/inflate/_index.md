---
title: System::Drawing::RectangleF::Inflate method
linktitle: Inflate
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::RectangleF::Inflate method. Increases the width and height of the rectangle represented by the current object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the amounts specified by width and height values of the specified size object correspondingly in C++.'
type: docs
weight: 1600
url: /cpp/system.drawing/rectanglef/inflate/
---
## RectangleF::Inflate(const SizeF\&) method


Increases the width and height of the rectangle represented by the current object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the amounts specified by width and height values of the specified size object correspondingly.

```cpp
void System::Drawing::RectangleF::Inflate(const SizeF &size)
```


| Parameter | Type | Description |
| --- | --- | --- |
| size | const SizeF\& | The [SizeF](../../sizef/) object specifying the amounts to increase the width and height of the rectangle by |

## See Also

* Class [SizeF](../../sizef/)
* Class [RectangleF](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## RectangleF::Inflate(float, float) method


Increases the width and height of the rectangle represented by the current object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the specified amounts.

```cpp
void System::Drawing::RectangleF::Inflate(float width, float height)
```


| Parameter | Type | Description |
| --- | --- | --- |
| width | float | The amount by which the width of the rectangle is to be increased in both directions |
| height | float | The amount by which the height of the rectangle is to be increased in both directions |

## See Also

* Class [RectangleF](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## RectangleF::Inflate(const RectangleF\&, float, float) method


Increases the width and height of the rectangle represented by the specified object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the specified amounts.

```cpp
static RectangleF System::Drawing::RectangleF::Inflate(const RectangleF &rect, float x, float y)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | const RectangleF\& | A rectangle to inflate |
| x | float | The amount by which the width of the rectangle is to be increased in both directions |
| y | float | The amount by which the height of the rectangle is to be increased in both directions |

### ReturnValue

The [RectangleF](../) object representing the enlarged rectangle

## See Also

* Class [RectangleF](../)
* Class [RectangleF](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
