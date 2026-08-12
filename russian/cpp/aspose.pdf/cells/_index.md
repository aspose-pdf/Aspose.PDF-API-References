---
title: "Класс Aspose::Pdf::Cells"
linktitle: "Cells"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Cells. Представляет коллекцию ячеек строки в C++."
type: docs
weight: 1800
url: /ru/cpp/aspose.pdf/cells/
---
## Cells class


Представляет коллекцию ячеек строки.

```cpp
class Cells : public System::Collections::Generic::IEnumerable<System::SharedPtr<Cell>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)() | Добавить ячейку в коллекцию. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<Text::TextState\>\&) | Добавить ячейку в коллекцию. |
| [Add](./add/)(const System::String\&) | Добавить ячейку в коллекцию. |
| [Add](./add/)(const System::SharedPtr\<Text::TextFragment\>\&) | Добавить ячейку в коллекцию. |
| [Add](./add/)(const System::SharedPtr\<Cell\>\&) | Добавить ячейку в коллекцию. |
| [begin](./begin/)() | Получает итератор, указывающий на первый элемент (если он существует) коллекции. |
| [begin](./begin/)() const | Получает итератор, указывающий на первый элемент (если он существует) константно-квалифицированного экземпляра коллекции. |
| [cbegin](./cbegin/)() const | Получает итератор, указывающий на первый константно-квалифицированный элемент (если он существует) коллекции. |
| [Cells](./cells/)() |  |
| [cend](./cend/)() const | Получает итератор, указывающий сразу после последнего константно-квалифицированного элемента (если он существует) коллекции. |
| [Dispose](./dispose/)() | Метод Dispose. |
| [end](./end/)() | Получает итератор, указывающий сразу после последнего элемента (если он существует) коллекции. |
| [end](./end/)() const | Получает итератор, указывающий сразу после последнего элемента (если он существует) константно-квалифицированного экземпляра коллекции. |
| [get_Count](./get_count/)() | Количество элементов. |
| [GetEnumerator](./getenumerator/)() override | Получает перечислитель коллекции. |
| [idx_get](./idx_get/)(int32_t) | Получает ячейки. |
| [idx_set](./idx_set/)(int32_t, const System::SharedPtr\<Cell\>\&) | Устанавливает ячейки. |
| [Insert](./insert/)(int32_t, const System::SharedPtr\<Cell\>\&) | Вставить ячейку в коллекцию. |
| [Remove](./remove/)(const System::SharedPtr\<Cell\>\&) | Удалить набор ячеек из коллекции. |
| [RemoveRange](./removerange/)(int32_t, int32_t) | Удалить набор ячеек из коллекции. |
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
