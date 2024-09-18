---
title: Aspose::Pdf::Operators::BT class
linktitle: BT
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::BT class. Class representing BT operator (Begin of text block) in C++.'
type: docs
weight: 700
url: /cpp/aspose.pdf.operators/bt/
---
## BT class


Class representing [BT](./) operator (Begin of text block).

```cpp
class BT : public Aspose::Pdf::Operators::BlockTextOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [BlockTextOperator](../blocktextoperator/blocktextoperator/)() | Initializes operator. |
| [BlockTextOperator](../blocktextoperator/blocktextoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | Initializes [BlockTextOperator](../blocktextoperator/) which accepts TextProperties. |
| [BT](./bt/)() | Initializes operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [TextOperator](../textoperator/textoperator/)() | Initializes operator. |
| [TextOperator](../textoperator/textoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | [Text](../../aspose.pdf.text/) operator which accepts text properties. |
| [ToString](./tostring/)() const override | Produces text code of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [BlockTextOperator](../blocktextoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
