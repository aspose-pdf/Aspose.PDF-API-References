---
title: Aspose::Pdf::Operators::SetTextMatrix class
linktitle: SetTextMatrix
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetTextMatrix class. Class representing Tm operator (set text matrix) in C++.'
type: docs
weight: 7200
url: /cpp/aspose.pdf.operators/settextmatrix/
---
## SetTextMatrix class


Class representing Tm operator (set text matrix).

```cpp
class SetTextMatrix : public Aspose::Pdf::Operators::TextPlaceOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Accepts visitor object to process operator. |
| [get_Matrix](./get_matrix/)() const | [Matrix](../../aspose.pdf/matrix/) argument of the operator. |
| [set_Matrix](./set_matrix/)(System::SharedPtr\<Aspose::Pdf::Matrix\>) | [Matrix](../../aspose.pdf/matrix/) argument of the operator. |
| [SetTextMatrix](./settextmatrix/)(double, double, double, double, double, double) | Initializes operator. |
| [SetTextMatrix](./settextmatrix/)(System::SharedPtr\<Aspose::Pdf::Matrix\>) | Initializes operator by matrix. |
| [ToString](./tostring/)() const override | Returns text representation of operator. |
## See Also

* Class [TextPlaceOperator](../textplaceoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
