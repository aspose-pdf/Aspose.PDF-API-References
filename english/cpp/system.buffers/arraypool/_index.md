---
title: System::Buffers::ArrayPool class
linktitle: ArrayPool
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::ArrayPool class. Provides a thread-safe pool for reusing managed array instances (ArrayPtr<T>) in C++.'
type: docs
weight: 200
url: /cpp/system.buffers/arraypool/
---
## ArrayPool class


Provides a thread-safe pool for reusing managed array instances ([ArrayPtr<T>](../../system/arrayptr/)).

```cpp
template<typename T>class ArrayPool : public System::Object
```


| Parameter | Description |
| --- | --- |
| T | The type of elements held by pooled arrays. |
## Methods

| Method | Description |
| --- | --- |
| explicit [ArrayPool](./arraypool/)(int32_t, int32_t) | Creates an [ArrayPool](./) instance. |
| static [Create](./create/)(int32_t, int32_t) | Creates a new pool instance with custom configuration options. |
| static [get_Shared](./get_shared/)() | Retrieves the process-wide shared pool instance. The instance is created lazily on first access and configured with the default options. |
| [Rent](./rent/)(int32_t) | Obtains a buffer that is at least **minimumLength** long. |
| [Return](./return/)(const ArrayPtr\<T\>\&, bool) | Returns a previously rented buffer back to the pool. |

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Buffers](../)
* Library [Aspose.PDF for C++](../../)
