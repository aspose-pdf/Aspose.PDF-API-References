---
title: Aspose::Pdf::Operators::GS class
linktitle: GS
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::GS class. Class representing gs operator (set parameters from graphic state parameter dictionary) in C++.'
type: docs
weight: 3200
url: /cpp/aspose.pdf.operators/gs/
---
## GS class


Class representing gs operator (set parameters from graphic state parameter dictionary).

```cpp
class GS : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_Name](./get_name/)() const | Gets name of graphic state resource. |
| [GS](./gs/)(System::String) | Initializes gs operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_Name](./set_name/)(System::String) | Sets name of graphic state resource. |
| [ToString](./tostring/)() const override | Returns string representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
