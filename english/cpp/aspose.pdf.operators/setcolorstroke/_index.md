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
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Accepts visitor object to process operator. |
| [get_B](./get_b/)() | Gets the blue component. |
| [get_C](./get_c/)() | Gets the cyan component. |
| [get_G](./get_g/)() | Gets the green component. |
| [get_K](./get_k/)() | Gets the black component. |
| [get_M](./get_m/)() | Gets the magenta component. |
| [get_R](./get_r/)() | Gets the red component. |
| [get_Y](./get_y/)() | Gets the yellow component. |
| [getColor](./getcolor/)() override | Returns color specified by operator. |
| [set_B](./set_b/)(double) | Sets the blue component. |
| [set_C](./set_c/)(double) | Sets the cyan component. |
| [set_G](./set_g/)(double) | Sets the green component. |
| [set_K](./set_k/)(double) | Sets the black component. |
| [set_M](./set_m/)(double) | Sets the magenta component. |
| [set_R](./set_r/)(double) | Sets the red component. |
| [set_Y](./set_y/)(double) | Sets the yellow component. |
| [SetColorStroke](./setcolorstroke/)() | Initializes operator. |
| [SetColorStroke](./setcolorstroke/)(double) | Set color for stroking operators for DeviceGray, CalGray and Indexed color spaces. |
| [SetColorStroke](./setcolorstroke/)(double, double, double) | Set color for stroking operator for DeviceRGB, CalRGB, and Lab color spaces. |
| [SetColorStroke](./setcolorstroke/)(System::ArrayPtr\<double\>) | Constructor which allows to set color components. |
| [SetColorStroke](./setcolorstroke/)(double, double, double, double) | Set color for stroking operator for CMYK color space. |
## See Also

* Class [BasicSetColorOperator](../basicsetcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
