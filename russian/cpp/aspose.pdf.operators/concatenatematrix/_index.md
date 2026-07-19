---
title: "Aspose::Pdf::Operators::ConcatenateMatrix класс"
linktitle: "ConcatenateMatrix"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Operators::ConcatenateMatrix класс. Класс, представляющий оператор cm (объединяет матрицу с текущей матрицей преобразования) в C++."
type: docs
weight: 1400
url: /ru/cpp/aspose.pdf.operators/concatenatematrix/
---
## ConcatenateMatrix class


Класс, представляющий оператор cm (объединяет матрицу с текущей матрицей преобразования).

```cpp
class ConcatenateMatrix : public Aspose::Pdf::Operator
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Принимает объект посетителя для обработки оператора. |
| [ConcatenateMatrix](./concatenatematrix/)(double, double, double, double, double, double) | Инициализирует оператор. |
| [ConcatenateMatrix](./concatenatematrix/)(const System::SharedPtr\<Aspose::Pdf::Matrix\>\&) | Инициализирует оператор с помощью матрицы. |
| [get_Matrix](./get_matrix/)() const | [Matrix](../../aspose.pdf/matrix/) аргумент оператора. |
| [set_Matrix](./set_matrix/)(const System::SharedPtr\<Aspose::Pdf::Matrix\>\&) | [Matrix](../../aspose.pdf/matrix/) аргумент оператора. |
| [ToString](./tostring/)() const override | Возвращает текстовое представление оператора. |
## См. также

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
