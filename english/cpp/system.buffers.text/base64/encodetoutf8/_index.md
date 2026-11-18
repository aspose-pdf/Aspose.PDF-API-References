---
title: System::Buffers::Text::Base64::EncodeToUtf8 method
linktitle: EncodeToUtf8
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::Text::Base64::EncodeToUtf8 method. Encodes the span of bytes into UTF-8 encoded base-64 text in C++.'
type: docs
weight: 300
url: /cpp/system.buffers.text/base64/encodetoutf8/
---
## Base64::EncodeToUtf8 method


Encodes the span of bytes into UTF-8 encoded base-64 text.

```cpp
static OperationStatus System::Buffers::Text::Base64::EncodeToUtf8(ReadOnlySpan<uint8_t> source, Span<uint8_t> destination, int32_t &consumed, int32_t &written)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | ReadOnlySpan\<uint8_t\> | The span of bytes to encode. |
| destination | Span\<uint8_t\> | The destination span for the encoded text. |
| consumed | int32_t\& | The number of source bytes consumed. |
| written | int32_t\& | The number of bytes written to the destination. |

### ReturnValue

The status of the operation.

## See Also

* Enum [OperationStatus](../../../system.buffers/operationstatus/)
* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Class [Span](../../../system/span/)
* Class [Base64](../)
* Namespace [System::Buffers::Text](../../)
* Library [Aspose.PDF for C++](../../../)
