---
title: "System::Globalization::SortKey класс"
linktitle: "SortKey"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Globalization::SortKey класс. Преобразование строки в её сортировочный ключ. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2200
url: /ru/cpp/system.globalization/sortkey/
---
## SortKey class


Преобразование строки в её сортировочный ключ. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class SortKey : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [Compare](./compare/)(const SortKeyPtr\&, const SortKeyPtr\&) | Сравнивает два сортировочных ключа. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Проверяет, равен ли указанный объект текущему объекту [SortKey](./). |
| virtual [get_KeyData](./get_keydata/)() | Получает массив байтов, представляющий текущий объект. |
| virtual [get_OriginalString](./get_originalstring/)() | Получает исходную строку, использованную для создания этого объекта. |
| [GetHashCode](./gethashcode/)() const override | Получает хеш‑код для текущего объекта [SortKey](./). |
| [operator=](./operator=/)(const SortKey\&) |  |
| [SortKey](./sortkey/)(const SortKey\&) |  |
| [ToString](./tostring/)() const override | Преобразует текущий объект в его строковое представление. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
