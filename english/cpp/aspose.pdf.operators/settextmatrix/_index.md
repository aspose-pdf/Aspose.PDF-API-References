---
title: Aspose::Pdf::Operators::SetTextMatrix class
linktitle: SetTextMatrix
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetTextMatrix class. Class representing Tm operator (set text matrix) in C++.'
type: docs
weight: 7200
url: /cpp/aspose.pdf.operators/settextmatrix/
---
## SetTextMatrix class


Class representing Tm operator (set text matrix).

```cpp
class SetTextMatrix : public Aspose::Pdf::Operators::TextPlaceOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_Matrix](./get_matrix/)() const | [Matrix](../../aspose.pdf/matrix/) argument of the operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_Matrix](./set_matrix/)(System::SharedPtr\<Aspose::Pdf::Matrix\>) | [Matrix](../../aspose.pdf/matrix/) argument of the operator. |
| [SetTextMatrix](./settextmatrix/)(double, double, double, double, double, double) | Initializes operator. |
| [SetTextMatrix](./settextmatrix/)(System::SharedPtr\<Aspose::Pdf::Matrix\>) | Initializes operator by matrix. |
| [TextOperator](../textoperator/textoperator/)() | Initializes operator. |
| [TextOperator](../textoperator/textoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | [Text](../../aspose.pdf.text/) operator which accepts text properties. |
| [TextPlaceOperator](../textplaceoperator/textplaceoperator/)() | Initializes [TextPlaceOperator](../textplaceoperator/). |
| [TextPlaceOperator](../textplaceoperator/textplaceoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | Initializes [TextPlaceOperator](../textplaceoperator/) which accepts TextProperties. |
| [ToString](./tostring/)() const override | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [TextPlaceOperator](../textplaceoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
