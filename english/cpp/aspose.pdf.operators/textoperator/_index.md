---
title: Aspose::Pdf::Operators::TextOperator class
linktitle: TextOperator
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::TextOperator class. Abstract base class for text-related operators (TJ, Tj, Tm, BT, ET, etc) in C++.'
type: docs
weight: 7900
url: /cpp/aspose.pdf.operators/textoperator/
---
## TextOperator class


Abstract base class for text-related operators (TJ, Tj, Tm, [BT](../bt/), [ET](../et/), etc).

```cpp
class TextOperator : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [TextOperator](./textoperator/)() | Initializes operator. |
| [TextOperator](./textoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | [Text](../../aspose.pdf.text/) operator which accepts text properties. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
