---
title: "System::Collections::Generic::_KeyList класс"
linktitle: "_KeyList"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::_KeyList класс. Реализует список ключей словаря. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 200
url: /ru/cpp/system.collections.generic/_keylist/
---
## _KeyList class


Реализует список ключей словаря. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename Dict>class _KeyList : public System::Collections::Generic::_KeyCollection<Dict>
```


| Параметр | Описание |
| --- | --- |
| Dict | [Dictionary](../dictionary/) тип. |
## Методы

| Метод | Описание |
| --- | --- |
| [_KeyList](./_keylist/)(const typename Dict::Ptr\&) | Инициализирует коллекцию, ссылающуюся на указанный словарь. |
| [Contains](./contains/)(const TKey\&) const override | Проверяет, присутствует ли указанный ключ в коллекции. |
| [idx_get](./idx_get/)(int) const override | Получает ключ в указанной позиции. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [TKey](./tkey/) | Тип ключа. |

## См. также

* Class [_KeyCollection](../_keycollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
