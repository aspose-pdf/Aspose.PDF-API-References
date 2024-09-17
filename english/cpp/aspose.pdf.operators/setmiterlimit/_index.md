---
title: Aspose::Pdf::Operators::SetMiterLimit class
linktitle: SetMiterLimit
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetMiterLimit class. Class representing M operator (set miter limit) in C++.'
type: docs
weight: 6700
url: /cpp/aspose.pdf.operators/setmiterlimit/
---
## SetMiterLimit class


Class representing M operator (set miter limit).

```cpp
class SetMiterLimit : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_MiterLimit](./get_miterlimit/)() const | Gets the miter limit. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_MiterLimit](./set_miterlimit/)(double) | Sets the miter limit. |
| [SetMiterLimit](./setmiterlimit/)(double) | Initializes operator. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
