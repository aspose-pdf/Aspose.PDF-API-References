---
title: Aspose::Pdf::Operators::SetColorSpace class
linktitle: SetColorSpace
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetColorSpace class. Class representing cs operator (set colorspace for non-stroking operations) in C++.'
type: docs
weight: 5500
url: /cpp/aspose.pdf.operators/setcolorspace/
---
## SetColorSpace class


Class representing cs operator (set colorspace for non-stroking operations)

```cpp
class SetColorSpace : public Aspose::Pdf::Operator
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
| [SetColorSpace](./setcolorspace/)(System::String) | Initializes operator. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
