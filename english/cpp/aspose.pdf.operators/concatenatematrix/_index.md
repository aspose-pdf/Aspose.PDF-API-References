---
title: Aspose::Pdf::Operators::ConcatenateMatrix class
linktitle: ConcatenateMatrix
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::ConcatenateMatrix class. Class representing cm operator (concatenate matrix to current transformation matrix) in C++.'
type: docs
weight: 1400
url: /cpp/aspose.pdf.operators/concatenatematrix/
---
## ConcatenateMatrix class


Class representing cm operator (concatenate matrix to current transformation matrix).

```cpp
class ConcatenateMatrix : public Aspose::Pdf::Operator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Accepts visitor object to process operator. |
| [ConcatenateMatrix](./concatenatematrix/)(double, double, double, double, double, double) | Initializes operator. |
| [ConcatenateMatrix](./concatenatematrix/)(System::SharedPtr\<Aspose::Pdf::Matrix\>) | Initializes operator by matrix. |
| [get_Matrix](./get_matrix/)() const | [Matrix](../../aspose.pdf/matrix/) argument of the operator. |
| [set_Matrix](./set_matrix/)(System::SharedPtr\<Aspose::Pdf::Matrix\>) | [Matrix](../../aspose.pdf/matrix/) argument of the operator. |
| [ToString](./tostring/)() const override | Returns text representation of operator. |
## See Also

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
