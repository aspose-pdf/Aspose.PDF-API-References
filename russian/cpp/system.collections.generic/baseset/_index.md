---
title: "System::Collections::Generic::BaseSet класс"
linktitle: "BaseSet"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать класс System::Collections::Generic::BaseSet в C++."
type: docs
weight: 800
url: /ru/cpp/system.collections.generic/baseset/
---
## BaseSet class




```cpp
template<typename T,typename SET_T>class BaseSet : public virtual System::Object,
                                                   public System::Collections::Generic::ICollection<T>
```

## Nested classes

* Class [Enumerator](./enumerator/)
## Методы

| Метод | Описание |
| --- | --- |
| [_add_range](./_add_range/)(std::initializer_list\<T\>) | Специфично для C++. |
| [Add](./add/)(const T\&) override | Добавляет элемент в множество. |
| [begin](./begin/)() const | Получает итератор к первому элементу константно‑квалифицированной коллекции. |
| [cbegin](./cbegin/)() const | Получает итератор к первому константно‑квалифицированному элементу коллекции. |
| [cend](./cend/)() const | Получает итератор для несуществующего константно‑квалифицированного элемента за концом коллекции. |
| [Clear](./clear/)() override | Удаляет все элементы из множества. |
| [Contains](./contains/)(const T\&) const override | Проверяет, присутствует ли элемент в множестве. |
| [CopyTo](./copyto/)(ArrayPtr\<T\>, int) override | Копирует содержимое хеша в существующие элементы массива. |
| [data](./data/)() | Доступ к базовой структуре данных. |
| [data](./data/)() const | Доступ к базовой структуре данных. |
| [end](./end/)() const | Получает итератор для несуществующего элемента за концом константно‑квалифицированной коллекции. |
| [get_Count](./get_count/)() const override | Получает количество элементов в множестве. |
| [GetEnumerator](./getenumerator/)() override | Создаёт перечислитель. |
| [Remove](./remove/)(const T\&) override | Удаляет элемент из множества. |
| [TryAdd](./tryadd/)(const T\&) | Добавляет элемент в множество. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Получает реализацию константного итератора begin для текущего контейнера. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Получает реализацию итератора begin для текущего контейнера. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Получает реализацию константного итератора end для текущего контейнера. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Получает реализацию итератора end для текущего контейнера. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [BaseType](./basetype/) | Реализованный интерфейс. |
| [const_iterator](./const_iterator/) | Тип константного итератора. |
| [IEnumerablePtr](./ienumerableptr/) | Указатель на интерфейс Enumerable. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) указатель. |
| [iterator](./iterator/) | Тип итератора. |
| [set_t](./set_t/) | Базовый тип данных. |
| [ThisPtr](./thisptr/) | Тип указателя. |
| [ThisType](./thistype/) | Тип самого себя. |
| [ValueType](./valuetype/) | Тип значения. |
## См. также

* Class [Object](../../system/object/)
* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
