---
title: Aspose::Pdf::Operators::SetLineJoin class
linktitle: SetLineJoin
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetLineJoin class. Class representing j operator (set line join style) in C++.'
type: docs
weight: 6500
url: /cpp/aspose.pdf.operators/setlinejoin/
---
## SetLineJoin class


Class representing j operator (set line join style).

```cpp
class SetLineJoin : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_Join](./get_join/)() |  |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_Join](./set_join/)(LineJoin) |  |
| [SetLineJoin](./setlinejoin/)() | Initializes operator. |
| [SetLineJoin](./setlinejoin/)(LineJoin) |  |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
