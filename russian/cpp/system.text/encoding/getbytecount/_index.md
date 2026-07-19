---
title: "Метод System::Text::Encoding::GetByteCount"
linktitle: "GetByteCount"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Text::Encoding::GetByteCount. Получает количество символов, необходимое для кодирования буфера символов, в C++."
type: docs
weight: 1700
url: /ru/cpp/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>) method


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
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) method


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
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetByteCount(const char_t *, int) method


Получить количество символов, необходимое для кодирования буфера символов.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | const char_t * | Буфер символов. |
| count | int | [Buffer](../../../system/buffer/) размер. |

### ReturnValue

Требуемый размер буфера.

## См. также

* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetByteCount(const String\&) method


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
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) method


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

* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) method


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

* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
