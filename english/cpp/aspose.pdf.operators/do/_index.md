---
title: Aspose::Pdf::Operators::Do class
linktitle: Do
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::Do class. Class representing Do operator (Invoke XObject) in C++.'
type: docs
weight: 1800
url: /cpp/aspose.pdf.operators/do/
---
## Do class


Class representing [Do](./) operator (Invoke XObject).

```cpp
class Do : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [Do](./do/)(System::String) | Constructs new [Do](./) operator. |
| [Do](./do/)() | Constructs new [Do](./) operator. Used for retrieving all [Do](./) operators, i.e. without checking their argument names. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_Name](./get_name/)() const | Name of XObject argument of the operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [set_Name](./set_name/)(System::String) | Name of XObject argument of the operator. |
| [ToString](./tostring/)() const override | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
