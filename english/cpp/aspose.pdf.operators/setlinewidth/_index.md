---
title: Aspose::Pdf::Operators::SetLineWidth class
linktitle: SetLineWidth
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetLineWidth class. Class representing w operator (set line width) in C++.'
type: docs
weight: 6600
url: /cpp/aspose.pdf.operators/setlinewidth/
---
## SetLineWidth class


Class representing w operator (set line width).

```cpp
class SetLineWidth : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_Width](./get_width/)() const | Gets width of the line. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_Width](./set_width/)(double) | Sets width of the line. |
| [SetLineWidth](./setlinewidth/)(double) | Initializes operator with width value. |
| [ToString](./tostring/)() const override | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
