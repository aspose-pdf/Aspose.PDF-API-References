---
title: System::Buffers::ReadOnlySequence class
linktitle: ReadOnlySequence
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::ReadOnlySequence class. Represents a sequence of elements that can be backed either by a single contiguous memory block or by a linked list of contiguous memory segments in C++.'
type: docs
weight: 700
url: /cpp/system.buffers/readonlysequence/
---
## ReadOnlySequence class


Represents a sequence of elements that can be backed either by a single contiguous memory block or by a linked list of contiguous memory segments.

```cpp
template<typename T>class ReadOnlySequence : public System::Details::BoxableObjectBase
```


| Parameter | Description |
| --- | --- |
| T | The type of elements in the sequence. |
## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(const ReadOnlySequence\&) const | Determines whether the current sequence references the same range as the specified sequence. |
| static [get_Empty](./get_empty/)() | Gets the default (empty) [ReadOnlySequence](./) instance. |
| [get_End](./get_end/)() const | Gets the position one past the last element in the sequence. |
| [get_First](./get_first/)() const | Gets the first memory block of the sequence. |
| [get_FirstSpan](./get_firstspan/)() const | Gets the first memory block of the sequence as a read-only span. |
| [get_IsEmpty](./get_isempty/)() const | Determines whether the sequence is empty. |
| [get_IsSingleSegment](./get_issinglesegment/)() const | Determines whether the sequence consists of a single contiguous memory block. |
| [get_Length](./get_length/)() const | Gets the number of elements in the sequence. |
| [get_Start](./get_start/)() const | Gets the position of the first element in the sequence. |
| [GetHashCode](./gethashcode/)() const | Returns a hash code for the current sequence. |
| [GetPosition](./getposition/)(int64_t) const | Gets the position at the specified zero-based offset from the start of the sequence. |
| [GetPosition](./getposition/)(int64_t, const SequencePosition\&) const | Gets the position at the specified zero-based offset from the given origin position. |
| [operator!=](./operator!=/)(const ReadOnlySequence\&) const | Determines whether the current sequence references a different range than the specified sequence. |
| [operator==](./operator==/)(const ReadOnlySequence\&) const | Determines whether the current sequence references the same range as the specified sequence. |
| [ReadOnlySequence](./readonlysequence/)() | Constructs an empty [ReadOnlySequence](./). |
| [ReadOnlySequence](./readonlysequence/)(const ReadOnlyMemory\<T\>\&) | Constructs a single-segment sequence that wraps the specified contiguous memory. |
| [ReadOnlySequence](./readonlysequence/)(const SequencePosition\&, const SequencePosition\&) | Constructs a multi-segment sequence from a range defined by a start and end position. |
| [ReadOnlySequence](./readonlysequence/)(const SharedPtr\<ReadOnlySequenceSegment\<T\>\>\&, int32_t, const SharedPtr\<ReadOnlySequenceSegment\<T\>\>\&, int32_t) | Constructs a multi-segment sequence from a linked list of segments. |
| [Slice](./slice/)(int64_t) const | Creates a slice of the sequence starting at the given offset. |
| [Slice](./slice/)(int64_t, int64_t) const | Creates a slice of the sequence defined by a start and length. |
| [Slice](./slice/)(const SequencePosition\&, const SequencePosition\&) const | Creates a slice of the sequence defined by a start and end position. |
| [TryGet](./tryget/)(SequencePosition\&, ReadOnlyMemory\<T\>\&, bool) const | Retrieves the memory block that contains the given position. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | The default (empty) [ReadOnlySequence](./) instance. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [value_type](./value_type/) | The element type. |

## See Also

* Namespace [System::Buffers](../)
* Library [Aspose.PDF for C++](../../)
