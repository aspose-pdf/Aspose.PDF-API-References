---
title: "System::Text::Encoder::Convert метод"
linktitle: "Преобразовать"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::Encoder::Convert метод. Преобразует символы в байты в C++."
type: docs
weight: 100
url: /ru/cpp/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) method


Преобразует символы в байты.

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | ArrayPtr\<char_t\> | Символы для кодирования. |
| charIndex | int | Смещение входного буфера. |
| charCount | int | Размер входного буфера. |
| байты | ArrayPtr\<uint8_t\> | Буфер целевых байтов. |
| byteIndex | int | Смещение целевого массива. |
| byteCount | int | Размер целевого массива. |
| flush | bool | Если true, очищает внутреннее состояние кодировщика после вычисления. |
| charsUsed | int\& | Ссылка на переменную для хранения количества прочитанных символов. |
| bytesUsed | int\& | Ссылка на переменную для хранения количества записанных байтов. |
| completed | bool\& | Ссылка на переменную, которая будет установлена в true, если входной буфер исчерпан, и в false в противном случае. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) method


Преобразует символы в байты.

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | const char_t * | Символы для кодирования. |
| charCount | int | Размер входного буфера. |
| байты | uint8_t * | Буфер целевых байтов. |
| byteCount | int | Размер целевого массива. |
| flush | bool | Если true, очищает внутреннее состояние кодировщика после вычисления. |
| charsUsed | int\& | Ссылка на переменную для хранения количества прочитанных символов. |
| bytesUsed | int\& | Ссылка на переменную для хранения количества записанных байтов. |
| completed | bool\& | Ссылка на переменную, которая будет установлена в true, если входной буфер исчерпан, и в false в противном случае. |

## См. также

* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
