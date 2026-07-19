---
title: "System::Text::ICUEncoding::GetBytes метод"
linktitle: "GetBytes"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::ICUEncoding::GetBytes метод. Получить байты, которые получаются при кодировании буфера символов в C++."
type: docs
weight: 300
url: /ru/cpp/system.text/icuencoding/getbytes/
---
## ICUEncoding::GetBytes(ArrayPtr\<char_t\>) method


Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | ArrayPtr\<char_t\> | Символы для кодирования. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) method


Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | ArrayPtr\<char_t\> | Символы для кодирования. |
| char_index | int | Начало среза символов. |
| char_count | int | Количество символов для преобразования. |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) для размещения символов. |
| byte_index | int | Смещение в выходном буфере. |

### ReturnValue

Количество записанных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int) method


Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | ArrayPtr\<char_t\> | Символы для кодирования. |
| индекс | int | Начало среза символов. |
| count | int | Количество символов для преобразования. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) method


Получить байты, полученные в результате кодирования буфера символов.

```cpp
int System::Text::ICUEncoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | const char_t * | Символы для кодирования. |
| char_count | int | Количество символов для преобразования. |
| bytes | uint8_t * | [Buffer](../../../system/buffer/) для размещения символов. |
| byte_count | int | Размер выходного буфера. |

### ReturnValue

Количество записанных байтов.

## См. также

* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetBytes(const String\&) method


Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const String\& | [String](../../../system/string/) для кодирования. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) method


Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const String\& | [String](../../../system/string/) для кодирования. |
| char_index | int | Начало среза символов. |
| char_count | int | Количество символов для преобразования. |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) для размещения символов. |
| byte_index | int | Смещение в выходном буфере. |

### ReturnValue

Количество записанных байтов.

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) method


Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | const System::Details::ArrayView\<char_t\>\& | Символы для кодирования. |
| индекс | int | Начало среза символов. |
| count | int | Количество символов для преобразования. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) method


Получить байты, полученные в результате кодирования буфера символов.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | const System::Details::StackArray\<char_t, N\>\& | Символы для кодирования. |
| индекс | int | Начало среза символов. |
| count | int | Количество символов для преобразования. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) method


Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | System::Details::ArrayView\<char_t\> | Символы для кодирования. |
| char_index | int | Начало среза символов. |
| char_count | int | Количество символов для преобразования. |
| bytes | System::Details::ArrayView\<uint8_t\> | [Buffer](../../../system/buffer/) для размещения символов. |
| byte_index | int | Смещение в выходном буфере. |

### ReturnValue

Количество записанных байтов.

## См. также

* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) method


Получить байты, полученные в результате кодирования буфера символов.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | System::Details::StackArray\<char_t, SC\>\& | Символы для кодирования. |
| char_index | int | Начало среза символов. |
| char_count | int | Количество символов для преобразования. |
| bytes | System::Details::StackArray\<uint8_t, SB\>\& | [Buffer](../../../system/buffer/) для размещения символов. |
| byte_index | int | Смещение в выходном буфере. |

### ReturnValue

Количество записанных байтов.

## См. также

* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
