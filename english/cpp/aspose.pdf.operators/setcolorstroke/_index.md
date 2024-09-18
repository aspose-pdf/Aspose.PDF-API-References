---
title: Aspose::Pdf::Operators::SetColorStroke class
linktitle: SetColorStroke
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetColorStroke class. Class representing SC operator set color for stroking color operators in C++.'
type: docs
weight: 5700
url: /cpp/aspose.pdf.operators/setcolorstroke/
---
## SetColorStroke class


Class representing SC operator set color for stroking color operators.

```cpp
class SetColorStroke : public Aspose::Pdf::Operators::BasicSetColorOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_B](./get_b/)() const | Gets the blue component. |
| [get_B](../basicsetcoloroperator/get_b/)() | Gets red component of color. |
| [get_C](./get_c/)() const | Gets the cyan component. |
| [get_C](../basicsetcoloroperator/get_c/)() | Gets cyan component of CMYK color. |
| virtual [get_Color](../basicsetcoloroperator/get_color/)() | Gets array of color components. |
| [get_G](./get_g/)() const | Gets the green component. |
| [get_G](../basicsetcoloroperator/get_g/)() | Gets green component of color. |
| [get_Gray](../basicsetcoloroperator/get_gray/)() | Gets black component of gray color. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_K](./get_k/)() const | Gets the black component. |
| [get_K](../basicsetcoloroperator/get_k/)() | Gets black component of CMYK color. |
| [get_M](./get_m/)() const | Gets the magenta component. |
| [get_M](../basicsetcoloroperator/get_m/)() | Gets magenta component of CMYK color. |
| [get_R](./get_r/)() const | Gets the red component. |
| [get_R](../basicsetcoloroperator/get_r/)() | Gets red component of color. |
| [get_Y](./get_y/)() const | Gets the yellow component. |
| [get_Y](../basicsetcoloroperator/get_y/)() | Gets yellow component of CMYK color. |
| [getColor](./getcolor/)() override | Returns color specified by operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_B](./set_b/)(double) | Sets the blue component. |
| [set_C](./set_c/)(double) | Sets the cyan component. |
| [set_G](./set_g/)(double) | Sets the green component. |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_K](./set_k/)(double) | Sets the black component. |
| [set_M](./set_m/)(double) | Sets the magenta component. |
| [set_R](./set_r/)(double) | Sets the red component. |
| [set_Y](./set_y/)(double) | Sets the yellow component. |
| [SetColorStroke](./setcolorstroke/)() | Initializes operator. |
| [SetColorStroke](./setcolorstroke/)(double) | Set color for stroking operators for DeviceGray, CalGray and Indexed color spaces. |
| [SetColorStroke](./setcolorstroke/)(double, double, double) | Set color for stroking operator for DeviceRGB, CalRGB, and Lab color spaces. |
| [SetColorStroke](./setcolorstroke/)(System::ArrayPtr\<double\>) | Constructor which allows to set color components. |
| [SetColorStroke](./setcolorstroke/)(double, double, double, double) | Set color for stroking operator for CMYK color space. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [BasicSetColorOperator](../basicsetcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
