---
title: System::Collections::Generic::KeyIterator class
linktitle: KeyIterator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::KeyIterator class. Dictionary iterator that provides key access in C++.'
type: docs
weight: 2800
url: /cpp/system.collections.generic/keyiterator/
---
## KeyIterator class


[Dictionary](../dictionary/) iterator that provides key access.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```


| Parameter | Description |
| --- | --- |
| Dict | [Dictionary](../dictionary/) class. |
## Methods

| Method | Description |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Clones current iterator. |
| [DecrementIterator](./decrementiterator/)() override | Moves the iterator step back. |
| [IncrementIterator](./incrementiterator/)() override | Moves the iterator step forward. |
| [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Constructor. |
| [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Constructor. |
| [KeyIterator](./keyiterator/)(KeyIterator\&&) | Move constructor. |
| [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Moves the iterator by the specified number of steps. |
| virtual [~KeyIterator](./~keyiterator/)() | Destructor. |

## See Also

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
