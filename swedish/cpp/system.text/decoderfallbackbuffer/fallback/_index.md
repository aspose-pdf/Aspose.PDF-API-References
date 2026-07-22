---
title: "System::Text::DecoderFallbackBuffer::Fallback‑metod"
linktitle: "Fallback"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::DecoderFallbackBuffer::Fallback‑metod. Implementerar den faktiska fallback‑proceduren i C++."
type: docs
weight: 100
url: /sv/cpp/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback method


Implementerar den faktiska fallback‑proceduren.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytesUnknown | ArrayPtr\<uint8_t\> | [Array](../../../system/array/) av byte inklusive den som avkodaren misslyckas med att avkoda. |
| index | int | [Index](../../../system/index/) för byte som utlöste fel. |

### ReturnValue

Sant om bufferten behandlar okända byte, falskt om den ignorerar dem.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DecoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
