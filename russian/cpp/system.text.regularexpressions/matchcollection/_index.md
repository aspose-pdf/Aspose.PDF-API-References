---
title: "System::Text::RegularExpressions::MatchCollection класс"
linktitle: "MatchCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::RegularExpressions::MatchCollection класс. Коллекция совпадений, получаемая путем многократного применения регулярного выражения к строке. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 700
url: /ru/cpp/system.text.regularexpressions/matchcollection/
---
## MatchCollection class


Коллекция совпадений, получаемая путем многократного применения регулярного выражения к строке. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class MatchCollection : public System::Collections::Generic::List<MatchPtr>
```

## Методы

| Метод | Описание |
| --- | --- |
| [IsReadOnly](./isreadonly/)() const | Помечает коллекцию как только для чтения. |
## См. также

* Class [List](../../system.collections.generic/list/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
