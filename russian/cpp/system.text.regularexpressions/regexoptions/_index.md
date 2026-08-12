---
title: "System::Text::RegularExpressions::RegexOptions перечисление"
linktitle: "RegexOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::RegularExpressions::RegexOptions перечисление. Параметры регулярных выражений в C++."
type: docs
weight: 900
url: /ru/cpp/system.text.regularexpressions/regexoptions/
---
## RegexOptions enum


[Regex](../regex/) options.

```cpp
enum class RegexOptions
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 | Поведение по умолчанию. |
| Compiled | 1 | Компилировать регулярное выражение для повышения производительности. Всегда выполняется по умолчанию. |
| CultureInvariant | 2 | Использовать сопоставление, независимое от культуры. Игнорируется. |
| ECMAScript | 4 | Использовать синтаксис ECMAScript. Игнорируется. |
| ExplicitCapture | 8 | Только явное захватывание. Игнорируется. |
| IgnoreCase | 16 | Игнорировать регистр при сопоставлении. |
| IgnorePatternWhitespace | 32 | Игнорировать пробелы в шаблоне. Не поддерживается. |
| Multiline | 64 | Рассматривать '^' и '$' как начало и конец строки, а не всей строки. |
| RightToLeft | 128 | Сопоставление справа налево. Не поддерживается. |
| Singleline | 256 | Заставляет '.' соответствовать любому символу без исключений (обычно символы новой строки не совпадают). |

## См. также

* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
