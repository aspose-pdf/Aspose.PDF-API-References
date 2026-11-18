---
title: System::Text::Unicode::Utf8::FromUtf16 method
linktitle: FromUtf16
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Unicode::Utf8::FromUtf16 method. Converts a span of UTF-16 characters into a span of UTF-8 bytes in C++.'
type: docs
weight: 100
url: /cpp/system.text.unicode/utf8/fromutf16/
---
## Utf8::FromUtf16 method


Converts a span of UTF-16 characters into a span of UTF-8 bytes.

```cpp
static Buffers::OperationStatus System::Text::Unicode::Utf8::FromUtf16(ReadOnlySpan<char16_t> source, Span<uint8_t> destination, int32_t &charsRead, int32_t &bytesWritten, bool replaceInvalidSequences, bool isFinalBlock)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | ReadOnlySpan\<char16_t\> | The UTF-16 source characters. |
| destination | Span\<uint8_t\> | The destination buffer for the UTF-8 bytes. |
| charsRead | int32_t\& | The number of source characters consumed. |
| bytesWritten | int32_t\& | The number of destination bytes written. |
| replaceInvalidSequences | bool | Whether to replace invalid sequences with the replacement character. |
| isFinalBlock | bool | Whether this is the final block of input. |

### ReturnValue

The operation status.

## See Also

* Enum [OperationStatus](../../../system.buffers/operationstatus/)
* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Class [Span](../../../system/span/)
* Class [Utf8](../)
* Namespace [System::Text::Unicode](../../)
* Library [Aspose.PDF for C++](../../../)
