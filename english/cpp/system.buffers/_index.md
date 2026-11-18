---
title: System::Buffers namespace
linktitle: System::Buffers
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Buffers namespace in C++.'
type: docs
weight: 2900
url: /cpp/system.buffers/
---



## Classes

| Class | Description |
| --- | --- |
| [ArrayBufferWriter](./arraybufferwriter/) | Represents a heap-based, array-backed output sink into which data can be written. |
| [ArrayPool](./arraypool/) | Provides a thread-safe pool for reusing managed array instances ([ArrayPtr<T>](../system/arrayptr/)). |
| [BuffersExtensions](./buffersextensions/) | Provides extension-style helper methods for working with buffers. |
| [IBufferWriter](./ibufferwriter/) | Represents a sink for data, into which a consumer can write data. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [MemoryHandle](./memoryhandle/) | Represents a handle to a block of memory. |
| [MemoryManager](./memorymanager/) | Provides an abstraction for managing memory blocks. |
| [ReadOnlySequence](./readonlysequence/) | Represents a sequence of elements that can be backed either by a single contiguous memory block or by a linked list of contiguous memory segments. |
| [ReadOnlySequenceSegment](./readonlysequencesegment/) | Represents a linked-list node that holds a single contiguous memory segment participating in a multi-segment [ReadOnlySequence<T>](./readonlysequence/). |
| [SearchValues](./searchvalues/) | Provides an immutable, read-only set of values optimized for efficient searching. Values are stored in a hash set, so [Contains()](./searchvalues/contains/) performs an average O(1) lookup. |
| [StandardFormat](./standardformat/) | Represents a standard format specifier with an optional precision. It wraps a format symbol (a single character, e.g. 'D', 'X', 'O', or '\0' for the default format) and an optional precision in the range [0, 99]. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../system/smartptr/) class to manage objects of this type. |
## Enums

| Enum | Description |
| --- | --- |
| [OperationStatus](./operationstatus/) | Represents the status of an operation that processes a buffer. |
