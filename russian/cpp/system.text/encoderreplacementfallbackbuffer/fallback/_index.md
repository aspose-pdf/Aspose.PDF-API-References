---
title: "System::Text::EncoderReplacementFallbackBuffer::Fallback метод"
linktitle: "Fallback"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::EncoderReplacementFallbackBuffer::Fallback метод. Обрабатывает сбой кодирования в C++."
type: docs
weight: 200
url: /ru/cpp/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) method


Обрабатывает сбой кодирования.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| charUnknown | char_t | Неизвестный символ; игнорируется. |
| индекс | int | Неизвестная позиция символа; игнорируется. |

### ReturnValue

True, если строка замены предоставлена и не пуста, иначе false.

## См. также

* Class [EncoderReplacementFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) method


Обрабатывает сбой кодирования.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| charUnknownHigh | char_t | Высокая часть суррогатной пары, вызвавшей ошибку. |
| charUnknownLow | char_t | Низкая часть суррогатной пары, вызвавшей ошибку. |
| индекс | int | Неизвестная позиция символа; игнорируется. |

### ReturnValue

True, если строка замены предоставлена и не пуста, иначе false.

## См. также

* Class [EncoderReplacementFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
