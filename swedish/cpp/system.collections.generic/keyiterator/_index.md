---
title: "System::Collections::Generic::KeyIterator-klass"
linktitle: "KeyIterator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::KeyIterator-klass. Dictionary-iterator som ger åtkomst till nycklar i C++."
type: docs
weight: 2800
url: /sv/cpp/system.collections.generic/keyiterator/
---
## KeyIterator class


[Dictionary](../dictionary/) iterator that provides key access.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
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
| [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
| [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
| [KeyIterator](./keyiterator/)(KeyIterator\&&) | Flyttkonstruktor. |
| [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Flyttar iteratorn med det angivna antalet steg. |
| virtual [~KeyIterator](./~keyiterator/)() | Destruktor. |

## Se även

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
