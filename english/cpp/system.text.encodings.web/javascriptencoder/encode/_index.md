---
title: System::Text::Encodings::Web::JavaScriptEncoder::Encode method
linktitle: Encode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Encodings::Web::JavaScriptEncoder::Encode method. Escapes a UTF-16 input span into a UTF-16 destination span in C++.'
type: docs
weight: 200
url: /cpp/system.text.encodings.web/javascriptencoder/encode/
---
## JavaScriptEncoder::Encode method


Escapes a UTF-16 input span into a UTF-16 destination span.

```cpp
Buffers::OperationStatus System::Text::Encodings::Web::JavaScriptEncoder::Encode(ReadOnlySpan<char16_t> text, Span<char16_t> destination, int32_t &charsConsumed, int32_t &charsWritten, bool isFinalBlock)
```


| Parameter | Type | Description |
| --- | --- | --- |
| text | ReadOnlySpan\<char16_t\> | The source UTF-16 text. |
| destination | Span\<char16_t\> | The destination buffer for the escaped output. |
| charsConsumed | int32_t\& | The number of source characters consumed. |
| charsWritten | int32_t\& | The number of destination characters written. |
| isFinalBlock | bool | Whether this is the final block of input. |

### ReturnValue

The operation status.

## See Also

* Enum [OperationStatus](../../../system.buffers/operationstatus/)
* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Class [Span](../../../system/span/)
* Class [JavaScriptEncoder](../)
* Namespace [System::Text::Encodings::Web](../../)
* Library [Aspose.PDF for C++](../../../)
