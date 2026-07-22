---
title: "System::Text::EncoderReplacementFallbackBuffer::Fallback metod"
linktitle: "Fallback"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::EncoderReplacementFallbackBuffer::Fallback metod. Hanterar kodningsfel i C++."
type: docs
weight: 200
url: /sv/cpp/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) method


Hantera kodningsfel.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| charUnknown | char_t | Okänt tecken; ignorerat. |
| index | int | Okänd teckenposition; ignorerat. |

### ReturnValue

Sant om ersättningssträngen är angiven och inte är tom, falskt annars.

## Se även

* Class [EncoderReplacementFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) method


Hantera kodningsfel.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| charUnknownHigh | char_t | Hög del av surrogatpar som orsakade fel. |
| charUnknownLow | char_t | Låg del av surrogatpar som orsakade fel. |
| index | int | Okänd teckenposition; ignorerat. |

### ReturnValue

Sant om ersättningssträngen är angiven och inte är tom, falskt annars.

## Se även

* Class [EncoderReplacementFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
