---
title: Aspose::Pdf::Operators::ShFill class
linktitle: ShFill
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::ShFill class. Class representing sh operator (paint area with shading pattern) in C++.'
type: docs
weight: 7600
url: /cpp/aspose.pdf.operators/shfill/
---
## ShFill class


Class representing sh operator (paint area with shading pattern).

```cpp
class ShFill : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_Name](./get_name/)() const | Gets the shading name. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_Name](./set_name/)(System::String) | Sets the shading name. |
| [ShFill](./shfill/)(System::String) | Initializes operator. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
