---
title: "System::Collections::Generic::SortedSet класс"
linktitle: "SortedSet"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::SortedSet класс. Объявление класса SortedSet вперёд в C++."
type: docs
weight: 4400
url: /ru/cpp/system.collections.generic/sortedset/
---
## SortedSet class


Объявление класса [SortedSet](./) вперёд.

```cpp
template<typename T>class SortedSet : public System::Collections::Generic::BaseSet<T, std::set<T, ComparerAdapter<T>, System::Details::CollectionHelpers::ContainerPointerMode<T>::allocator_type>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Max](./get_max/)() const | Получает максимальное значение в [SortedSet](./). |
| [SortedSet](./sortedset/)() | Информация RTTI. |
| [SortedSet](./sortedset/)(int) | Создаёт пустое множество с указанной ёмкостью. |
| [SortedSet](./sortedset/)(const SharedPtr\<IComparer\<T\>\>\&) | Создаёт пустое множество, использующее указанный компаратор равенства. |
| [SortedSet](./sortedset/)(const SharedPtr\<IEnumerable\<T\>\>\&) | Создаёт [SortedSet](./) на основе enumerable значений. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [BaseType](./basetype/) | Тип Vase. |
| [ThisPtr](./thisptr/) | Тип указателя. |
| [ThisType](./thistype/) | Тип самого себя. |
## Примечания


Реализация набора упорядоченных объектов. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [BaseSet](../baseset/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
