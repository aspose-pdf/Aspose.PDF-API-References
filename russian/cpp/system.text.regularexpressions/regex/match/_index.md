---
title: "Метод System::Text::RegularExpressions::Regex::Match"
linktitle: "Match"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Text::RegularExpressions::Regex::Match. Сопоставляет регулярное выражение со строкой в C++."
type: docs
weight: 600
url: /ru/cpp/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) method


Сравнивает регулярное выражение со строкой.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Целевая строка. |

### ReturnValue

[Match](../../match/) value containing match status and submatches.

## См. также

* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Match(const String\&, int, int) method


Сравнивает регулярное выражение со строкой.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Целевая строка. |
| startat | int | Начальный индекс. |
| длина | int | Количество символов для просмотра (0 — просмотреть всю строку). |

### ReturnValue

[Match](../../match/) value containing match status and submatches.

## См. также

* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) method


Сравнивает строку и шаблон.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const String\& | Входная строка. |
| шаблон | const String\& | Шаблон Regexp. |
| опции | RegexOptions | Параметры сопоставления. |
| matchTimeout | TimeSpan | Тайм-аут. |
| startat | int | [Match](../../match/) начальная позиция. |
| длина | int | Количество символов для просмотра (0 отключает ограничение). |

### ReturnValue

Первое найденное совпадение.

## См. также

* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
