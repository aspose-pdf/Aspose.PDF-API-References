---
title: "System::Text::DecoderReplacementFallbackBuffer::Fallback metod"
linktitle: "Fallback"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::DecoderReplacementFallbackBuffer::Fallback metod. Hanterar avkodningsfel i C++."
type: docs
weight: 200
url: /sv/cpp/system.text/decoderreplacementfallbackbuffer/fallback/
---
## DecoderReplacementFallbackBuffer::Fallback method


Hantera avkodningsfel.

```cpp
virtual bool System::Text::DecoderReplacementFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytesUnknown | ArrayPtr\<uint8_t\> | [Array](../../../system/array/) av okända byte; ignorerad. |
| index | int | Okänt byteoffset; ignorerat. |

### ReturnValue

Sant om ersättningssträngen är angiven och inte är tom, falskt annars.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DecoderReplacementFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
