---
title: "System::Collections::IListImplValueType класс"
linktitle: "IListImplValueType"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::IListImplValueType класс. Заглушка, которая реализует интерфейс System::Collections::IList на объекте System::Collections::Generic::List. Реализация для value типов в C++."
type: docs
weight: 1200
url: /ru/cpp/system.collections/ilistimplvaluetype/
---
## IListImplValueType class


Заглушка, которая реализует интерфейс [System::Collections::IList](../ilist/) на объекте [System::Collections::Generic::List](../../system.collections.generic/list/). Реализация для value типов.

```cpp
template<typename T>class IListImplValueType : public virtual System::Collections::IList
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(SharedPtr\<System::Object\>) override | Добавляет элемент в конец списка. |
| [Clear](./clear/)() override | Удаляет все элементы. |
| [Contains](./contains/)(SharedPtr\<System::Object\>) const override | Проверяет, присутствует ли элемент в списке. |
| [get_Count](./get_count/)() const override | Реализация метода [ICollection.get_Count()](../icollection/get_count/) Получает количество элементов в коллекции. |
| [GetEnumerator](./getenumerator/)() override | Реализация [IEnumerable.GetEnumerator()](../ienumerable/getenumerator/) Возвращает перечислитель, который перебирает элементы коллекции. |
| [idx_get](./idx_get/)(int, int) const override | Получает элемент по указанному индексу. |
| [IListImplValueType](./ilistimplvaluetype/)(System::SharedPtr\<System::Collections::Generic::IList\<T\>\>) | Создает новый экземпляр объекта. |
| [IndexOf](./indexof/)(System::SharedPtr\<System::Object\>) const override | Получает индекс первого появления элемента в контейнере. |
| [Insert](./insert/)(int, System::SharedPtr\<System::Object\>) override | Вставляет элемент в указанную позицию, сдвигая остальные элементы. |
| [Remove](./remove/)(SharedPtr\<System::Object\>) override | Удаляет первое вхождение конкретного элемента из списка. |
| [RemoveAt](./removeat/)(int) override | Удаляет элемент в указанной позиции. |
## См. также

* Class [IList](../ilist/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
