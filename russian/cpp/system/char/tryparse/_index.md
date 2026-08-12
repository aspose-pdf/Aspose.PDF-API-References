---
title: "System::Char::TryParse метод"
linktitle: "TryParse"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Char::TryParse метод. Пытается преобразовать строку, состоящую из одного символа, в символ UTF-16. Функция успешно завершается только тогда, когда входная строка не равна null и имеет длину ровно один символ в C++."
type: docs
weight: 2600
url: /ru/cpp/system/char/tryparse/
---
## Char::TryParse method


Пытается преобразовать строку, состоящую из одного символа, в символ UTF-16. Функция завершается успешно только когда входная строка не равна null и имеет длину ровно один символ.

```cpp
static bool System::Char::TryParse(const System::String &s, char_t &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const System::String\& | [String](../../string/) для преобразования |
| result | char_t\& | Выходная переменная, которая будет содержать результат преобразования, если преобразование успешно |

### ReturnValue

Истина, если преобразование успешно, иначе — false

## См. также

* Class [String](../../string/)
* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
