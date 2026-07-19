---
title: "System::Text::Decoder::GetChars метод"
linktitle: "GetChars"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::Decoder::GetChars метод. Получает символы, полученные в результате декодирования буфера в C++."
type: docs
weight: 500
url: /ru/cpp/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method


Получить символы, полученные в результате декодирования буфера.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | ArrayPtr\<uint8_t\> | Байты для декодирования. |
| byteIndex | int | Смещение входного буфера. |
| byteCount | int | Размер входного буфера. |
| символы | ArrayPtr\<char_t\> | Буфер назначения символов. |
| charIndex | int | Смещение целевого массива. |

### ReturnValue

Количество записанных символов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) method


Получить символы, полученные в результате декодирования буфера.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | ArrayPtr\<uint8_t\> | Байты для декодирования. |
| byteIndex | int | Смещение входного буфера. |
| byteCount | int | Размер входного буфера. |
| символы | ArrayPtr\<char_t\> | Буфер назначения символов. |
| charIndex | int | Смещение целевого массива. |
| flush | bool | Если true, очищает внутреннее состояние декодера после вычисления. |

### ReturnValue

Количество записанных символов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) method


Получить символы, полученные в результате декодирования буфера.

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | const uint8_t * | Байты для декодирования. |
| byteCount | int | Размер входного буфера. |
| символы | char_t * | Буфер назначения символов. |
| charCount | int | Размер целевого массива. |
| flush | bool | Если true, очищает внутреннее состояние декодера после вычисления. |

### ReturnValue

Количество записанных символов.

## См. также

* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
