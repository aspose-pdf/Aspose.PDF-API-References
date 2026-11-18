---
title: System::Buffers::ReadOnlySequence::Slice method
linktitle: Slice
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::ReadOnlySequence::Slice method. Creates a slice of the sequence defined by a start and end position in C++.'
type: docs
weight: 1400
url: /cpp/system.buffers/readonlysequence/slice/
---
## ReadOnlySequence::Slice(const SequencePosition\&, const SequencePosition\&) const method


Creates a slice of the sequence defined by a start and end position.

```cpp
ReadOnlySequence System::Buffers::ReadOnlySequence<T>::Slice(const SequencePosition &start, const SequencePosition &end) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| start | const SequencePosition\& | The position of the first element of the slice. |
| end | const SequencePosition\& | The position one past the last element of the slice. |

### ReturnValue

A [ReadOnlySequence](../) representing the requested sub-range.

## See Also

* Class [SequencePosition](../../../system/sequenceposition/)
* Class [ReadOnlySequence](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
## ReadOnlySequence::Slice(int64_t) const method


Creates a slice of the sequence starting at the given offset.

```cpp
ReadOnlySequence System::Buffers::ReadOnlySequence<T>::Slice(int64_t start) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| start | int64_t | The offset of the first element of the slice. |

### ReturnValue

A [ReadOnlySequence](../) representing the requested sub-range.

## See Also

* Class [ReadOnlySequence](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
## ReadOnlySequence::Slice(int64_t, int64_t) const method


Creates a slice of the sequence defined by a start and length.

```cpp
ReadOnlySequence System::Buffers::ReadOnlySequence<T>::Slice(int64_t start, int64_t length) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| start | int64_t | The offset of the first element of the slice. |
| length | int64_t | The number of elements in the slice. |

### ReturnValue

A [ReadOnlySequence](../) representing the requested sub-range.

## See Also

* Class [ReadOnlySequence](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
