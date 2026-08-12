---
title: "System::Text::UTF7Encoding::GetByteCount метод"
linktitle: "GetByteCount"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::UTF7Encoding::GetByteCount метод. Получить количество символов, необходимое для кодирования буфера символов в C++."
type: docs
weight: 400
url: /ru/cpp/system.text/utf7encoding/getbytecount/
---
## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>) method


Получить количество символов, необходимое для кодирования буфера символов.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | ArrayPtr\<char_t\> | Буфер символов. |

### ReturnValue

Требуемый размер буфера.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) method


Получить количество символов, необходимое для кодирования буфера символов.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | ArrayPtr\<char_t\> | Буфер символов. |
| индекс | int | Начало среза. |
| count | int | Размер среза. |

### ReturnValue

Требуемый размер буфера.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetByteCount(const char_t *, int) method


Получить количество символов, необходимое для кодирования буфера символов.

```cpp
int System::Text::UTF7Encoding::GetByteCount(const char_t *chars, int count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | const char_t * | Буфер символов. |
| count | int | [Buffer](../../../system/buffer/) размер. |

### ReturnValue

Требуемый размер буфера.

## См. также

* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetByteCount(const String\&) method


Получает количество символов, необходимых для кодирования строки.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const String\& | [String](../../../system/string/) для кодирования. |

### ReturnValue

Требуемый размер буфера.

## См. также

* Class [String](../../../system/string/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) method


Получить количество символов, необходимое для кодирования буфера символов.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | const System::Details::StackArray\<char_t, N\>\& | Буфер символов. |
| индекс | int | Начало среза. |
| count | int | Размер среза. |

### ReturnValue

Требуемый размер буфера.

## См. также

* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) method


Получить количество символов, необходимое для кодирования буфера символов.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | System::Details::ArrayView\<char_t\> | Буфер символов. |
| индекс | int | Начало среза. |
| count | int | Размер среза. |

### ReturnValue

Требуемый размер буфера.

## См. также

* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
