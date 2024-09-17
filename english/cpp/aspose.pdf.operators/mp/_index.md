---
title: Aspose::Pdf::Operators::MP class
linktitle: MP
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::MP class. Class representing MP operator (define marked-content point) in C++.'
type: docs
weight: 4100
url: /cpp/aspose.pdf.operators/mp/
---
## MP class


Class representing [MP](./) operator (define marked-content point).

```cpp
class MP : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_Tag](./get_tag/)() const | Gets marked content tag. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [MP](./mp/)(System::String) | Initializes operator. |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_Tag](./set_tag/)(System::String) | Sets marked content tag. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
