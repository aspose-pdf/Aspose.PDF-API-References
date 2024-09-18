---
title: Aspose::Pdf::Operators::TextStateOperator class
linktitle: TextStateOperator
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::TextStateOperator class. Abstract base class for operators which changes current text state (Tc, Tf, TL, etc) in C++.'
type: docs
weight: 8200
url: /cpp/aspose.pdf.operators/textstateoperator/
---
## TextStateOperator class


Abstract base class for operators which changes current text state (Tc, Tf, TL, etc).

```cpp
class TextStateOperator : public Aspose::Pdf::Operators::TextOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](../textoperator/accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [TextOperator](../textoperator/textoperator/)() | Initializes operator. |
| [TextOperator](../textoperator/textoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | [Text](../../aspose.pdf.text/) operator which accepts text properties. |
| [TextStateOperator](./textstateoperator/)() | Initializes [TextStateOperator](./). |
| [TextStateOperator](./textstateoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | Initializes TextStateoperator which allows to pass TextProperties. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [TextOperator](../textoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
