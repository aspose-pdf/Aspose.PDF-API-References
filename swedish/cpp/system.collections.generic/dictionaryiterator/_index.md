---
title: "System::Collections::Generic::DictionaryIterator-klass"
linktitle: "DictionaryIterator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::DictionaryIterator-klass. Dictionary-iterator som tillhandahåller KeyValuePair-notation i C++."
type: docs
weight: 1200
url: /sv/cpp/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator class


[Dictionary](../dictionary/) iterator that provides [KeyValuePair](../keyvaluepair/) notation.

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```


| Parameter | Beskrivning |
| --- | --- |
| Dict | [Dictionary](../dictionary/) klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Klonar aktuell iterator. |
| [DecrementIterator](./decrementiterator/)() override | Flyttar iteratorn ett steg bakåt. |
| [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
| [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
| [DictionaryIterator](./dictionaryiterator/)(DictionaryIterator\&&) | Flyttkonstruktor. |
| [IncrementIterator](./incrementiterator/)() override | Flyttar iteratorn ett steg framåt. |
| [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Flyttar iteratorn med det angivna antalet steg. |
| virtual [~DictionaryIterator](./~dictionaryiterator/)() | Destruktor. |

## Se även

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
