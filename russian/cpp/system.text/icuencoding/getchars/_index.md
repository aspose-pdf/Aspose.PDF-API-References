---
title: "Метод System::Text::ICUEncoding::GetChars"
linktitle: "GetChars"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Text::ICUEncoding::GetChars. Получает символы, полученные в результате декодирования буфера байтов в C++."
type: docs
weight: 500
url: /ru/cpp/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>) method


Получить символы, полученные в результате декодирования буфера байтов.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) для чтения байтов. |

### ReturnValue

[Buffer](../../../system/buffer/) of decoded characters.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method


Получить символы, полученные в результате декодирования буфера байтов.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) для чтения байтов. |
| byte_index | int | Смещение входного буфера. |
| byte_count | int | Размер входного буфера. |
| chars | ArrayPtr\<char_t\> | [Buffer](../../../system/buffer/) для размещения символов. |
| char_index | int | Смещение в выходном буфере. |

### ReturnValue

Количество записанных символов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int) method


Получить символы, полученные в результате декодирования буфера байтов.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) для чтения байтов. |
| индекс | int | Смещение входного буфера. |
| count | int | Размер входного буфера. |

### ReturnValue

[Buffer](../../../system/buffer/) of decoded characters.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) method


Получить символы, полученные в результате декодирования буфера байтов.

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const uint8_t * | [Buffer](../../../system/buffer/) для чтения байтов. |
| byte_count | int | Размер входного буфера. |
| chars | char_t * | [Buffer](../../../system/buffer/) для размещения символов. |
| char_count | int | Размер выходного буфера. |

### ReturnValue

Количество записанных символов.

## См. также

* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
