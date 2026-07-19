---
title: "System::Collections::Generic::_ValueList класс"
linktitle: "_ValueList"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::_ValueList класс. Реализует список значений словаря. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 400
url: /ru/cpp/system.collections.generic/_valuelist/
---
## _ValueList class


Реализует список значений словаря. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename Dict>class _ValueList : public System::Collections::Generic::_ValueCollection<Dict>
```


| Параметр | Описание |
| --- | --- |
| Dict | [Dictionary](../dictionary/) тип. |
## Методы

| Метод | Описание |
| --- | --- |
| [_ValueList](./_valuelist/)(const typename Dict::Ptr\&) | Инициализирует коллекцию, ссылающуюся на указанный словарь. |
| virtual [idx_get](./idx_get/)(int) const | Возвращает значение в указанной позиции. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [TValue](./tvalue/) | Тип значения. |

## См. также

* Class [_ValueCollection](../_valuecollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
