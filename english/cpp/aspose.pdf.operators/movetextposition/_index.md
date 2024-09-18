---
title: Aspose::Pdf::Operators::MoveTextPosition class
linktitle: MoveTextPosition
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::MoveTextPosition class. Class representing Td operator (move text position) in C++.'
type: docs
weight: 3600
url: /cpp/aspose.pdf.operators/movetextposition/
---
## MoveTextPosition class


Class representing Td operator (move text position).

```cpp
class MoveTextPosition : public Aspose::Pdf::Operators::TextPlaceOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_X](./get_x/)() const | X coordinate of text position. |
| [get_Y](./get_y/)() const | Y coordinate of text position. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [MoveTextPosition](./movetextposition/)(double, double) | Initializes operator. |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_X](./set_x/)(double) | X coordinate of text position. |
| [set_Y](./set_y/)(double) | Y coordinate of text position. |
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
