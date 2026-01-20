---
title: Aspose::Pdf::Operator class
linktitle: Operator
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operator class. Abstract class representing operator in C++.'
type: docs
weight: 12000
url: /cpp/aspose.pdf/operator/
---
## Operator class


Abstract class representing operator.

```cpp
class Operator : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) | Accepts visitor [IOperatorSelector](../ioperatorselector/) which provides operators processing. |
| [get_Index](./get_index/)() | [Operator](./) index in page operators list. |
| static [IsTextShowOperator](./istextshowoperator/)(const System::SharedPtr\<Operator\>\&) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](./set_index/)(int32_t) | [Operator](./) index in page operators list. |
| [ToString](./tostring/)() const override | Returns text of operator and its parameters. |
| [ValueEquals](./valueequals/)(const System::SharedPtr\<Operator\>\&) | Compares this instance with the given object. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
