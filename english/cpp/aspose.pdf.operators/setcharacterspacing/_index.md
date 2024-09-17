---
title: Aspose::Pdf::Operators::SetCharacterSpacing class
linktitle: SetCharacterSpacing
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetCharacterSpacing class. Class representing Tc operator (set character spacing) in C++.'
type: docs
weight: 4700
url: /cpp/aspose.pdf.operators/setcharacterspacing/
---
## SetCharacterSpacing class


Class representing Tc operator (set character spacing).

```cpp
class SetCharacterSpacing : public Aspose::Pdf::Operators::TextStateOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_CharSpacing](./get_charspacing/)() const | Gets the character spacing. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_CharSpacing](./set_charspacing/)(double) | Sets the character spacing. |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [SetCharacterSpacing](./setcharacterspacing/)(double) | Initializes operator. |
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
