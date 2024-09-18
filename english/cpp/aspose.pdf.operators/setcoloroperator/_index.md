---
title: Aspose::Pdf::Operators::SetColorOperator class
linktitle: SetColorOperator
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetColorOperator class. Class representing set color operation in C++.'
type: docs
weight: 5300
url: /cpp/aspose.pdf.operators/setcoloroperator/
---
## SetColorOperator class


Class representing set color operation.

```cpp
class SetColorOperator : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Accept](../../aspose.pdf/operator/accept/)(System::SharedPtr\<IOperatorSelector\>) | Accepts visitor [IOperatorSelector](../../aspose.pdf/ioperatorselector/) which provides operators processing. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| virtual [getColor](./getcolor/)() | Retirns color specified by the operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
