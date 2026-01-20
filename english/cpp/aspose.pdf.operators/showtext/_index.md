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
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Accepts visitor object to process operator. |
| [get_Text](./get_text/)() override | [Text](../../aspose.pdf.text/) of operator. |
| [set_Text](./set_text/)(System::String) override | [Text](../../aspose.pdf.text/) of operator. |
| [ShowText](./showtext/)(int32_t, System::String) | Initializes Tj opearor. |
| [ShowText](./showtext/)(System::String) | Initializes Tj operator. |
| [ShowText](./showtext/)(System::String, System::SharedPtr\<Text::Font\>) | Initializes Tj opearor. |
| [ShowText](./showtext/)() | Initializes Tj operator. |
| [ToString](./tostring/)() const override | Produces text code of operator. |
## See Also

* Class [TextShowOperator](../textshowoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
