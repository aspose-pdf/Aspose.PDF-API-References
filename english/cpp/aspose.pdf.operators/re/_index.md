---
title: Aspose::Pdf::Operators::Re class
linktitle: Re
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::Re class. Class representing re operator (add rectangle to the path) in C++.'
type: docs
weight: 4300
url: /cpp/aspose.pdf.operators/re/
---
## Re class


Class representing re operator (add rectangle to the path).

```cpp
class Re : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Height](./get_height/)() const | Height of the rectangle. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_Width](./get_width/)() const | Width of the rectangle. |
| [get_X](./get_x/)() const | X coordinate of most left side of rectangle. |
| [get_Y](./get_y/)() const | Y corrdinate of bottom side of rectangle. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [Re](./re/)() | Initializes operator. |
| [Re](./re/)(double, double, double, double) | Initializes operator. |
| [set_Height](./set_height/)(double) | Height of the rectangle. |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_Width](./set_width/)(double) | Width of the rectangle. |
| [set_X](./set_x/)(double) | X coordinate of most left side of rectangle. |
| [set_Y](./set_y/)(double) | Y corrdinate of bottom side of rectangle. |
| [ToString](./tostring/)() const override | Returns text representation of the operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
