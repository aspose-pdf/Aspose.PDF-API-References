---
title: System::Buffers::ReadOnlySequenceSegment class
linktitle: ReadOnlySequenceSegment
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::ReadOnlySequenceSegment class. Represents a linked-list node that holds a single contiguous memory segment participating in a multi-segment ReadOnlySequence<T> in C++.'
type: docs
weight: 800
url: /cpp/system.buffers/readonlysequencesegment/
---
## ReadOnlySequenceSegment class


Represents a linked-list node that holds a single contiguous memory segment participating in a multi-segment [ReadOnlySequence<T>](../readonlysequence/).

```cpp
template<typename T>class ReadOnlySequenceSegment : public System::Object
```


| Parameter | Description |
| --- | --- |
| T | The type of elements held by the segment. |
## Methods

| Method | Description |
| --- | --- |
| [get_Memory](./get_memory/)() const | Gets the contiguous memory held by this segment. |
| [get_Next](./get_next/)() const | Gets the next segment in the sequence. |
| [get_RunningIndex](./get_runningindex/)() const | Gets the index of the first element of this segment within the overall sequence. |
| [ReadOnlySequenceSegment](./readonlysequencesegment/)() | Constructs an empty segment. |
| explicit [ReadOnlySequenceSegment](./readonlysequencesegment/)(const ReadOnlyMemory\<T\>\&) | Constructs a segment wrapping the given memory block. |
| [set_Memory](./set_memory/)(const ReadOnlyMemory\<T\>\&) | Sets the contiguous memory held by this segment. |
| [set_Next](./set_next/)(const SharedPtr\<ReadOnlySequenceSegment\<T\>\>\&) | Sets the next segment in the sequence. |
| [set_RunningIndex](./set_runningindex/)(int64_t) | Sets the index of the first element of this segment within the overall sequence. |

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Buffers](../)
* Library [Aspose.PDF for C++](../../)
