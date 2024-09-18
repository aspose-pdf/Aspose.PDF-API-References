---
title: Aspose::Pdf::Operators::BMC class
linktitle: BMC
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::BMC class. Class representing BMC operator (Begin marked-content sequence) in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.operators/bmc/
---
## BMC class


Class representing [BMC](./) operator (Begin marked-content sequence).

```cpp
class BMC : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [BMC](./bmc/)(System::String) | Initializes operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_Tag](./get_tag/)() const | Gets marked content tag. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_Tag](./set_tag/)(System::String) | Sets marked content tag. |
| [ToString](./tostring/)() const override | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
