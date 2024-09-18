---
title: Aspose::Pdf::Operators::ClosePathStroke class
linktitle: ClosePathStroke
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::ClosePathStroke class. Class representing s operator (Close and stroke path) in C++.'
type: docs
weight: 1300
url: /cpp/aspose.pdf.operators/closepathstroke/
---
## ClosePathStroke class


Class representing s operator (Close and stroke path).

```cpp
class ClosePathStroke : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [ClosePathStroke](./closepathstroke/)() | Initializes operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [ToString](./tostring/)() const override | Returns text representation of the operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
