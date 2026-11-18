---
title: System::Text::Json::PooledByteBufferWriter::GetSpan method
linktitle: GetSpan
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Json::PooledByteBufferWriter::GetSpan method. Returns a Span that can be written to, and is guaranteed to have at least sizeHint elements in C++.'
type: docs
weight: 1200
url: /cpp/system.text.json/pooledbytebufferwriter/getspan/
---
## PooledByteBufferWriter::GetSpan method


Returns a [Span](../../../system/span/) that can be written to, and is guaranteed to have at least **sizeHint** elements.

```cpp
Span<uint8_t> System::Text::Json::PooledByteBufferWriter::GetSpan(int32_t sizeHint=MinimumBufferSize) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| sizeHint | int32_t | The minimum number of elements that must be available. |

### ReturnValue

A [Span](../../../system/span/) that can be written to.

## See Also

* Class [Span](../../../system/span/)
* Class [PooledByteBufferWriter](../)
* Namespace [System::Text::Json](../../)
* Library [Aspose.PDF for C++](../../../)
