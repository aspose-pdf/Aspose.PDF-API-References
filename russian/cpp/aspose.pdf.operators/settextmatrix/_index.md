---
title: "Aspose::Pdf::Operators::SetTextMatrix класс"
linktitle: "SetTextMatrix"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Operators::SetTextMatrix класс. Класс, представляющий оператор Tm (установка матрицы текста) в C++."
type: docs
weight: 7200
url: /ru/cpp/aspose.pdf.operators/settextmatrix/
---
## SetTextMatrix class


Класс, представляющий оператор Tm (устанавливает матрицу текста).

```cpp
class SetTextMatrix : public Aspose::Pdf::Operators::TextPlaceOperator
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Принимает объект посетителя для обработки оператора. |
| [get_Matrix](./get_matrix/)() const | [Matrix](../../aspose.pdf/matrix/) аргумент оператора. |
| [set_Matrix](./set_matrix/)(const System::SharedPtr\<Aspose::Pdf::Matrix\>\&) | [Matrix](../../aspose.pdf/matrix/) аргумент оператора. |
| [SetTextMatrix](./settextmatrix/)(double, double, double, double, double, double) | Инициализирует оператор. |
| [SetTextMatrix](./settextmatrix/)(const System::SharedPtr\<Aspose::Pdf::Matrix\>\&) | Инициализирует оператор с помощью матрицы. |
| [ToString](./tostring/)() const override | Возвращает текстовое представление оператора. |
## См. также

* Class [TextPlaceOperator](../textplaceoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
