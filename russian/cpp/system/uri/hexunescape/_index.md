---
title: "System::Uri::HexUnescape метод"
linktitle: "HexUnescape"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Uri::HexUnescape метод. Преобразует указанное шестнадцатеричное представление символа в символ в C++."
type: docs
weight: 4000
url: /ru/cpp/system/uri/hexunescape/
---
## Uri::HexUnescape method


Преобразует указанное шестнадцатеричное представление символа в символ.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| шаблон | const String\& | Строка, содержащая шестнадцатеричное представление символа |
| индекс | int32_t\& | Позиция в **pattern**, где начинается шестнадцатеричное представление символа |

### ReturnValue

Символ, представленный шестнадцатеричным кодированием в позиции **index**. Если символ в **index** не закодирован в шестнадцатеричном виде, возвращается символ в **index**. Значение **index** увеличивается, указывая на символ, следующий за возвращённым.

## См. также

* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
