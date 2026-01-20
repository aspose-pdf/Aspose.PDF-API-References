---
title: System::Collections::Generic::EnumeratorWrapperIterator class
linktitle: EnumeratorWrapperIterator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::EnumeratorWrapperIterator class. Iterator that wraps the pre-created enumerator and redirects all calls into it in C++.'
type: docs
weight: 1500
url: /cpp/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator class


Iterator that wraps the pre-created enumerator and redirects all calls into it.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```


| Parameter | Description |
| --- | --- |
| Element | Element type. |
## Methods

| Method | Description |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Clones current iterator. |
| [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const SharedPtr\<IEnumerator\<Element\>\>\&) |  |
| [IncrementIterator](./incrementiterator/)() override | Moves the iterator step forward. Must update m_is_end and m_pointer. |
| [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | Checks if two iterators point to the same item. |
| virtual [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | Destructor. |

## See Also

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
