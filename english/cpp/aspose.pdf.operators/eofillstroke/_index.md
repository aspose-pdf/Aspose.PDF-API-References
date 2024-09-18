---
title: Aspose::Pdf::Operators::EOFillStroke class
linktitle: EOFillStroke
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::EOFillStroke class. Class representing B* operator (fill and stroke path usign even-odd rule) in C++.'
type: docs
weight: 2500
url: /cpp/aspose.pdf.operators/eofillstroke/
---
## EOFillStroke class


Class representing B* operator (fill and stroke path usign even-odd rule).

```cpp
class EOFillStroke : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [EOFillStroke](./eofillstroke/)() | Initializes operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
