---
title: System::Collections::Generic::ValueIterator class
linktitle: ValueIterator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::ValueIterator class. Dictionary iterator that provides value access in C++.'
type: docs
weight: 4800
url: /cpp/system.collections.generic/valueiterator/
---
## ValueIterator class


[Dictionary](../dictionary/) iterator that provides value access.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
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
| [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Moves the iterator by the specified number of steps. |
| [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Constructor. |
| [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Constructor. |
| [ValueIterator](./valueiterator/)(ValueIterator\&&) | Move constructor. |
| virtual [~ValueIterator](./~valueiterator/)() | Destructor. |

## See Also

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
