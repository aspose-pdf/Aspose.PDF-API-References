---
title: System::Text::DecoderReplacementFallbackBuffer::Fallback method
linktitle: Fallback
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::DecoderReplacementFallbackBuffer::Fallback method. Handles decoding failure in C++.'
type: docs
weight: 200
url: /cpp/system.text/decoderreplacementfallbackbuffer/fallback/
---
## DecoderReplacementFallbackBuffer::Fallback method


Handles decoding failure.

```cpp
virtual bool System::Text::DecoderReplacementFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| bytesUnknown | ArrayPtr\<uint8_t\> | [Array](../../../system/array/) of unknown bytes; ignored. |
| index | int | Unknown bytes offset; ignored. |

### ReturnValue

True if replacement string is provided and is not empty, false otherwise.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DecoderReplacementFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
