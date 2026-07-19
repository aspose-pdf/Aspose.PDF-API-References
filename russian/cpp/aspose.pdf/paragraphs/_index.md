---
title: "Класс Aspose::Pdf::Paragraphs"
linktitle: "Параграфы"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Paragraphs. Этот класс представляет коллекцию параграфов в C++."
type: docs
weight: 14600
url: /ru/cpp/aspose.pdf/paragraphs/
---
## Paragraphs class


Этот класс представляет коллекцию абзацев.

```cpp
class Paragraphs : public System::Collections::Generic::IEnumerable<System::SharedPtr<BaseParagraph>>,
                   public System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<BaseParagraph\>\&) | Добавить параграф в коллекцию. |
| [begin](./begin/)() | Получает итератор, указывающий на первый элемент (если он существует) коллекции. |
| [begin](./begin/)() const | Получает итератор, указывающий на первый элемент (если он существует) константно-квалифицированного экземпляра коллекции. |
| [cbegin](./cbegin/)() const | Получает итератор, указывающий на первый константно-квалифицированный элемент (если он существует) коллекции. |
| [cend](./cend/)() const | Получает итератор, указывающий сразу после последнего константно-квалифицированного элемента (если он существует) коллекции. |
| [Clear](./clear/)() | Очистить параграфы. |
| [Clone](./clone/)() override | Создаёт новый объект [Clone](./clone/). |
| [cpp_switch_last_paragraph_to_week](./cpp_switch_last_paragraph_to_week/)() |  |
| [end](./end/)() | Получает итератор, указывающий сразу после последнего элемента (если он существует) коллекции. |
| [end](./end/)() const | Получает итератор, указывающий сразу после последнего элемента (если он существует) константно-квалифицированного экземпляра коллекции. |
| [get_Count](./get_count/)() | Получить количество параграфов. |
| [GetEnumerator](./getenumerator/)() override | Получает перечислитель. |
| [GetRange](./getrange/)(int32_t, int32_t) | Удалить диапазон параграфов. |
| [idx_get](./idx_get/)(int32_t) | Получает параграф из или в коллекцию. |
| [idx_set](./idx_set/)(int32_t, const System::SharedPtr\<BaseParagraph\>\&) | Устанавливает параграф из или в коллекцию. |
| [Insert](./insert/)(int32_t, const System::SharedPtr\<BaseParagraph\>\&) | Вставить параграф в коллекцию. |
| [InsertRange](./insertrange/)(int32_t, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<BaseParagraph\>\>\>\&) | Вставляет элементы коллекции в список в указанном индексе. |
| [Paragraphs](./paragraphs/)() |  |
| [Remove](./remove/)(const System::SharedPtr\<BaseParagraph\>\&) | Удалить параграф из коллекции. |
| [RemoveRange](./removerange/)(int32_t, int32_t) | Удалить диапазон параграфов. |
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
* Class [ICloneable](../../system/icloneable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
