---
title: System::Text::DecoderFallbackBuffer::Fallback method
linktitle: Fallback
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::DecoderFallbackBuffer::Fallback method. Implements actual fallback procedure in C++.'
type: docs
weight: 100
url: /cpp/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback method


Implements actual fallback procedure.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| bytesUnknown | ArrayPtr\<uint8_t\> | [Array](../../../system/array/) of bytes including the one decoder fails to decode. |
| index | int | Index of byte that triggered error. |

### ReturnValue

True if buffer processes unknown bytes, false if it ignores them.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DecoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
