---
title: Aspose::Pdf::Operators::SetRGBColorStroke class
linktitle: SetRGBColorStroke
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetRGBColorStroke class. Class representing RG operator (set RGB color for stroking operators) in C++.'
type: docs
weight: 6900
url: /cpp/aspose.pdf.operators/setrgbcolorstroke/
---
## SetRGBColorStroke class


Class representing RG operator (set RGB color for stroking operators).

```cpp
class SetRGBColorStroke : public Aspose::Pdf::Operators::SetColorOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_B](./get_b/)() const | Gets the blue component. |
| [get_G](./get_g/)() const | Gets the green component. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_R](./get_r/)() const | Gets the red component. |
| [getColor](./getcolor/)() override | Returns color specified by operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_B](./set_b/)(double) | Sets the blue component. |
| [set_G](./set_g/)(double) | Sets the green component. |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_R](./set_r/)(double) | Sets the red component. |
| [SetRGBColorStroke](./setrgbcolorstroke/)(double, double, double) | Initializes operator. |
| [SetRGBColorStroke](./setrgbcolorstroke/)(System::Drawing::Color) | Initializes operator with color. |
| [ToString](./tostring/)() const override | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [SetColorOperator](../setcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
