---
title: Aspose::Pdf::Operators::BasicSetColorOperator class
linktitle: BasicSetColorOperator
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::BasicSetColorOperator class. Base class for set color operators in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.operators/basicsetcoloroperator/
---
## BasicSetColorOperator class


Base class for set color operators.

```cpp
class BasicSetColorOperator : public Aspose::Pdf::Operators::SetColorOperator
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Accept](../../aspose.pdf/operator/accept/)(System::SharedPtr\<IOperatorSelector\>) | Accepts visitor [IOperatorSelector](../../aspose.pdf/ioperatorselector/) which provides operators processing. |
| [get_B](./get_b/)() | Gets red component of color. |
| [get_C](./get_c/)() | Gets cyan component of CMYK color. |
| virtual [get_Color](./get_color/)() | Gets array of color components. |
| [get_G](./get_g/)() | Gets green component of color. |
| [get_Gray](./get_gray/)() | Gets black component of gray color. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_K](./get_k/)() | Gets black component of CMYK color. |
| [get_M](./get_m/)() | Gets magenta component of CMYK color. |
| [get_R](./get_r/)() | Gets red component of color. |
| [get_Y](./get_y/)() | Gets yellow component of CMYK color. |
| virtual [getColor](../setcoloroperator/getcolor/)() | Retirns color specified by the operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [SetColorOperator](../setcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
