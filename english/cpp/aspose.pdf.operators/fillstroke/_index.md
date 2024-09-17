---
title: Aspose::Pdf::Operators::FillStroke class
linktitle: FillStroke
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::FillStroke class. Class representing B operator (fill and stroke path using nonzero winding rule) in C++.'
type: docs
weight: 2900
url: /cpp/aspose.pdf.operators/fillstroke/
---
## FillStroke class


Class representing B operator (fill and stroke path using nonzero winding rule)

```cpp
class FillStroke : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [FillStroke](./fillstroke/)() | Initializes operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [ToString](./tostring/)() const override | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
