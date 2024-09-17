---
title: Aspose::Pdf::Operators::SelectFont class
linktitle: SelectFont
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SelectFont class. Class representing Tf operator (set text font and size) in C++.'
type: docs
weight: 4400
url: /cpp/aspose.pdf.operators/selectfont/
---
## SelectFont class


Class representing Tf operator (set text font and size).

```cpp
class SelectFont : public Aspose::Pdf::Operators::TextStateOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_Name](./get_name/)() const | Name of font. |
| [get_Size](./get_size/)() const | Size of text. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [SelectFont](./selectfont/)(System::String, double) | Initializes operator. |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [TextOperator](../textoperator/textoperator/)() | Initializes operator. |
| [TextOperator](../textoperator/textoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | [Text](../../aspose.pdf.text/) operator which accepts text properties. |
| [TextStateOperator](../textstateoperator/textstateoperator/)() | Initializes [TextStateOperator](../textstateoperator/). |
| [TextStateOperator](../textstateoperator/textstateoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | Initializes TextStateoperator which allows to pass TextProperties. |
| [ToString](./tostring/)() const override | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [TextStateOperator](../textstateoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
