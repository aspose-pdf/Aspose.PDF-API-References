---
title: System::Buffers::Text::Base64::DecodeFromUtf8 method
linktitle: DecodeFromUtf8
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::Text::Base64::DecodeFromUtf8 method. Decodes UTF-8 encoded base-64 text into a span of bytes in C++.'
type: docs
weight: 100
url: /cpp/system.buffers.text/base64/decodefromutf8/
---
## Base64::DecodeFromUtf8 method


Decodes UTF-8 encoded base-64 text into a span of bytes.

```cpp
static OperationStatus System::Buffers::Text::Base64::DecodeFromUtf8(ReadOnlySpan<uint8_t> source, Span<uint8_t> destination, int32_t &consumed, int32_t &written)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | ReadOnlySpan\<uint8_t\> | The span of UTF-8 base-64 text to decode. |
| destination | Span\<uint8_t\> | The destination span for the decoded bytes. |
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
