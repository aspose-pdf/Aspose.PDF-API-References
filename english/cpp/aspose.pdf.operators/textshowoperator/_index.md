---
title: Aspose::Pdf::Operators::TextShowOperator class
linktitle: TextShowOperator
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::TextShowOperator class. Abstract base class for all operators which used to out text (Tj, TJ, etc) in C++.'
type: docs
weight: 8100
url: /cpp/aspose.pdf.operators/textshowoperator/
---
## TextShowOperator class


Abstract base class for all operators which used to out text (Tj, TJ, etc).

```cpp
class TextShowOperator : public Aspose::Pdf::Operators::TextOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](../textoperator/accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| virtual [get_Text](./get_text/)() | Gets text which operator out on the page. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| virtual [set_Text](./set_text/)(System::String) | Gets text which operator out on the page. |
| [TextOperator](../textoperator/textoperator/)() | Initializes operator. |
| [TextOperator](../textoperator/textoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | [Text](../../aspose.pdf.text/) operator which accepts text properties. |
| [TextShowOperator](./textshowoperator/)() | Initializes [TextShowOperator](./). |
| [TextShowOperator](./textshowoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | Initializes [TextShowOperator](./) which allows to pass TextProperties. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [TextOperator](../textoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
