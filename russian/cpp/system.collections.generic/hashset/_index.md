---
title: "System::Collections::Generic::HashSet класс"
linktitle: "HashSet"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::HashSet класс. Предварительное объявление класса HashSet в C++."
type: docs
weight: 1700
url: /ru/cpp/system.collections.generic/hashset/
---
## HashSet class


Предварительное объявление класса [HashSet](./).

```cpp
template<typename T>class HashSet : public System::Collections::Generic::BaseSet<T, std::unordered_set<T, EqualityComparerHashAdapter<T>, EqualityComparerAdapter<T>, System::Details::CollectionHelpers::ContainerPointerMode<T>::allocator_type>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [HashSet](./hashset/)() | Информация RTTI. |
| [HashSet](./hashset/)(int) | Создаёт пустое множество с указанной ёмкостью. |
| [HashSet](./hashset/)(const SharedPtr\<IEqualityComparer\<T\>\>\&) | Создаёт пустое множество, использующее указанный компаратор равенства. |
| [HashSet](./hashset/)(const SharedPtr\<IEnumerable\<T\>\>\&) | Создаёт HashSet на основе перечислимых значений. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [BaseType](./basetype/) | Базовый тип. |
| [ThisPtr](./thisptr/) | Тип указателя. |
| [ThisType](./thistype/) | Тип самого себя. |
## Примечания


Реализация множества на основе хеширования. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [BaseSet](../baseset/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
