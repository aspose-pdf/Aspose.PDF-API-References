---
title: System::Buffers::BuffersExtensions::CopyTo method
linktitle: CopyTo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::BuffersExtensions::CopyTo method. Copies the elements of the given ReadOnlySequence to the destination span in C++.'
type: docs
weight: 100
url: /cpp/system.buffers/buffersextensions/copyto/
---
## BuffersExtensions::CopyTo method


Copies the elements of the given [ReadOnlySequence](../../readonlysequence/) to the destination span.

```cpp
template<typename T> static void System::Buffers::BuffersExtensions::CopyTo(const ReadOnlySequence<T> &source, Span<T> destination)
```


| Parameter | Description |
| --- | --- |
| T | The type of elements. |

| Parameter | Type | Description |
| --- | --- | --- |
| source | const ReadOnlySequence\<T\>\& | The sequence whose elements are copied. |
| destination | Span\<T\> | The destination span to fill. |

## See Also

* Class [ReadOnlySequence](../../readonlysequence/)
* Class [Span](../../../system/span/)
* Class [BuffersExtensions](../)
* Namespace [System::Buffers](../../)
* Library [Aspose.PDF for C++](../../../)
