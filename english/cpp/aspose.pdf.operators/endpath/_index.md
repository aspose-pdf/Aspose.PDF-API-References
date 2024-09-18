---
title: Aspose::Pdf::Operators::EndPath class
linktitle: EndPath
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::EndPath class. Class representing n operator (end path without filling or stroking) in C++.'
type: docs
weight: 2200
url: /cpp/aspose.pdf.operators/endpath/
---
## EndPath class


Class representing n operator (end path without filling or stroking).

```cpp
class EndPath : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [EndPath](./endpath/)() | Initializes operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [ToString](./tostring/)() const override | [Text](../../aspose.pdf.text/) representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
