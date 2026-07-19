---
title: "Aspose::Pdf::Structure::ElementCollection класс"
linktitle: "ElementCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Structure::ElementCollection класс. Коллекция базовых элементов логической структуры в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.structure/elementcollection/
---
## ElementCollection class


[Collection](../../aspose.pdf/collection/) of base logical structure elements.

```cpp
class ElementCollection : public System::Collections::Generic::IEnumerable<System::SharedPtr<Element>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [begin](./begin/)() | Получает итератор, указывающий на первый элемент (если он существует) коллекции. |
| [begin](./begin/)() const | Получает итератор, указывающий на первый элемент (если он существует) константно-квалифицированного экземпляра коллекции. |
| [cbegin](./cbegin/)() const | Получает итератор, указывающий на первый константно-квалифицированный элемент (если он существует) коллекции. |
| [cend](./cend/)() const | Получает итератор, указывающий сразу после последнего константно-квалифицированного элемента (если он существует) коллекции. |
| [end](./end/)() | Получает итератор, указывающий сразу после последнего элемента (если он существует) коллекции. |
| [end](./end/)() const | Получает итератор, указывающий сразу после последнего элемента (если он существует) константно-квалифицированного экземпляра коллекции. |
| [get_Count](./get_count/)() | Количество элементов. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель, который проходит по коллекции. |
| [idx_get](./idx_get/)(int32_t) | Получает [Element](../element/) по индексу. |
| [Remove](./remove/)(const System::SharedPtr\<Element\>\&) | Удалить элемент из коллекции. |
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
* Namespace [Aspose::Pdf::Structure](../)
* Library [Aspose.PDF for C++](../../)
