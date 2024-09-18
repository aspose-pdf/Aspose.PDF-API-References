---
title: Aspose::Pdf::Operators::SetGray class
linktitle: SetGray
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetGray class. Set gray level for non-stroking operations in C++.'
type: docs
weight: 6100
url: /cpp/aspose.pdf.operators/setgray/
---
## SetGray class


Set gray level for non-stroking operations.

```cpp
class SetGray : public Aspose::Pdf::Operators::SetColorOperator
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
| [SetGray](./setgray/)(double) | Initializes operator. |
| [ToString](./tostring/)() const override | Returns string representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [SetColorOperator](../setcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
