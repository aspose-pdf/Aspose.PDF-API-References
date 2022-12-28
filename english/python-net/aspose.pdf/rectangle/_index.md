---
title: Rectangle
second_title: Aspose.PDF for Python via .NET API Reference
description: Class represents rectangle.
type: docs
weight: 1320
url: /python-net/aspose.pdf/rectangle/
---

## Rectangle class

Class represents rectangle.

The Rectangle type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Rectangle(llx, lly, urx, ury, normalize_coordinates)|Initializes a new instance of the Rectangle class|
## Properties
| Name | Description |
| :- | :- |
|width|Width of rectangle.|
|height|Height of rectangle.|
|llx|X-coordinate of lower - left corner.|
|lly|Y - coordinate of lower-left corner.|
|urx|X - coordinate of upper-right corner.|
|ury|Y - coordinate of upper-right corner.|
|trivial|Initializes trivial rectangle i.e. rectangle with zero position and size.|
|is_trivial|Checks if rectangle is trivial i.e. has zero size and position.|
|is_empty|Checks if rectangle is empty.|
|is_point|Checks if rectangle is point i.e. LLX is equal URX and LLY is equal URY.|
|empty|Empty rectangle|
## Methods
| Name | Description |
| :- | :- |
|rotate(angle)|Rotate rectangle by the specified angle.|
|rotate(angle)|Rotate rectangle by the specified angle.|
|to_rect()|Converts rectangle to instance of System.Drawing.Rectangle. Floating-point positions and size are truncated.|
|from_rect(src)|Initializes new rectangle from given instance of System.Drawing.Rectangle.|
|parse(value)|Try to parse string and extract from it rectangle components llx, lly, urx, ury.|
|equals(other)|Check if rectangles are equal i.e. have same position and sizes.|
|near_equals(other, delta)|Check if rectangles are near equal i.e. have near same (up to delta) position and sizes.|
|intersect(other_rect)|Intersects to rectangles.|
|join(other_rect)|Joins rectangles.|
|is_intersect(other_rect)|Determines whether this rectangle intersects with other rectangle.|
|contains(point)|Determinces whether given point is inside of the rectangle.|
|center()|Returncs coordinates of center of the rectangle.|
|clone()|Clones the Rectangle object.|
|to_points()|Converts rectangle into array of points ("QuadPoints").|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

