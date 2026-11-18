---
title: System::Buffers::Text::Base64::DecodeFromUtf8InPlace method
linktitle: DecodeFromUtf8InPlace
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::Text::Base64::DecodeFromUtf8InPlace method. Decodes UTF-8 encoded base-64 text in place in C++.'
type: docs
weight: 200
url: /cpp/system.buffers.text/base64/decodefromutf8inplace/
---
## Base64::DecodeFromUtf8InPlace method


Decodes UTF-8 encoded base-64 text in place.

```cpp
static OperationStatus System::Buffers::Text::Base64::DecodeFromUtf8InPlace(Span<uint8_t> buffer, int32_t &bytesWritten)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | Span\<uint8_t\> | The buffer containing the UTF-8 base-64 text; on success contains the decoded bytes. |
| bytesWritten | int32_t\& | The number of bytes written after decoding. |

### ReturnValue

The status of the operation.

## See Also

* Enum [OperationStatus](../../../system.buffers/operationstatus/)
* Class [Span](../../../system/span/)
* Class [Base64](../)
* Namespace [System::Buffers::Text](../../)
* Library [Aspose.PDF for C++](../../../)
