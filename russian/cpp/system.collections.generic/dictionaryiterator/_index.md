---
title: "Класс System::Collections::Generic::DictionaryIterator"
linktitle: "DictionaryIterator"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Collections::Generic::DictionaryIterator. Перечислитель словаря, предоставляющий нотацию KeyValuePair в C++."
type: docs
weight: 1200
url: /ru/cpp/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator class


[Dictionary](../dictionary/) iterator that provides [KeyValuePair](../keyvaluepair/) notation.

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```


| Параметр | Описание |
| --- | --- |
| Dict | [Dictionary](../dictionary/) класс. |
## Методы

| Метод | Описание |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Клонирует текущий итератор. |
| [DecrementIterator](./decrementiterator/)() override | Перемещает итератор на шаг назад. |
| [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Конструктор. |
| [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Конструктор. |
| [DictionaryIterator](./dictionaryiterator/)(DictionaryIterator\&&) | Конструктор перемещения. |
| [IncrementIterator](./incrementiterator/)() override | Перемещает итератор на шаг вперёд. |
| [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Перемещает итератор на указанное количество шагов. |
| virtual [~DictionaryIterator](./~dictionaryiterator/)() | Деструктор. |

## См. также

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
