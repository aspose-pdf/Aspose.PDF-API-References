---
title: Aspose::Pdf::Operators::LineTo class
linktitle: LineTo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::LineTo class. Class representing l operator (add line to the path) in C++.'
type: docs
weight: 3500
url: /cpp/aspose.pdf.operators/lineto/
---
## LineTo class


Class representing l operator (add line to the path).

```cpp
class LineTo : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_X](./get_x/)() const | X coordinate of line point. |
| [get_Y](./get_y/)() const | Y coordinate of line point. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [LineTo](./lineto/)(double, double) | Initializes line operator. |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_X](./set_x/)(double) | X coordinate of line point. |
| [set_Y](./set_y/)(double) | Y coordinate of line point. |
| [ToString](./tostring/)() const override | Returns text representation of the operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
