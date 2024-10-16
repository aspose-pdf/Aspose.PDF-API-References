---
title: Aspose::Pdf::Operators::SetColor class
linktitle: SetColor
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetColor class. Represents class for sc operator (set color for non-stroking operations) in C++.'
type: docs
weight: 5200
url: /cpp/aspose.pdf.operators/setcolor/
---
## SetColor class


Represents class for sc operator (set color for non-stroking operations).

```cpp
class SetColor : public Aspose::Pdf::Operators::BasicSetColorOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_B](./get_b/)() const | Gets the blue component. |
| [get_C](./get_c/)() const | Gets the cyan component. |
| [get_G](./get_g/)() const | Gets the green component. |
| [get_K](./get_k/)() const | Gets the black component. |
| [get_M](./get_m/)() const | Gets the magenta component. |
| [get_R](./get_r/)() const | Gets the red component. |
| [get_Y](./get_y/)() const | Gets the yellow component. |
| [getColor](./getcolor/)() override | Returns color specified by the operator. |
| [set_B](./set_b/)(double) | Sets the blue component. |
| [set_C](./set_c/)(double) | Sets the cyan component. |
| [set_G](./set_g/)(double) | Sets the green component. |
| [set_K](./set_k/)(double) | Sets the black component. |
| [set_M](./set_m/)(double) | Sets the magenta component. |
| [set_R](./set_r/)(double) | Sets the red component. |
| [set_Y](./set_y/)(double) | Sets the yellow component. |
| [SetColor](./setcolor/)() | Initializes operator. |
| [SetColor](./setcolor/)(double) | Set color for stroking operators for DeviceGray, CalGray and Indexed color spaces. |
| [SetColor](./setcolor/)(double, double, double) | Set color for stroking operator for DeviceRGB, CalRGB, and Lab color spaces. |
| [SetColor](./setcolor/)(double, double, double, double) | Set color for non-stroking operator for CMYK color space. |
| [SetColor](./setcolor/)(System::ArrayPtr\<double\>) | Constructor which allows to specify color components. |
| [ToString](./tostring/)() const override | Returns string representation of color. |
## See Also

* Class [BasicSetColorOperator](../basicsetcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
