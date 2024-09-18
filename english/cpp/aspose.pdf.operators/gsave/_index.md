---
title: Aspose::Pdf::Operators::GSave class
linktitle: GSave
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::GSave class. Class representing q operator (save graphics state) in C++.'
type: docs
weight: 3300
url: /cpp/aspose.pdf.operators/gsave/
---
## GSave class


Class representing q operator (save graphics state).

```cpp
class GSave : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [GSave](./gsave/)() | Initializes q operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [ToString](./tostring/)() const override | Returns text of the operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
