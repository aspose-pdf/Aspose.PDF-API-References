---
title: System::Runtime::InteropServices::MemoryMarshal class
linktitle: MemoryMarshal
second_title: Aspose.PDF for C++ API Reference
description: 'System::Runtime::InteropServices::MemoryMarshal class. Provides memory marshalling implementation. For compatibility with translated code only, as no managed code is supported on C++ side. This is a static type with no instance services. You should never create instances of it by any means in C++.'
type: docs
weight: 200
url: /cpp/system.runtime.interopservices/memorymarshal/
---
## MemoryMarshal class


Provides memory marshalling implementation. For compatibility with translated code only, as no managed code is supported on C++ side. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class MemoryMarshal
```

## Methods

| Method | Description |
| --- | --- |
| static [AsBytes](./asbytes/)(const Span\<T\>\&) | Casts a [Span](../../system/span/) of one primitive type T to [Span](../../system/span/) of bytes. |
| static [AsMemory](./asmemory/)(const ReadOnlyMemory\<T\>\&) | Casts a [ReadOnlyMemory](../../system/readonlymemory/) to mutable [Memory](../../system/memory/). |
| static [Cast](./cast/)(const Span\<TFrom\>\&) | Casts a [Span](../../system/span/) of one primitive type TFrom to another primitive type TTo. |
| static [GetReference](./getreference/)(const Span\<T\>\&) | Gets a reference to the first element of the specified span. |
| static [GetReference](./getreference/)(const ReadOnlySpan\<T\>\&) | Gets a reference to the first element of the specified read-only span. |
## See Also

* Namespace [System::Runtime::InteropServices](../)
* Library [Aspose.PDF for C++](../../)
