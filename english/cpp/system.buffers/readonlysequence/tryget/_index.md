---
title: System::Buffers::ReadOnlySequence::TryGet method
linktitle: TryGet
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::ReadOnlySequence::TryGet method. Retrieves the memory block that contains the given position in C++.'
type: docs
weight: 1500
url: /cpp/system.buffers/readonlysequence/tryget/
---
## ReadOnlySequence::TryGet method


Retrieves the memory block that contains the given position.

```cpp
bool System::Buffers::ReadOnlySequence<T>::TryGet(SequencePosition &position, ReadOnlyMemory<T> &memory, bool advance) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| position | SequencePosition\& | On input, a position identifying a segment. On output, updated to the position of the first element of the next segment (if **advance** is true), or left at the end of the returned memory otherwise. |
| memory | ReadOnlyMemory\<T\>\& | When this method returns, contains the memory block starting at the given position. |
| advance | bool | True to advance the position to the next segment after reading. |

### ReturnValue

True if a segment was found and **memory** was populated; otherwise, false.

## See Also

* Class [SequencePosition](../../../system/sequenceposition/)
* Class [ReadOnlyMemory](../../../system/readonlymemory/)
* Class [ReadOnlySequence](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
