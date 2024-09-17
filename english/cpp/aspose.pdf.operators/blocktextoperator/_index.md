---
title: Aspose::Pdf::Operators::BlockTextOperator class
linktitle: BlockTextOperator
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::BlockTextOperator class. Abstract base class for text block operators i.e. Begin and End text operators (BT/ET) in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf.operators/blocktextoperator/
---
## BlockTextOperator class


Abstract base class for text block operators i.e. Begin and End text operators (BT/ET)

```cpp
class BlockTextOperator : public Aspose::Pdf::Operators::TextOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](../textoperator/accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [BlockTextOperator](./blocktextoperator/)() | Initializes operator. |
| [BlockTextOperator](./blocktextoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | Initializes [BlockTextOperator](./) which accepts TextProperties. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [TextOperator](../textoperator/textoperator/)() | Initializes operator. |
| [TextOperator](../textoperator/textoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | [Text](../../aspose.pdf.text/) operator which accepts text properties. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [TextOperator](../textoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
