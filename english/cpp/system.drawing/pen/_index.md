---
title: System::Drawing::Pen class
linktitle: Pen
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Pen class. Represents properties such as color, width etc. of the lines and curves being drawn. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1500
url: /cpp/system.drawing/pen/
---
## Pen class


Represents properties such as color, width etc. of the lines and curves being drawn. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Pen : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() | Returns a copy of the current object. |
| [Dispose](./dispose/)() | Releases all operating resources acquired by the current object. |
| [get_Alignment](./get_alignment/)() const | Returns a value that indicates the alignment of the current [Pen](./) object. |
| [get_Brush](./get_brush/)() | Returns this pen's [Brush](../brush/) object. |
| [get_Color](./get_color/)() const | Returns this pen's color. |
| [get_CompoundArray](./get_compoundarray/)() const | Returns an array of values that specifies a compound pen. |
| [get_DashCap](./get_dashcap/)() const | Returns a value that indicates the cap used at the both ends of a dashed line. |
| [get_DashOffset](./get_dashoffset/)() const | Returns the distance from the start of a line to the beginning of a dash pattern. |
| [get_DashPattern](./get_dashpattern/)() const | Returns an array indicating custom dash pattern in a dashed line. |
| [get_DashStyle](./get_dashstyle/)() const | Returns a value that indicates the dash style of the current [Pen](./) object. |
| [get_EndCap](./get_endcap/)() const | Returns a value that indicates the ending line cap of the current [Pen](./) object. |
| [get_LineJoin](./get_linejoin/)() const | Returns a value that indicates how the lines drawn by this [Pen](./) object are joined. |
| [get_MiterLimit](./get_miterlimit/)() const | Returns the limit of the thickness of the join on a mitered corner. |
| [get_PenType](./get_pentype/)() const | NOT IMPLEMENTED. |
| [get_StartCap](./get_startcap/)() const | Returns a value that indicates the starting line cap of the current [Pen](./) object. |
| [get_Transform](./get_transform/)() | Returns a copy of a Matrix object that specifies the geometrical transformations for the pen represneted by the current object. |
| [get_Width](./get_width/)() const | Returns the width of the current [Pen](./) object. |
| [MultiplyTransform](./multiplytransform/)(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) | Multiplies current object's transform matrix by the specified matrix. |
| [Pen](./pen/)(const Color\&) | Constructs a new [Pen](./) object representing the specified color. |
| [Pen](./pen/)(const Color\&, float) | Constructs a new [Pen](./) object representing the specified color and width. |
| [Pen](./pen/)(const SharedPtr\<Brush\>\&) | Constructs a new [Pen](./) object and initializes it with the specified [Brush](../brush/) object. |
| [Pen](./pen/)(const SharedPtr\<Brush\>\&, float) | Constructs a new [Pen](./) object and initializes it with the specified [Brush](../brush/) object. |
| [ResetTransform](./resettransform/)() | Resets the current object's transform matrix so that it becomes an identity matrix. |
| [RotateTransform](./rotatetransform/)(float, Drawing2D::MatrixOrder) | Rotates the local geometric transformation by the specified angle in the specified order. |
| [ScaleTransform](./scaletransform/)(float, float, Drawing2D::MatrixOrder) | Scales the local geometric transformation by the specified factors in the specified order. |
| [set_Alignment](./set_alignment/)(Drawing2D::PenAlignment) | Sets the alignment of the current [Pen](./) object. |
| [set_Brush](./set_brush/)(const SharedPtr\<Brush\>\&) | Sets this pen's [Brush](../brush/) object. |
| [set_Color](./set_color/)(const Color\&) | Sets this pen's color. |
| [set_CompoundArray](./set_compoundarray/)(const System::ArrayPtr\<float\>\&) | Sets an array of values that specifies a compound pen. |
| [set_CustomEndCap](./set_customendcap/)(const SharedPtr\<Drawing2D::CustomLineCap\>\&) | Sets the custom end line cap. |
| [set_CustomStartCap](./set_customstartcap/)(const SharedPtr\<Drawing2D::CustomLineCap\>\&) | Sets the custom start line cap. |
| [set_DashCap](./set_dashcap/)(Drawing2D::DashCap) | Sets a value that specifies the cap used at the both ends of a dashed line. |
| [set_DashOffset](./set_dashoffset/)(float) | Sets the distance from the start of a line to the beginning of a dash pattern. |
| [set_DashPattern](./set_dashpattern/)(const System::ArrayPtr\<float\>\&) | Sets an array specifying custom dash pattern in a dashed line. The array consists of numbers that specify the lengths of alternating dashes and spaces. |
| [set_DashStyle](./set_dashstyle/)(Drawing2D::DashStyle) | Sets a value that specifies the dash style of the current [Pen](./) object. |
| [set_EndCap](./set_endcap/)(Drawing2D::LineCap) | Sets the ending line cap of the current [Pen](./) object. |
| [set_LineJoin](./set_linejoin/)(Drawing2D::LineJoin) | Sets a value that specifies how the lines drawn by this [Pen](./) object are joined. |
| [set_MiterLimit](./set_miterlimit/)(float) | Sets the limit of the thickness of the join on a mitered corner. |
| [set_StartCap](./set_startcap/)(Drawing2D::LineCap) | Sets the starting line cap of the current [Pen](./) object. |
| [set_Transform](./set_transform/)(const SharedPtr\<Drawing2D::Matrix\>\&) | Sets a Matrix object that specifies the geometrical transformations for the pen represneted by the current object. |
| [set_Width](./set_width/)(float) | Sets the width of the current [Pen](./) object. |
| [SetLineCap](./setlinecap/)(Drawing2D::LineCap, Drawing2D::LineCap, Drawing2D::DashCap) | NOT IMPLEMENTED. |
| [TranslateTransform](./translatetransform/)(float, float, Drawing2D::MatrixOrder) | Translates the local geometric transformation by the specified dimensions in the specified order. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
