---
title: "System::Collections::Generic::IList класс"
linktitle: "IList"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::IList класс. Интерфейс индексированного контейнера элементов. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2600
url: /ru/cpp/system.collections.generic/ilist/
---
## IList class


Интерфейс индексированного контейнера элементов. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename T>class IList : public System::Collections::Generic::ICollection<T>
```


| Параметр | Описание |
| --- | --- |
| T | Тип элемента. |
## Методы

| Метод | Описание |
| --- | --- |
| [get_IsFixedSize](./get_isfixedsize/)() | Проверяет, имеет ли коллекция фиксированный размер. |
| virtual [idx_get](./idx_get/)(int) const | Получает элемент по указанному индексу. |
| virtual [idx_set](./idx_set/)(int, T) | Устанавливает элемент по указанному индексу. |
| virtual [IndexOf](./indexof/)(const T\&) const | Получает индекс первого появления элемента в контейнере. |
| virtual [Insert](./insert/)(int, const T\&) | Вставляет элемент в указанную позицию, сдвигая остальные элементы. |
| virtual [RemoveAt](./removeat/)(int) | Удаляет элемент по указанному индексу. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [BaseType](./basetype/) | Информация RTTI. |
| [ThisType](./thistype/) | Этот тип. |
| [ValueType](./valuetype/) | Тип значения. |

## См. также

* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
