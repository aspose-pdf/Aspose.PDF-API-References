---
title: Aspose::Pdf::Operators::SetCharWidth class
linktitle: SetCharWidth
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetCharWidth class. Class representing d0 operator (set glyph width) in C++.'
type: docs
weight: 4800
url: /cpp/aspose.pdf.operators/setcharwidth/
---
## SetCharWidth class


Class representing d0 operator (set glyph width).

```cpp
class SetCharWidth : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_Wx](./get_wx/)() const | Horizontal displacement of glyph coordinate. |
| [get_Wy](./get_wy/)() const | Vertical displacement of glyph coordinate. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [SetCharWidth](./setcharwidth/)(double, double) | Constructor. |
| [ToString](./tostring/)() const override | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
