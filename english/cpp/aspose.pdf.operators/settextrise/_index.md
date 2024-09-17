---
title: Aspose::Pdf::Operators::SetTextRise class
linktitle: SetTextRise
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetTextRise class. Class representing Ts operator (set text rise) in C++.'
type: docs
weight: 7400
url: /cpp/aspose.pdf.operators/settextrise/
---
## SetTextRise class


Class representing Ts operator (set text rise).

```cpp
class SetTextRise : public Aspose::Pdf::Operators::TextStateOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_TextRise](./get_textrise/)() const | Gets the text rise. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_TextRise](./set_textrise/)(double) | Sets the text rise. |
| [SetTextRise](./settextrise/)(double) | Initializes operator. |
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
