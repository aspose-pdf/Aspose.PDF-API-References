---
title: System::Drawing::Drawing2D::PathData class
linktitle: PathData
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Drawing2D::PathData class. Contains the graphical data that represents a path. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1100
url: /cpp/system.drawing.drawing2d/pathdata/
---
## PathData class


Contains the graphical data that represents a path. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class PathData : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Points](./get_points/)() | Returns an array containing the points that make up a path. |
| [get_Types](./get_types/)() | Returns an array containing the values that specify the types of corresponding points in **Points** array. |
| [PathData](./pathdata/)() | Constructs an empty [PathData](./) object. |
| [set_Points](./set_points/)(const ArrayPtr\<PointF\>\&) | Sets an array containing the points that make up a path. |
| [set_Types](./set_types/)(const ArrayPtr\<uint8_t\>\&) | Sets an array containing the values that specify the types of corresponding points in **Points** array. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
