---
title: Aspose::Pdf::Operators::MoveToNextLine class
linktitle: MoveToNextLine
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::MoveToNextLine class. Class representing T* operator (Move to start of the next line) in C++.'
type: docs
weight: 3900
url: /cpp/aspose.pdf.operators/movetonextline/
---
## MoveToNextLine class


Class representing T* operator (Move to start of the next line).

```cpp
class MoveToNextLine : public Aspose::Pdf::Operators::TextPlaceOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [MoveToNextLine](./movetonextline/)() | Initializes operator. |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [TextOperator](../textoperator/textoperator/)() | Initializes operator. |
| [TextOperator](../textoperator/textoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | [Text](../../aspose.pdf.text/) operator which accepts text properties. |
| [TextPlaceOperator](../textplaceoperator/textplaceoperator/)() | Initializes [TextPlaceOperator](../textplaceoperator/). |
| [TextPlaceOperator](../textplaceoperator/textplaceoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | Initializes [TextPlaceOperator](../textplaceoperator/) which accepts TextProperties. |
| [ToString](./tostring/)() const override | Returns text of the operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [TextPlaceOperator](../textplaceoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
