---
title: Aspose::Pdf::Operators::SetRGBColor class
linktitle: SetRGBColor
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetRGBColor class. Class representing rg operator (set RGB color for non-stroking operators) in C++.'
type: docs
weight: 6800
url: /cpp/aspose.pdf.operators/setrgbcolor/
---
## SetRGBColor class


Class representing rg operator (set RGB color for non-stroking operators).

```cpp
class SetRGBColor : public Aspose::Pdf::Operators::SetColorOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Accepts visitor object to process operator. |
| [get_B](./get_b/)() const | Gets the blue component. |
| [get_G](./get_g/)() const | Gets the green component. |
| [get_R](./get_r/)() const | Gets the red component. |
| [getColor](./getcolor/)() override | Returns color specified by operator. |
| [set_B](./set_b/)(double) | Sets the blue component. |
| [set_G](./set_g/)(double) | Sets the green component. |
| [set_R](./set_r/)(double) | Sets the red component. |
| [SetRGBColor](./setrgbcolor/)(double, double, double) | Initializes operator. |
| [SetRGBColor](./setrgbcolor/)(System::Drawing::Color) | Initializes operator with color. |
| [ToString](./tostring/)() const override | Returns text representation of the operator. |
## See Also

* Class [SetColorOperator](../setcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
