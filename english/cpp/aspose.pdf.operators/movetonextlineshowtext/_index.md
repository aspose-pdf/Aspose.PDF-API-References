---
title: Aspose::Pdf::Operators::MoveToNextLineShowText class
linktitle: MoveToNextLineShowText
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::MoveToNextLineShowText class. Class representing '' operator (move to next line and show text) in C++.'
type: docs
weight: 4000
url: /cpp/aspose.pdf.operators/movetonextlineshowtext/
---
## MoveToNextLineShowText class


Class representing ' operator (move to next line and show text).

```cpp
class MoveToNextLineShowText : public Aspose::Pdf::Operators::TextShowOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_Text](./get_text/)() override | Gets operator text. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [MoveToNextLineShowText](./movetonextlineshowtext/)() | Initializes operator. |
| [MoveToNextLineShowText](./movetonextlineshowtext/)(System::String) | Initializes operator. |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| virtual [set_Text](../textshowoperator/set_text/)(System::String) | Gets text which operator out on the page. |
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
