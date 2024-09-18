---
title: Aspose::Pdf::Operators::BasicSetColorAndPatternOperator class
linktitle: BasicSetColorAndPatternOperator
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::BasicSetColorAndPatternOperator class. Base operator for all Set Color operators in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.operators/basicsetcolorandpatternoperator/
---
## BasicSetColorAndPatternOperator class


Base operator for all Set [Color](../../aspose.pdf/color/) operators.

```cpp
class BasicSetColorAndPatternOperator : public Aspose::Pdf::Operators::BasicSetColorOperator
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Accept](../../aspose.pdf/operator/accept/)(System::SharedPtr\<IOperatorSelector\>) | Accepts visitor [IOperatorSelector](../../aspose.pdf/ioperatorselector/) which provides operators processing. |
| [get_B](../basicsetcoloroperator/get_b/)() | Gets red component of color. |
| [get_C](../basicsetcoloroperator/get_c/)() | Gets cyan component of CMYK color. |
| virtual [get_Color](../basicsetcoloroperator/get_color/)() | Gets array of color components. |
| [get_G](../basicsetcoloroperator/get_g/)() | Gets green component of color. |
| [get_Gray](../basicsetcoloroperator/get_gray/)() | Gets black component of gray color. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_K](../basicsetcoloroperator/get_k/)() | Gets black component of CMYK color. |
| [get_M](../basicsetcoloroperator/get_m/)() | Gets magenta component of CMYK color. |
| [get_PatternName](./get_patternname/)() const | Gets Pattern Name. |
| [get_R](../basicsetcoloroperator/get_r/)() | Gets red component of color. |
| [get_Y](../basicsetcoloroperator/get_y/)() | Gets yellow component of CMYK color. |
| virtual [getColor](../setcoloroperator/getcolor/)() | Retirns color specified by the operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [BasicSetColorOperator](../basicsetcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
