---
title: System::Text::Encodings::Web::JavaScriptEncoder::EncodeUtf8 method
linktitle: EncodeUtf8
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Encodings::Web::JavaScriptEncoder::EncodeUtf8 method. Escapes a UTF-8 input span into a UTF-8 destination span in C++.'
type: docs
weight: 300
url: /cpp/system.text.encodings.web/javascriptencoder/encodeutf8/
---
## JavaScriptEncoder::EncodeUtf8 method


Escapes a UTF-8 input span into a UTF-8 destination span.

```cpp
Buffers::OperationStatus System::Text::Encodings::Web::JavaScriptEncoder::EncodeUtf8(ReadOnlySpan<uint8_t> utf8Text, Span<uint8_t> destination, int32_t &bytesConsumed, int32_t &bytesWritten, bool isFinalBlock)
```


| Parameter | Type | Description |
| --- | --- | --- |
| utf8Text | ReadOnlySpan\<uint8_t\> | The source UTF-8 text. |
| destination | Span\<uint8_t\> | The destination buffer for the escaped output. |
| bytesConsumed | int32_t\& | The number of source bytes consumed. |
| bytesWritten | int32_t\& | The number of destination bytes written. |
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
