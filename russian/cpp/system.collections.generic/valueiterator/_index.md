---
title: "System::Collections::Generic::ValueIterator класс"
linktitle: "ValueIterator"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::ValueIterator класс. Итератор словаря, предоставляющий доступ к значениям в C++."
type: docs
weight: 4800
url: /ru/cpp/system.collections.generic/valueiterator/
---
## ValueIterator class


[Dictionary](../dictionary/) iterator that provides value access.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
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
| [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Перемещает итератор на указанное количество шагов. |
| [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Конструктор. |
| [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Конструктор. |
| [ValueIterator](./valueiterator/)(ValueIterator\&&) | Конструктор перемещения. |
| virtual [~ValueIterator](./~valueiterator/)() | Деструктор. |

## См. также

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
