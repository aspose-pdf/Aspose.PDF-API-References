---
title: "Класс System::Collections::Generic::_ValueCollection"
linktitle: "_ValueCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::_ValueCollection класс. Коллекция значений Dictionary. Ссылается на коллекцию, не копирует ничего. Объекты этого класса должны быть выделены только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 300
url: /ru/cpp/system.collections.generic/_valuecollection/
---
## _ValueCollection class


Коллекция значений [Dictionary](../dictionary/). Ссылается на коллекцию, не копирует ничего. Объекты этого класса должны быть выделены только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename Dict>class _ValueCollection : public System::Collections::Generic::BaseKVCollection<Dict, Dict::map_t::mapped_type>
```

## Nested classes

* Class [Enumerator](./enumerator/)
## Методы

| Метод | Описание |
| --- | --- |
| [_ValueCollection](./_valuecollection/)(const typename Dict::Ptr\&) | Инициализирует коллекцию, ссылающуюся на указанный словарь. |
| [Contains](./contains/)(const TValue\&) const override | Проверяет, присутствует ли элемент в контейнере. |
| [GetEnumerator](./getenumerator/)() override | Получает перечислитель, проходящий по значениям. |
| [idx_get](./idx_get/)(int) const override | Реализует метод [IList](../ilist/). Не поддерживается. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Получает реализацию константного итератора begin для текущего контейнера. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Получает реализацию итератора begin для текущего контейнера. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Получает реализацию константного итератора end для текущего контейнера. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Получает реализацию итератора end для текущего контейнера. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [TValue](./tvalue/) | Тип значения. |

## См. также

* Class [BaseKVCollection](../basekvcollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
