---
title: "System::Text::UTF7Encoding::GetChars метод"
linktitle: "GetChars"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::UTF7Encoding::GetChars метод. Получить символы, полученные в результате декодирования буфера байтов в C++."
type: docs
weight: 700
url: /ru/cpp/system.text/utf7encoding/getchars/
---
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>) method


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
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method


Получить символы, полученные в результате декодирования буфера байтов.

```cpp
int System::Text::UTF7Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index) override
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
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) method


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
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) method


Получить символы, полученные в результате декодирования буфера байтов.

```cpp
int System::Text::UTF7Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
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

* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
