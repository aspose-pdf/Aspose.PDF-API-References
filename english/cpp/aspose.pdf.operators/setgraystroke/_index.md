---
title: Aspose::Pdf::Operators::SetGrayStroke class
linktitle: SetGrayStroke
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetGrayStroke class. Class representing gray level for stroking operations in C++.'
type: docs
weight: 6200
url: /cpp/aspose.pdf.operators/setgraystroke/
---
## SetGrayStroke class


Class representing gray level for stroking operations.

```cpp
class SetGrayStroke : public Aspose::Pdf::Operators::SetColorOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Gray](./get_gray/)() const | Gets the level of gray value. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [getColor](./getcolor/)() override | Returns color specified by operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Gray](./set_gray/)(double) | Sets the level of gray value. |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [SetGrayStroke](./setgraystroke/)(double) | Initializes operator with the specified color. |
| [ToString](./tostring/)() const override | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [SetColorOperator](../setcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
