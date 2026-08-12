---
title: "System::Char::IsHighSurrogate метод"
linktitle: "IsHighSurrogate"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Char::IsHighSurrogate метод. Определяет, является ли указанный символ высоким суррогатом в C++."
type: docs
weight: 800
url: /ru/cpp/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(char_t) method


Определяет, является ли указанный символ старшим суррогатом.

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| c | char_t | Символ для проверки |

### ReturnValue

True, если указанный символ является высоким суррогатом, иначе - false

## См. также

* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Char::IsHighSurrogate(const char_t *, int) method


Определяет, является ли символ в указанном индексе заданного буфера символов старшим суррогатом.

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const char_t * | Указатель на начало буфера символов |
| idx | int | Нулевой индекс в указанном буфере символа для проверки |

### ReturnValue

True, если символ по указанному индексу является высоким суррогатом, иначе - false

## См. также

* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Char::IsHighSurrogate(const String\&, int) method


Определяет, является ли символ в указанном индексе заданной строки старшим суррогатом UTF-16.

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const String\& | Строка |
| индекс | int | Индекс в указанной строке символа для проверки |

### ReturnValue

True, если символ по указанному индексу является кодовой единицей UTF-16 высокого суррогата, иначе - false

## См. также

* Class [String](../../string/)
* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
