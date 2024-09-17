---
title: Aspose::Pdf::Operators::SetColorSpaceStroke class
linktitle: SetColorSpaceStroke
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetColorSpaceStroke class. Class representing CS operator (set color for stroking operations) in C++.'
type: docs
weight: 5600
url: /cpp/aspose.pdf.operators/setcolorspacestroke/
---
## SetColorSpaceStroke class


Class representing CS operator (set color for stroking operations).

```cpp
class SetColorSpaceStroke : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_Name](./get_name/)() const | Gets color space name. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_Name](./set_name/)(System::String) | Sets color space name. |
| [SetColorSpaceStroke](./setcolorspacestroke/)(System::String) | Initializes operator. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
