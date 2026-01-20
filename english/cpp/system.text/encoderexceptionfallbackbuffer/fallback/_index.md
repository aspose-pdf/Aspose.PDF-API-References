---
title: System::Text::EncoderExceptionFallbackBuffer::Fallback method
linktitle: Fallback
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::EncoderExceptionFallbackBuffer::Fallback method. Handles encoding failure in C++.'
type: docs
weight: 200
url: /cpp/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) method


Handles encoding failure.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| charUnknown | char_t | Unknown characters; ignored. |
| index | int | Unknown characters offset; ignored. |

### ReturnValue

Never actually returns, throws instead.

## See Also

* Class [EncoderExceptionFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) method


Handles encoding failure.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| charUnknownHigh | char_t | High part of surrogate pair that triggered error. |
| charUnknownLow | char_t | Low part of surrogate pair that triggered error. |
| index | int | Unknown character offset; ignored. |

### ReturnValue

Never actually returns, throws instead.

## See Also

* Class [EncoderExceptionFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
