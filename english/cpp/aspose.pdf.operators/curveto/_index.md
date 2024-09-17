---
title: Aspose::Pdf::Operators::CurveTo class
linktitle: CurveTo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::CurveTo class. Class representing c operator (append curve to path) in C++.'
type: docs
weight: 1500
url: /cpp/aspose.pdf.operators/curveto/
---
## CurveTo class


Class representing c operator (append curve to path).

```cpp
class CurveTo : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [CurveTo](./curveto/)(double, double, double, double, double, double) | Initializes curve operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_Points](./get_points/)() const | Points of the curve. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [ToString](./tostring/)() const override | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
