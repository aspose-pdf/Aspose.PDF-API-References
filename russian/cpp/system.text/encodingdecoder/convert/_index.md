---
title: "Метод System::Text::EncodingDecoder::Convert"
linktitle: "Преобразовать"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Text::EncodingDecoder::Convert. Преобразует байты в символы в C++."
type: docs
weight: 100
url: /ru/cpp/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method


Преобразует байты в символы.

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | ArrayPtr\<uint8_t\> | Байты для декодирования. |
| byteIndex | int | Смещение входного буфера. |
| byteCount | int | Размер входного буфера. |
| символы | ArrayPtr\<char_t\> | Буфер назначения символов. |
| charIndex | int | Смещение целевого массива. |
| charCount | int | Размер целевого массива. |
| flush | bool | Если true, очищает внутреннее состояние декодера после вычисления. |
| bytesUsed | int\& | Ссылка на переменную для хранения количества прочитанных байтов. |
| charsUsed | int\& | Ссылка на переменную для хранения количества записанных символов. |
| completed | bool\& | Ссылка на переменную, которая будет установлена в true, если входной буфер исчерпан, и в false в противном случае. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [EncodingDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method


Преобразует байты в символы.

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | const uint8_t * | Байты для декодирования. |
| byteCount | int | Размер входного буфера. |
| символы | char_t * | Буфер назначения символов. |
| charCount | int | Размер целевого массива. |
| flush | bool | Если true, очищает внутреннее состояние декодера после вычисления. |
| bytesUsed | int\& | Ссылка на переменную для хранения количества прочитанных байтов. |
| charsUsed | int\& | Ссылка на переменную для хранения количества записанных символов. |
| completed | bool\& | Ссылка на переменную, которая будет установлена в true, если входной буфер исчерпан, и в false в противном случае. |

## См. также

* Class [EncodingDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
