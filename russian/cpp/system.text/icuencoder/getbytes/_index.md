---
title: "System::Text::ICUEncoder::GetBytes метод"
linktitle: "GetBytes"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::ICUEncoder::GetBytes метод. Получить байты, полученные при кодировании буфера в C++."
type: docs
weight: 500
url: /ru/cpp/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) method


Получить байты, полученные в результате кодирования буфера.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | ArrayPtr\<char_t\> | Символы для кодирования. |
| charIndex | int | Смещение исходного массива. |
| charCount | int | Длина подмассива источника. |
| байты | ArrayPtr\<uint8_t\> | Буфер целевых байтов. |
| byteIndex | int | Смещение буфера назначения. |
| flush | bool | Если true, очищает внутреннее состояние кодировщика после вычисления. |

### ReturnValue

Количество записанных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) method


Получить байты, полученные в результате кодирования буфера.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | const char_t * | Символы для кодирования. |
| charCount | int | Длина исходного массива. |
| байты | uint8_t * | Буфер целевых байтов. |
| byteCount | int | Размер буфера назначения. |
| flush | bool | Если true, очищает внутреннее состояние кодировщика после вычисления. |

### ReturnValue

Количество записанных байтов.

## См. также

* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
