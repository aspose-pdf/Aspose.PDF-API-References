---
title: System::Text::EncoderReplacementFallbackBuffer::Fallback method
linktitle: Fallback
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::EncoderReplacementFallbackBuffer::Fallback method. Handles encoding failure in C++.'
type: docs
weight: 200
url: /cpp/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) method


Handles encoding failure.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| charUnknown | char_t | Unknown character; ignored. |
| index | int | Unknown character position; ignored. |

### ReturnValue

True if replacement string is provided and is not empty, false otherwise.

## See Also

* Class [EncoderReplacementFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) method


Handles encoding failure.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| charUnknownHigh | char_t | High part of surrogate pair that triggered error. |
| charUnknownLow | char_t | Low part of surrogate pair that triggered error. |
| index | int | Unknown character position; ignored. |

### ReturnValue

True if replacement string is provided and is not empty, false otherwise.

## See Also

* Class [EncoderReplacementFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
