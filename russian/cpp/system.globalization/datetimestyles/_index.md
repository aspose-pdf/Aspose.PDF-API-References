---
title: "Перечисление System::Globalization::DateTimeStyles"
linktitle: "DateTimeStyles"
second_title: "Справочник API Aspose.PDF для C++"
description: "Перечисление System::Globalization::DateTimeStyles. Определяет параметры форматирования даты и времени. Битовые флаги в C++."
type: docs
weight: 3500
url: /ru/cpp/system.globalization/datetimestyles/
---
## DateTimeStyles enum


Определяет параметры форматирования даты и времени. Битовые флаги.

```cpp
enum class DateTimeStyles : int32_t
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 | По умолчанию. |
| AllowLeadingWhite | 1 | Игнорировать начальные пробелы. |
| AllowTrailingWhite | 2 | Игнорировать конечные пробелы. |
| AllowInnerWhite | 4 | Игнорировать внутренние пробелы. |
| AllowWhiteSpaces | n/a | Игнорировать все пробелы. |
| NoCurrentDateDefault | 8 | При разборе строки даты/времени, если отсутствуют все значения года, месяца и дня, установить дату по умолчанию 0001/1/1, вместо текущего года, месяца и дня. |
| AdjustToUniversal | 16 | При разборе строки даты/времени, если указатель часового пояса ("GMT","Z","+xxxx", "-xxxx" существует), мы будем ajdust разобранное время относительно GMT. |
| AssumeLocal | 32 | Если часовой пояс не указан, используйте локальный часовой пояс. |
| AssumeUniversal | 64 | Если часовой пояс не указан, используйте UTC. |
| RoundtripKind | 128 | Попытка сохранить, является ли входное значение неопределённым, локальным или UTC. |

## См. также

* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
