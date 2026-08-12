---
title: "System::Text::EncoderFallbackBuffer::Fallback metod"
linktitle: "Fallback"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::EncoderFallbackBuffer::Fallback metod. Implementerar den faktiska fallback‑proceduren i C++."
type: docs
weight: 100
url: /sv/cpp/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) method


Implementerar den faktiska fallback‑proceduren.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| charUnknown | char_t | Teckenkodaren misslyckas med att koda. |
| index | int | [Index](../../../system/index/) för tecken som utlöste fel. |

### ReturnValue

Sant om bufferten behandlar okända tecken, falskt om den ignorerar dem.

## Se även

* Class [EncoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## EncoderFallbackBuffer::Fallback(char_t, char_t, int) method


Implementerar den faktiska fallback‑proceduren.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| charUnknownHigh | char_t | Hög del av surrogatpar som orsakade fel. |
| charUnknownLow | char_t | Låg del av surrogatpar som orsakade fel. |
| index | int | [Index](../../../system/index/) för tecken som utlöste fel. |

### ReturnValue

Sant om bufferten behandlar okända tecken, falskt om den ignorerar dem.

## Se även

* Class [EncoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
