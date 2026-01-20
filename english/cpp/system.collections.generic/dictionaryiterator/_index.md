---
title: System::Collections::Generic::DictionaryIterator class
linktitle: DictionaryIterator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::DictionaryIterator class. Dictionary iterator that provides KeyValuePair notation in C++.'
type: docs
weight: 1200
url: /cpp/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator class


[Dictionary](../dictionary/) iterator that provides [KeyValuePair](../keyvaluepair/) notation.

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```


| Parameter | Description |
| --- | --- |
| Dict | [Dictionary](../dictionary/) class. |
## Methods

| Method | Description |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Clones current iterator. |
| [DecrementIterator](./decrementiterator/)() override | Moves the iterator step back. |
| [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Constructor. |
| [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Constructor. |
| [DictionaryIterator](./dictionaryiterator/)(DictionaryIterator\&&) | Move constructor. |
| [IncrementIterator](./incrementiterator/)() override | Moves the iterator step forward. |
| [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Moves the iterator by the specified number of steps. |
| virtual [~DictionaryIterator](./~dictionaryiterator/)() | Destructor. |

## See Also

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
