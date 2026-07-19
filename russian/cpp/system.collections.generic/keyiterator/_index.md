---
title: "System::Collections::Generic::KeyIterator класс"
linktitle: "KeyIterator"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::KeyIterator класс. Итератор словаря, предоставляющий доступ к ключам в C++."
type: docs
weight: 2800
url: /ru/cpp/system.collections.generic/keyiterator/
---
## KeyIterator class


[Dictionary](../dictionary/) iterator that provides key access.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```


| Параметр | Описание |
| --- | --- |
| Dict | [Dictionary](../dictionary/) класс. |
## Методы

| Метод | Описание |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Клонирует текущий итератор. |
| [DecrementIterator](./decrementiterator/)() override | Перемещает итератор на шаг назад. |
| [IncrementIterator](./incrementiterator/)() override | Перемещает итератор на шаг вперёд. |
| [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Конструктор. |
| [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Конструктор. |
| [KeyIterator](./keyiterator/)(KeyIterator\&&) | Конструктор перемещения. |
| [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Перемещает итератор на указанное количество шагов. |
| virtual [~KeyIterator](./~keyiterator/)() | Деструктор. |

## См. также

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
