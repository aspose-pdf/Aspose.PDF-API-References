---
title: System::Drawing::Region class
linktitle: Region
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Region class. Represents the interior of a graphic shape. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2100
url: /cpp/system.drawing/region/
---
## Region class


Represents the interior of a graphic shape. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Region : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() const | Returns a copy of the current object. |
| [Complement](./complement/)(const RectangleF\&) | Replaces the region represented by the current object with the portion of the region defined by the specified recangle that does not intersect with this region. |
| [Complement](./complement/)(const Rectangle\&) | Replaces the region represented by the current object with the portion of the region defined by the specified recangle that does not intersect with this region. |
| [Complement](./complement/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Replaces the region represented by the current object with the portion of the region defined by the specified path that does not intersect with this region. |
| [Complement](./complement/)(const SharedPtr\<Region\>\&) | Replaces the region represented by the current object with the portion of the specified region that does not intersect with this region. |
| [Dispose](./dispose/)() | Releases all operating system resources acquired by the current object. |
| [Equals](./equals/)(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) | Determines whether the specified region is identical to the region represented by the current object on the specified drawing surface. |
| [Exclude](./exclude/)(const RectangleF\&) | Replaces the region represented by the current object with the result of exclusion of the region defined by the specified rectange from it. |
| [Exclude](./exclude/)(const Rectangle\&) | Replaces the region represented by the current object with the result of exclusion of the region defined by the specified rectange from it. |
| [Exclude](./exclude/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Replaces the region represented by the current object with the result of exclusion of the region defined by the specified path from it. |
| [Exclude](./exclude/)(const SharedPtr\<Region\>\&) | Replaces the region represented by the current object with the result of exclusion of the specified region from it. |
| [GetBounds](./getbounds/)(const SharedPtr\<Graphics\>\&) const | Gets a [RectangleF](../rectanglef/) structure that represents a rectangle that bounds this [Region](./) on the drawing surface of a [Graphics](../graphics/) object. |
| [GetRegionData](./getregiondata/)() const | Returns a RegionData object containing data that defines the region represented by the current object. |
| [GetRegionScans](./getregionscans/)(const SharedPtr\<Drawing2D::Matrix\>\&) const | Returns an array of [RectangleF](../rectanglef/) structures that approximate this [Region](./) after the specified matrix transformation is applied. |
| [Intersect](./intersect/)(const RectangleF\&) | Replaces the region represented by the current object with the result of intersection of this region and a region defined by the specified rectangle. |
| [Intersect](./intersect/)(const Rectangle\&) | Replaces the region represented by the current object with the result of intersection of this region and a region defined by the specified rectangle. |
| [Intersect](./intersect/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Replaces the region represented by the current object with the result of intersection of this region and a region defined by the specified path. |
| [Intersect](./intersect/)(const SharedPtr\<Region\>\&) | Replaces the region represented by the current object with the result of intersection of this region and the specified region. |
| [IsEmpty](./isempty/)(const SharedPtr\<Graphics\>\&) const | Determines wheter the region represented by the current object has empty interior on the specified drawing surface. |
| [IsInfinite](./isinfinite/)(const SharedPtr\<Graphics\>\&) const | Determines wheter the region represented by the current object has infinite interior on the specified drawing surface. |
| [IsVisible](./isvisible/)(const Point\&) const | Determines if the specified point is contained within the region represented by the current object. |
| [IsVisible](./isvisible/)(const PointF\&) const | Determines if the specified point is contained within the region represented by the current object. |
| [IsVisible](./isvisible/)(const Rectangle\&) | Determines if any portion the specified rectangle is contained within the region represented by the current object. |
| [IsVisible](./isvisible/)(const RectangleF\&) | Determines if any portion the specified rectangle is contained within the region represented by the current object. |
| [IsVisible](./isvisible/)(const Point\&, const SharedPtr\<Graphics\>\&) const | Determines if the specified point is contained within the region represented by the current object using the specified graphics. |
| [IsVisible](./isvisible/)(const PointF\&, const SharedPtr\<Graphics\>\&) const | Determines if the specified point is contained within the region represented by the current object using the specified graphics. |
| [IsVisible](./isvisible/)(const Rectangle\&, const SharedPtr\<Graphics\>\&) | Determines if any portion the specified rectangle is contained within the region represented by the current object using the specified graphics. |
| [IsVisible](./isvisible/)(const RectangleF\&, const SharedPtr\<Graphics\>\&) | Determines if any portion the specified rectangle is contained within the region represented by the current object using the specified graphics. |
| [IsVisible](./isvisible/)(float, float) const | Determines if the specified point is contained within the region represented by the current object. |
| [IsVisible](./isvisible/)(float, float, const SharedPtr\<Graphics\>\&) const | Determines if the specified point is contained within the region represented by the current object using the specified graphics. |
| [MakeEmpty](./makeempty/)() | Initializes the current object to empty interior. |
| [MakeInfinite](./makeinfinite/)() | Initializes this region object to an infinite interior. |
| [Region](./region/)() | Constructs a new instance of [Region](./) class. |
| [Region](./region/)(const RectangleF\&) | Constructs a new instance of [Region](./) class that represents a region defined by the specified rectangle. |
| [Region](./region/)(const Rectangle\&) | Constructs a new instance of [Region](./) class that represents a region defined by the specified rectangle. |
| [Region](./region/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Constructs a new instance of [Region](./) class that represents a region defined by the specified path. |
| [Region](./region/)(const SkPath\&) |  |
| [Region](./region/)(const SharedPtr\<Drawing2D::RegionData\>\&) | Constructs a new instance of [Region](./) class that represents a region defined by the specified RegionData object. |
| [Transform](./transform/)(const SharedPtr\<Drawing2D::Matrix\>\&) | Transforms this region by the specified matrix. |
| [Transform](./transform/)(const SkMatrix\&) | Transforms this region by the specified matrix. |
| [Translate](./translate/)(int, int) | Moves the coordinates of the region by the specified amount. |
| [Translate](./translate/)(float, float) | Moves the coordinates of the region by the specified amount. |
| [Union](./union/)(const RectangleF\&) | Replaces the region represented by the current object with the result of union operation of this region and a region defined by the specified rectangle. |
| [Union](./union/)(const Rectangle\&) | Replaces the region represented by the current object with the result of union of this region and a region defined by the specified rectangle. |
| [Union](./union/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Replaces the region represented by the current object with the result of union of this region and a region defined by the specified path. |
| [Union](./union/)(const SharedPtr\<Region\>\&) | Replaces the region represented by the current object with the result of union of this region and and the specified region. |
| [Xor](./xor/)(const RectangleF\&) | Replaces the region represented by the current object with the portions of this region and the region defined by the specified recangle that do not intersect. |
| [Xor](./xor/)(const Rectangle\&) | Replaces the region represented by the current object with the portions of this region and the region defined by the specified recangle that do not intersect. |
| [Xor](./xor/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Replaces the region represented by the current object with the portions of this region and the region defined by the specified path that do not intersect. |
| [Xor](./xor/)(const SharedPtr\<Region\>\&) | Replaces the region represented by the current object with the portions of this region and the specified region that do not intersect. |
| virtual [~Region](./~region/)() | Destructor. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
