---
title: "System::Collections::Generic::ValueIterator-klass"
linktitle: "ValueIterator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::ValueIterator-klass. Dictionary-iterator som ger åtkomst till värden i C++."
type: docs
weight: 4800
url: /sv/cpp/system.collections.generic/valueiterator/
---
## ValueIterator class


[Dictionary](../dictionary/) iterator that provides value access.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```


| Parameter | Beskrivning |
| --- | --- |
| Dict | [Dictionary](../dictionary/) klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Klonar aktuell iterator. |
| [DecrementIterator](./decrementiterator/)() override | Flyttar iteratorn ett steg bakåt. |
| [IncrementIterator](./incrementiterator/)() override | Flyttar iteratorn ett steg framåt. |
| [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Flyttar iteratorn med det angivna antalet steg. |
| [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
| [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
| [ValueIterator](./valueiterator/)(ValueIterator\&&) | Flyttkonstruktor. |
| virtual [~ValueIterator](./~valueiterator/)() | Destruktor. |

## Se även

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
