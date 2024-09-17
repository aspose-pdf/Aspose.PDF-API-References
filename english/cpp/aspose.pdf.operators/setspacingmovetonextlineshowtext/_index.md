---
title: Aspose::Pdf::Operators::SetSpacingMoveToNextLineShowText class
linktitle: SetSpacingMoveToNextLineShowText
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetSpacingMoveToNextLineShowText class. Class representing " operator (set word and character spacing, move to the next line and show text) in C++.'
type: docs
weight: 7000
url: /cpp/aspose.pdf.operators/setspacingmovetonextlineshowtext/
---
## SetSpacingMoveToNextLineShowText class


Class representing " operator (set word and character spacing, move to the next line and show text).

```cpp
class SetSpacingMoveToNextLineShowText : public Aspose::Pdf::Operators::TextShowOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Ac](./get_ac/)() const | Get character spacing. |
| [get_Aw](./get_aw/)() const | Gets word spacing. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_Text](./get_text/)() override | Gets text of operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| virtual [set_Text](../textshowoperator/set_text/)(System::String) | Gets text which operator out on the page. |
| [SetSpacingMoveToNextLineShowText](./setspacingmovetonextlineshowtext/)(double, double, System::String) | Initializes operator. |
| [TextOperator](../textoperator/textoperator/)() | Initializes operator. |
| [TextOperator](../textoperator/textoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | [Text](../../aspose.pdf.text/) operator which accepts text properties. |
| [TextShowOperator](../textshowoperator/textshowoperator/)() | Initializes [TextShowOperator](../textshowoperator/). |
| [TextShowOperator](../textshowoperator/textshowoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | Initializes [TextShowOperator](../textshowoperator/) which allows to pass TextProperties. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [TextShowOperator](../textshowoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
