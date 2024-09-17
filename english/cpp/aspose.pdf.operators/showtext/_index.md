---
title: Aspose::Pdf::Operators::ShowText class
linktitle: ShowText
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::ShowText class. Class representing Tj operator (show text) in C++.'
type: docs
weight: 7700
url: /cpp/aspose.pdf.operators/showtext/
---
## ShowText class


Class representing Tj operator (show text).

```cpp
class ShowText : public Aspose::Pdf::Operators::TextShowOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_Text](./get_text/)() override | [Text](../../aspose.pdf.text/) of operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_Text](./set_text/)(System::String) override | [Text](../../aspose.pdf.text/) of operator. |
| [ShowText](./showtext/)(int32_t, System::String) | Initializes Tj opearor. |
| [ShowText](./showtext/)(System::String) | Initializes Tj operator. |
| [ShowText](./showtext/)(System::String, System::SharedPtr\<Text::Font\>) | Initializes Tj opearor. |
| [ShowText](./showtext/)() | Initializes Tj operator. |
| [TextOperator](../textoperator/textoperator/)() | Initializes operator. |
| [TextOperator](../textoperator/textoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | [Text](../../aspose.pdf.text/) operator which accepts text properties. |
| [TextShowOperator](../textshowoperator/textshowoperator/)() | Initializes [TextShowOperator](../textshowoperator/). |
| [TextShowOperator](../textshowoperator/textshowoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | Initializes [TextShowOperator](../textshowoperator/) which allows to pass TextProperties. |
| [ToString](./tostring/)() const override | Produces text code of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [TextShowOperator](../textshowoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
