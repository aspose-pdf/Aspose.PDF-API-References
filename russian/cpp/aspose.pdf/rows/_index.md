---
title: "Класс Aspose::Pdf::Rows"
linktitle: "Rows"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Rows. Представляет коллекцию строк таблицы в C++."
type: docs
weight: 16900
url: /ru/cpp/aspose.pdf/rows/
---
## Rows class


Представляет коллекцию строк таблицы.

```cpp
class Rows : public System::Collections::Generic::IEnumerable<System::SharedPtr<Row>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)() | Добавить строку в коллекцию. |
| [Add](./add/)(const System::SharedPtr\<Row\>\&) | Добавить строку в коллекцию. |
| [begin](./begin/)() | Получает итератор, указывающий на первый элемент (если он существует) коллекции. |
| [begin](./begin/)() const | Получает итератор, указывающий на первый элемент (если он существует) константно-квалифицированного экземпляра коллекции. |
| [cbegin](./cbegin/)() const | Получает итератор, указывающий на первый константно-квалифицированный элемент (если он существует) коллекции. |
| [cend](./cend/)() const | Получает итератор, указывающий сразу после последнего константно-квалифицированного элемента (если он существует) коллекции. |
| [Dispose](./dispose/)() | Освободить. |
| [end](./end/)() | Получает итератор, указывающий сразу после последнего элемента (если он существует) коллекции. |
| [end](./end/)() const | Получает итератор, указывающий сразу после последнего элемента (если он существует) константно-квалифицированного экземпляра коллекции. |
| [get_Count](./get_count/)() | Количество элементов. |
| [GetEnumerator](./getenumerator/)() override | Получает перечислитель коллекции. |
| [idx_get](./idx_get/)(int32_t) | Получает строку. |
| [idx_set](./idx_set/)(int32_t, const System::SharedPtr\<Row\>\&) | Устанавливает строку. |
| [IndexOf](./indexof/)(const System::SharedPtr\<Row\>\&) | Возвращает индекс строки в коллекции. |
| [Remove](./remove/)(const System::SharedPtr\<Row\>\&) | Удалить строку из коллекции. |
| [RemoveAt](./removeat/)(int32_t) | Удалить строку в позиции из коллекции. |
| [RemoveRange](./removerange/)(int32_t, int32_t) | Удалить набор строк из коллекции. |
| [Rows](./rows/)() |  |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Получает итератор, указывающий на первый элемент (если он существует) константно-квалифицированного экземпляра коллекции. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Получает итератор, указывающий на первый элемент (если он существует) коллекции. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Получает итератор, указывающий сразу после последнего элемента (если он существует) константно-квалифицированного экземпляра коллекции. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Получает итератор, указывающий сразу после последнего элемента (если он существует) коллекции. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [const_iterator](./const_iterator/) | Тип константного итератора. |
| [iterator](./iterator/) | Тип итератора. |
| [iterator_holder_type](./iterator_holder_type/) | Тип коллекции, чьи типы итераторов используются в качестве типов итераторов текущей коллекции. |
| [virtualized_iterator](./virtualized_iterator/) | Виртуализированный тип. |
| [virtualized_iterator_element](./virtualized_iterator_element/) | Виртуализированный тип элемента. |
## См. также

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
