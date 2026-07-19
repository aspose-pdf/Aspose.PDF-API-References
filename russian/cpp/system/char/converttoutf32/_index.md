---
title: "System::Char::ConvertToUtf32 method"
linktitle: "ConvertToUtf32"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Char::ConvertToUtf32 method. Преобразует указанную пару суррогатов UTF-16 в кодовую единицу UTF-32 в C++."
type: docs
weight: 200
url: /ru/cpp/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) method


Преобразует указанную пару суррогатов UTF-16 в кодовую единицу UTF-32.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| highSurrogate | char_t | Старший суррогат пары суррогатов UTF-16 для преобразования |
| lowSurrogate | char_t | Младший суррогат пары суррогатов UTF-16 для преобразования |

### ReturnValue

Кодовая единица UTF-32, полученная в результате преобразования

## См. также

* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Char::ConvertToUtf32(const String\&, int) method


Преобразует значение символа, закодированного в UTF-16, или пары суррогатов в указанной позиции строки в кодовую единицу UTF-32.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const String\& | Строка, содержащая символ или пару суррогатов |
| индекс | int | Позиция индекса символа или пары суррогатов в указанной строке |

### ReturnValue

Кодовая единица UTF-32, полученная в результате преобразования

## См. также

* Class [String](../../string/)
* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
