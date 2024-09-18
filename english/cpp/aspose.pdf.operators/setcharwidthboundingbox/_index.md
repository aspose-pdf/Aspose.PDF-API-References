---
title: Aspose::Pdf::Operators::SetCharWidthBoundingBox class
linktitle: SetCharWidthBoundingBox
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetCharWidthBoundingBox class. Class representing d1 operator (set glyph and bounding box) in C++.'
type: docs
weight: 4900
url: /cpp/aspose.pdf.operators/setcharwidthboundingbox/
---
## SetCharWidthBoundingBox class


Class representing d1 operator (set glyph and bounding box).

```cpp
class SetCharWidthBoundingBox : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_Llx](./get_llx/)() const | Lower-left horizontal coordinate of bounding rectangle. |
| [get_Lly](./get_lly/)() const | Lower-left vertical coordinate of bounding rectangle. |
| [get_Urx](./get_urx/)() const | Upper-right horizontal coordinate of bounding rectangle. |
| [get_Ury](./get_ury/)() const | Upper-right vertical coordinate of bounding rectangle. |
| [get_Wx](./get_wx/)() const | Horizontal displacement of glyph. |
| [get_Wy](./get_wy/)() const | Vertical displacement of glyph. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [SetCharWidthBoundingBox](./setcharwidthboundingbox/)(double, double, double, double, double, double) | Initializes [SetCharWidthBoundingBox](./) operator. |
| [ToString](./tostring/)() const override | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
