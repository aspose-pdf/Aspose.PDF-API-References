---
title: System::Runtime::InteropServices::MemoryMarshal::GetReference method
linktitle: GetReference
second_title: Aspose.PDF for C++ API Reference
description: 'System::Runtime::InteropServices::MemoryMarshal::GetReference method. Gets a reference to the first element of the specified read-only span in C++.'
type: docs
weight: 400
url: /cpp/system.runtime.interopservices/memorymarshal/getreference/
---
## MemoryMarshal::GetReference(const ReadOnlySpan\<T\>\&) method


Gets a reference to the first element of the specified read-only span.

```cpp
template<typename T> static T & System::Runtime::InteropServices::MemoryMarshal::GetReference(const ReadOnlySpan<T> &span)
```


| Parameter | Description |
| --- | --- |
| T | The type of elements in the read-only span. |

| Parameter | Type | Description |
| --- | --- | --- |
| span | const ReadOnlySpan\<T\>\& | The read-only span to access. |

### ReturnValue

A reference to the first element of the read-only span.

## See Also

* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Class [MemoryMarshal](../)
* Namespace [System::Runtime::InteropServices](../../)
* Library [Aspose.PDF for C++](../../../)
## MemoryMarshal::GetReference(const Span\<T\>\&) method


Gets a reference to the first element of the specified span.

```cpp
template<typename T> static T & System::Runtime::InteropServices::MemoryMarshal::GetReference(const Span<T> &span)
```


| Parameter | Description |
| --- | --- |
| T | The type of elements in the span. |

| Parameter | Type | Description |
| --- | --- | --- |
| span | const Span\<T\>\& | The span to access. |

### ReturnValue

A reference to the first element of the span.

## See Also

* Class [Span](../../../system/span/)
* Class [MemoryMarshal](../)
* Namespace [System::Runtime::InteropServices](../../)
* Library [Aspose.PDF for C++](../../../)
