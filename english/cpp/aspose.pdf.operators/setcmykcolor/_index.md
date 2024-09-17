---
title: Aspose::Pdf::Operators::SetCMYKColor class
linktitle: SetCMYKColor
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetCMYKColor class. Class representing k operator (set CMYK color for non-stroking operations) in C++.'
type: docs
weight: 5000
url: /cpp/aspose.pdf.operators/setcmykcolor/
---
## SetCMYKColor class


Class representing k operator (set CMYK color for non-stroking operations).

```cpp
class SetCMYKColor : public Aspose::Pdf::Operators::SetColorOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_C](./get_c/)() const | Gets the cyan component. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_K](./get_k/)() const | Gets the black component. |
| [get_M](./get_m/)() const | Gets the magenta component. |
| [get_Y](./get_y/)() const | Gets the yellow component. |
| [getColor](./getcolor/)() override | Returns color. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_C](./set_c/)(double) | Sets the cyan component. |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_K](./set_k/)(double) | Sets the black component. |
| [set_M](./set_m/)(double) | Sets the magenta component. |
| [set_Y](./set_y/)(double) | Sets the yellow component. |
| [SetCMYKColor](./setcmykcolor/)(double, double, double, double) | Initializes operator. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [SetColorOperator](../setcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
