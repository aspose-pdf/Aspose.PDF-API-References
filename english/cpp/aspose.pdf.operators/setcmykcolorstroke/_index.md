---
title: Aspose::Pdf::Operators::SetCMYKColorStroke class
linktitle: SetCMYKColorStroke
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetCMYKColorStroke class. Class representing K operator (set CMYK color for stroking operations) in C++.'
type: docs
weight: 5100
url: /cpp/aspose.pdf.operators/setcmykcolorstroke/
---
## SetCMYKColorStroke class


Class representing K operator (set CMYK color for stroking operations).

```cpp
class SetCMYKColorStroke : public Aspose::Pdf::Operators::SetColorOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Accepts visitor object to process operator. |
| [get_C](./get_c/)() const | Gets the cyan component. |
| [get_K](./get_k/)() const | Gets the black component. |
| [get_M](./get_m/)() const | Gets the magenta component. |
| [get_Y](./get_y/)() const | Gets the yellow component. |
| [getColor](./getcolor/)() override | Returns the RGB color. |
| [set_C](./set_c/)(double) | Sets the cyan component. |
| [set_K](./set_k/)(double) | Sets the black component. |
| [set_M](./set_m/)(double) | Sets the magenta component. |
| [set_Y](./set_y/)(double) | Sets the yellow component. |
| [SetCMYKColorStroke](./setcmykcolorstroke/)(double, double, double, double) | Initializes operator. |
## See Also

* Class [SetColorOperator](../setcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
