---
title: Aspose::Pdf::Operators::MoveTo class
linktitle: MoveTo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::MoveTo class. Class representing m operator (move to and begin new subpath) in C++.'
type: docs
weight: 3800
url: /cpp/aspose.pdf.operators/moveto/
---
## MoveTo class


Class representing m operator (move to and begin new subpath).

```cpp
class MoveTo : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_X](./get_x/)() const | X coordinate. |
| [get_Y](./get_y/)() const | Y coordinate. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [MoveTo](./moveto/)(double, double) | Inintalizes new [Operators::m](../) (move to) operator. |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_X](./set_x/)(double) | X coordinate. |
| [set_Y](./set_y/)(double) | Y coordinate. |
| [ToString](./tostring/)() const override | Returns text representation of the operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
