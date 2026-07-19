---
title: "Aspose::Pdf::Operator class"
linktitle: "Operator"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Operator class. Абстрактный класс, представляющий оператор в C++."
type: docs
weight: 12000
url: /ru/cpp/aspose.pdf/operator/
---
## Operator class


Абстрактный класс, представляющий оператор.

```cpp
class Operator : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) | Принимает посетителя [IOperatorSelector](../ioperatorselector/), который обеспечивает обработку операторов. |
| [get_Index](./get_index/)() | Индекс [Operator](./) в списке операторов страницы. |
| static [IsTextShowOperator](./istextshowoperator/)(const System::SharedPtr\<Operator\>\&) | Определяет, является ли оператор оператором, отвечающим за вывод текста (Tj, TJ и др.) |
| [set_Index](./set_index/)(int32_t) | Индекс [Operator](./) в списке операторов страницы. |
| [ToString](./tostring/)() const override | Возвращает текст оператора и его параметры. |
| [ValueEquals](./valueequals/)(const System::SharedPtr\<Operator\>\&) | Сравнивает этот экземпляр с заданным объектом. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
