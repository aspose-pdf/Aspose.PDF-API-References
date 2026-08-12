---
title: "Класс Aspose::Pdf::BoundsCheckableList"
linktitle: "BoundsCheckableList"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::BoundsCheckableList. Представляет BoundsCheckableList — обёртку над System.Collections.Generic.List в C++."
type: docs
weight: 1400
url: /ru/cpp/aspose.pdf/boundscheckablelist/
---
## BoundsCheckableList class


Представляет [BoundsCheckableList](./) — обёртку над [System.Collections.Generic.List](../../system.collections.generic/list/).

```cpp
template<typename T>class BoundsCheckableList : public System::Collections::Generic::IList<T>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const T\&) override | Добавляет объект в конец [System.Collections.Generic.List](../../system.collections.generic/list/) в зависимости от параметра "boundsCheckMode". |
| [begin](./begin/)() | Получает итератор, указывающий на первый элемент (если он существует) коллекции. |
| [begin](./begin/)() const | Получает итератор, указывающий на первый элемент (если он существует) константно-квалифицированного экземпляра коллекции. |
| [BoundsCheckableList](./boundscheckablelist/)() | Инициализирует новый экземпляр класса [BoundsCheckableList](./). |
| [BoundsCheckableList](./boundscheckablelist/)(BoundsCheckMode, double, double) | Инициализирует новый экземпляр класса [BoundsCheckableList](./). |
| [cbegin](./cbegin/)() const | Получает итератор, указывающий на первый константно-квалифицированный элемент (если он существует) коллекции. |
| [cend](./cend/)() const | Получает итератор, указывающий сразу после последнего константно-квалифицированного элемента (если он существует) коллекции. |
| [Clear](./clear/)() override | Удаляет все элементы из [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [Contains](./contains/)(const T\&) const override | Определяет, находится ли элемент в [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int32_t) override | Копирует весь [System.Collections.Generic.List](../../system.collections.generic/list/) в совместимый одномерный массив, начиная с указанного индекса целевого массива. |
| [end](./end/)() | Получает итератор, указывающий сразу после последнего элемента (если он существует) коллекции. |
| [end](./end/)() const | Получает итератор, указывающий сразу после последнего элемента (если он существует) константно-квалифицированного экземпляра коллекции. |
| [get_Count](./get_count/)() const override | Получает количество элементов, содержащихся в [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [get_IsReadOnly](./get_isreadonly/)() const override | Получает значение, указывающее, является ли коллекция только для чтения. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель, который перебирает [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [idx_get](./idx_get/)(int32_t) const override | Получает параграф из или в коллекцию. |
| [idx_set](./idx_set/)(int32_t, T) override | Устанавливает параграф из или в коллекцию. |
| [IndexOf](./indexof/)(const T\&) const override | Ищет указанный объект и возвращает нулевой индекс первого вхождения во весь [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [Insert](./insert/)(int32_t, const T\&) override | Вставляет элемент в [System.Collections.Generic.List](../../system.collections.generic/list/) по указанному индексу. |
| [Remove](./remove/)(const T\&) override | Удаляет первое вхождение конкретного объекта из [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [RemoveAt](./removeat/)(int32_t) override | Удаляет элемент по указанному индексу из [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Устанавливает n‑й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| [UpdateBoundsCheckMode](./updateboundscheckmode/)(BoundsCheckMode, double, double) | Обновляет параметр boundsCheckMode для инициализированной коллекции. |
| [UpdateBoundsCheckMode](./updateboundscheckmode/)(BoundsCheckMode) | Обновляет параметр boundsCheckMode для инициализированной коллекции. |
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

* Class [IList](../../system.collections.generic/ilist/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
