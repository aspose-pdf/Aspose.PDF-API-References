---
title: System::Buffers::ReadOnlySequence::ReadOnlySequence constructor
linktitle: ReadOnlySequence
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::ReadOnlySequence::ReadOnlySequence constructor. Constructs an empty ReadOnlySequence in C++.'
type: docs
weight: 100
url: /cpp/system.buffers/readonlysequence/readonlysequence/
---
## ReadOnlySequence::ReadOnlySequence() constructor


Constructs an empty [ReadOnlySequence](../).

```cpp
System::Buffers::ReadOnlySequence<T>::ReadOnlySequence()=default
```

## See Also

* Class [ReadOnlySequence](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
## ReadOnlySequence::ReadOnlySequence(const ReadOnlyMemory\<T\>\&) constructor


Constructs a single-segment sequence that wraps the specified contiguous memory.

```cpp
System::Buffers::ReadOnlySequence<T>::ReadOnlySequence(const ReadOnlyMemory<T> &memory)
```


| Parameter | Type | Description |
| --- | --- | --- |
| memory | const ReadOnlyMemory\<T\>\& | The memory block to wrap as a single-segment sequence. |

## See Also

* Class [ReadOnlyMemory](../../../system/readonlymemory/)
* Class [ReadOnlySequence](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
## ReadOnlySequence::ReadOnlySequence(const SequencePosition\&, const SequencePosition\&) constructor


Constructs a multi-segment sequence from a range defined by a start and end position.

```cpp
System::Buffers::ReadOnlySequence<T>::ReadOnlySequence(const SequencePosition &start, const SequencePosition &end)
```


| Parameter | Type | Description |
| --- | --- | --- |
| start | const SequencePosition\& | The position of the first element. |
| end | const SequencePosition\& | The position one past the last element. |

## See Also

* Class [SequencePosition](../../../system/sequenceposition/)
* Class [ReadOnlySequence](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
## ReadOnlySequence::ReadOnlySequence(const SharedPtr\<ReadOnlySequenceSegment\<T\>\>\&, int32_t, const SharedPtr\<ReadOnlySequenceSegment\<T\>\>\&, int32_t) constructor


Constructs a multi-segment sequence from a linked list of segments.

```cpp
System::Buffers::ReadOnlySequence<T>::ReadOnlySequence(const SharedPtr<ReadOnlySequenceSegment<T>> &startSegment, int32_t startIndex, const SharedPtr<ReadOnlySequenceSegment<T>> &endSegment, int32_t endIndex)
```


| Parameter | Type | Description |
| --- | --- | --- |
| startSegment | const SharedPtr\<ReadOnlySequenceSegment\<T\>\>\& | The first segment of the sequence. |
| startIndex | int32_t | The offset of the first element within **startSegment**. |
| endSegment | const SharedPtr\<ReadOnlySequenceSegment\<T\>\>\& | The last segment of the sequence. |
| endIndex | int32_t | The offset one past the last element within **endSegment**. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ReadOnlySequenceSegment](../../readonlysequencesegment/)
* Class [ReadOnlySequence](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
