---
title: System::Buffers::BuffersExtensions::ToArray method
linktitle: ToArray
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::BuffersExtensions::ToArray method. Copies the elements of the given ReadOnlySequence to a newly allocated array in C++.'
type: docs
weight: 200
url: /cpp/system.buffers/buffersextensions/toarray/
---
## BuffersExtensions::ToArray method


Copies the elements of the given [ReadOnlySequence](../../readonlysequence/) to a newly allocated array.

```cpp
template<typename T> static SharedPtr<Array<T>> System::Buffers::BuffersExtensions::ToArray(const ReadOnlySequence<T> &sequence)
```


| Parameter | Description |
| --- | --- |
| T | The type of elements. |

| Parameter | Type | Description |
| --- | --- | --- |
| sequence | const ReadOnlySequence\<T\>\& | The sequence whose elements are copied. |

### ReturnValue

A new array containing a copy of the elements in the sequence.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Array](../../../system/array/)
* Class [ReadOnlySequence](../../readonlysequence/)
* Class [BuffersExtensions](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
