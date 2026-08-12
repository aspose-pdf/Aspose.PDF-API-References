---
title: "System::Collections::IListImplRefType класс"
linktitle: "IListImplRefType"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::IListImplRefType класс. Заглушка, реализующая интерфейс System::Collections::IList на объекте System::Collections::Generic::List. Реализация для ссылочных типов в C++."
type: docs
weight: 1100
url: /ru/cpp/system.collections/ilistimplreftype/
---
## IListImplRefType class


Заглушка, реализующая интерфейс [System::Collections::IList](../ilist/) на объекте [System::Collections::Generic::List](../../system.collections.generic/list/). Реализация для ссылочных типов.

```cpp
template<typename T>class IListImplRefType : public virtual System::Collections::IList
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(SharedPtr\<System::Object\>) override | Добавляет элемент в конец списка. |
| static [BoxValue](./boxvalue/)(System::SharedPtr\<T\>) | Преобразование ссылки типа в значение объекта. |
| [Clear](./clear/)() override | Удаляет все элементы. |
| [Contains](./contains/)(SharedPtr\<System::Object\>) const override | Проверяет, присутствует ли элемент в списке. |
| [get_Count](./get_count/)() const override | Реализация метода [ICollection.get_Count()](../icollection/get_count/) Получает количество элементов в коллекции. |
| [GetEnumerator](./getenumerator/)() override | Реализация [IEnumerable.GetEnumerator()](../ienumerable/getenumerator/) Возвращает перечислитель, который перебирает элементы коллекции. |
| [idx_get](./idx_get/)(int, int) const override | Получает элемент по указанному индексу. |
| [IListImplRefType](./ilistimplreftype/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<T\>\>\>) | Создает новый экземпляр объекта. |
| [IndexOf](./indexof/)(System::SharedPtr\<System::Object\>) const override | Получает индекс первого появления элемента в контейнере. |
| [Insert](./insert/)(int, System::SharedPtr\<System::Object\>) override | Вставляет элемент в указанную позицию, сдвигая остальные элементы. |
| [Remove](./remove/)(SharedPtr\<System::Object\>) override | Удаляет первое вхождение конкретного элемента из списка. |
| [RemoveAt](./removeat/)(int) override | Удаляет элемент в указанной позиции. |
| static [UnboxValue](./unboxvalue/)(System::SharedPtr\<System::Object\>) | Преобразование значения объекта в конкретную ссылку типа. |
## См. также

* Class [IList](../ilist/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
