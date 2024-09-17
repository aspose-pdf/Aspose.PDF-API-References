---
title: Aspose::Pdf::Operators::SetColorRenderingIntent class
linktitle: SetColorRenderingIntent
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetColorRenderingIntent class. Class representing ri operator (set color rendering intent) in C++.'
type: docs
weight: 5400
url: /cpp/aspose.pdf.operators/setcolorrenderingintent/
---
## SetColorRenderingIntent class


Class representing ri operator (set color rendering intent).

```cpp
class SetColorRenderingIntent : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_IntentName](./get_intentname/)() const | Gets color rendering intent name. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_IntentName](./set_intentname/)(System::String) | Sets color rendering intent name. |
| [SetColorRenderingIntent](./setcolorrenderingintent/)(System::String) | Set [Color](../../aspose.pdf/color/) Rendering Intent operator constructor. |
| [ToString](../../aspose.pdf/operator/tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
