---
title: Aspose::Pdf::Operators::SetFlat class
linktitle: SetFlat
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetFlat class. Class representing i operator (set flatness tolerance) in C++.'
type: docs
weight: 5900
url: /cpp/aspose.pdf.operators/setflat/
---
## SetFlat class


Class representing i operator (set flatness tolerance).

```cpp
class SetFlat : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Flatness](./get_flatness/)() const | Gets the flatness. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Flatness](./set_flatness/)(double) | Sets the flatness. |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [SetFlat](./setflat/)(double) | Initializes operator. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
