---
title: Aspose::Pdf::Operators::SetTextRenderingMode class
linktitle: SetTextRenderingMode
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetTextRenderingMode class. Class representing Tr operator (set text rendering mode) in C++.'
type: docs
weight: 7300
url: /cpp/aspose.pdf.operators/settextrenderingmode/
---
## SetTextRenderingMode class


Class representing Tr operator (set text rendering mode).

```cpp
class SetTextRenderingMode : public Aspose::Pdf::Operators::TextStateOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [SetTextRenderingMode](./settextrenderingmode/)() | Initializes operator. |
| [TextOperator](../textoperator/textoperator/)() | Initializes operator. |
| [TextOperator](../textoperator/textoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | [Text](../../aspose.pdf.text/) operator which accepts text properties. |
| [TextStateOperator](../textstateoperator/textstateoperator/)() | Initializes [TextStateOperator](../textstateoperator/). |
| [TextStateOperator](../textstateoperator/textstateoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | Initializes TextStateoperator which allows to pass TextProperties. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [TextStateOperator](../textstateoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
