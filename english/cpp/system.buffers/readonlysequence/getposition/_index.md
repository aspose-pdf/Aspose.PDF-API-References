---
title: System::Buffers::ReadOnlySequence::GetPosition method
linktitle: GetPosition
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::ReadOnlySequence::GetPosition method. Gets the position at the specified zero-based offset from the start of the sequence in C++.'
type: docs
weight: 1100
url: /cpp/system.buffers/readonlysequence/getposition/
---
## ReadOnlySequence::GetPosition(int64_t) const method


Gets the position at the specified zero-based offset from the start of the sequence.

```cpp
SequencePosition System::Buffers::ReadOnlySequence<T>::GetPosition(int64_t offset) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| offset | int64_t | The number of elements to advance. |

### ReturnValue

The resulting [SequencePosition](../../../system/sequenceposition/).

## See Also

* Class [SequencePosition](../../../system/sequenceposition/)
* Class [ReadOnlySequence](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
## ReadOnlySequence::GetPosition(int64_t, const SequencePosition\&) const method


Gets the position at the specified zero-based offset from the given origin position.

```cpp
SequencePosition System::Buffers::ReadOnlySequence<T>::GetPosition(int64_t offset, const SequencePosition &origin) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| offset | int64_t | The number of elements to advance. |
| origin | const SequencePosition\& | The position from which the offset is measured. |

### ReturnValue

The resulting [SequencePosition](../../../system/sequenceposition/).

## See Also

* Class [SequencePosition](../../../system/sequenceposition/)
* Class [ReadOnlySequence](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
