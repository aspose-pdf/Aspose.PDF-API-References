---
title: System::Text::Json::PooledByteBufferWriter::GetMemory method
linktitle: GetMemory
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Json::PooledByteBufferWriter::GetMemory method. Returns a Memory that can be written to, and is guaranteed to have at least sizeHint elements in C++.'
type: docs
weight: 1100
url: /cpp/system.text.json/pooledbytebufferwriter/getmemory/
---
## PooledByteBufferWriter::GetMemory method


Returns a [Memory](../../../system/memory/) that can be written to, and is guaranteed to have at least **sizeHint** elements.

```cpp
Memory<uint8_t> System::Text::Json::PooledByteBufferWriter::GetMemory(int32_t sizeHint=MinimumBufferSize) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| sizeHint | int32_t | The minimum number of elements that must be available. |

### ReturnValue

A [Memory](../../../system/memory/) that can be written to.

## See Also

* Class [Memory](../../../system/memory/)
* Class [PooledByteBufferWriter](../)
* Namespace [System::Text::Json](../../)
* Library [Aspose.PDF for C++](../../../)
