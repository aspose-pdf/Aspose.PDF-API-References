---
title: System::Drawing::Drawing2D::CustomLineCap class
linktitle: CustomLineCap
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Drawing2D::CustomLineCap class. Represents a user-defined line cap. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 400
url: /cpp/system.drawing.drawing2d/customlinecap/
---
## CustomLineCap class


Represents a user-defined line cap. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CustomLineCap : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Clone](./clone/)() | Returns a copy of the current object. |
| [CustomLineCap](./customlinecap/)(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) | Constructs a new instance of [CustomLineCap](./) class that represents a user-defined line cap with the specified properties. |
| [Dispose](./dispose/)() | Releases all operating system resources acquired by the current object. |
| [get_BaseCap](./get_basecap/)() const | Returns the base line cap from which this custom cap is created. |
| [get_BaseInset](./get_baseinset/)() const | Returns the distance between the line and the cap. |
| [get_StrokeJoin](./get_strokejoin/)() const | Returns the [LineJoin](../linejoin/) value which determines how lines of this custom cap are joined. |
| [get_WidthScale](./get_widthscale/)() const | Returns the scale of this custom cap. |
| [GetStrokeCaps](./getstrokecaps/)(LineCap\&, LineCap\&) | Gets the start and end line caps of the custom cap represented by the current object. |
| [set_BaseCap](./set_basecap/)(LineCap) | Sets the base line cap value for this custom cap. |
| [set_BaseInset](./set_baseinset/)(float) | Sets the distance between the line and the cap. |
| [set_StrokeJoin](./set_strokejoin/)(LineJoin) | Sets the [LineJoin](../linejoin/) value which determines how lines of this custom cap are joined. |
| [set_WidthScale](./set_widthscale/)(float) | Sets the scale value of this custom cap. |
| [SetStrokeCaps](./setstrokecaps/)(LineCap, LineCap) | Sets the start and end line caps of the custom cap represented by the current object. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
