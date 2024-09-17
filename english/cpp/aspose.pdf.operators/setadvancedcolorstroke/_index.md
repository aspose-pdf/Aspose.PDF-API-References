---
title: Aspose::Pdf::Operators::SetAdvancedColorStroke class
linktitle: SetAdvancedColorStroke
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetAdvancedColorStroke class. Class representing SCN operator (set color for stroking operations) in C++.'
type: docs
weight: 4600
url: /cpp/aspose.pdf.operators/setadvancedcolorstroke/
---
## SetAdvancedColorStroke class


Class representing SCN operator (set color for stroking operations).

```cpp
class SetAdvancedColorStroke : public Aspose::Pdf::Operators::BasicSetColorAndPatternOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_B](../basicsetcoloroperator/get_b/)() | Gets red component of color. |
| [get_C](../basicsetcoloroperator/get_c/)() | Gets cyan component of CMYK color. |
| virtual [get_Color](../basicsetcoloroperator/get_color/)() | Gets array of color components. |
| [get_G](../basicsetcoloroperator/get_g/)() | Gets green component of color. |
| [get_Gray](../basicsetcoloroperator/get_gray/)() | Gets black component of gray color. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_K](../basicsetcoloroperator/get_k/)() | Gets black component of CMYK color. |
| [get_M](../basicsetcoloroperator/get_m/)() | Gets magenta component of CMYK color. |
| [get_PatternName](../basicsetcolorandpatternoperator/get_patternname/)() const | Gets Pattern Name. |
| [get_R](../basicsetcoloroperator/get_r/)() | Gets red component of color. |
| [get_Y](../basicsetcoloroperator/get_y/)() | Gets yellow component of CMYK color. |
| [getColor](./getcolor/)() override | Returns color specified by operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [SetAdvancedColorStroke](./setadvancedcolorstroke/)() | Initializes operator. |
| [SetAdvancedColorStroke](./setadvancedcolorstroke/)(double) | Constructor for scn operator. |
| [SetAdvancedColorStroke](./setadvancedcolorstroke/)(double, System::String) | Constructor for scn operator. |
| [SetAdvancedColorStroke](./setadvancedcolorstroke/)(double, double, double, System::String) | Constructor for scn operator. |
| [SetAdvancedColorStroke](./setadvancedcolorstroke/)(double, double, double, double, System::String) | Constructor for scn operator. |
| [SetAdvancedColorStroke](./setadvancedcolorstroke/)(System::ArrayPtr\<double\>, System::String) | Constructor for scn operator. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [BasicSetColorAndPatternOperator](../basicsetcolorandpatternoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
