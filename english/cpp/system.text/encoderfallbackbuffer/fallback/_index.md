---
title: System::Text::EncoderFallbackBuffer::Fallback method
linktitle: Fallback
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::EncoderFallbackBuffer::Fallback method. Implements actual fallback procedure in C++.'
type: docs
weight: 100
url: /cpp/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) method


Implements actual fallback procedure.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| charUnknown | char_t | Character encoder fails to encode. |
| index | int | Index of character that triggered error. |

### ReturnValue

True if buffer processes unknown characters, false if it ignores them.

## See Also

* Class [EncoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## EncoderFallbackBuffer::Fallback(char_t, char_t, int) method


Implements actual fallback procedure.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| charUnknownHigh | char_t | High part of surrogate pair that triggered error. |
| charUnknownLow | char_t | Low part of surrogate pair that triggered error. |
| index | int | Index of character that triggered error. |

### ReturnValue

True if buffer processes unknown characters, false if it ignores them.

## See Also

* Class [EncoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
