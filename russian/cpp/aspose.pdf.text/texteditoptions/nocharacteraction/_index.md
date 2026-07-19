---
title: "Aspose::Pdf::Text::TextEditOptions::NoCharacterAction enum"
linktitle: "NoCharacterAction"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::TextEditOptions::NoCharacterAction enum. Действие, которое следует выполнить, если шрифт не содержит требуемый символ в C++."
type: docs
weight: 1900
url: /ru/cpp/aspose.pdf.text/texteditoptions/nocharacteraction/
---
## NoCharacterAction enum


Действие, которое следует выполнить, если шрифт не содержит требуемый символ.

```cpp
enum class NoCharacterAction
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| ThrowException | 0 | Выбросить исключение. |
| UseStandardFont | 1 | Заменить шрифт на стандартный шрифт, содержащий требуемый символ. |
| ReplaceAnyway | 2 | Заменить текст в любом случае без замены шрифта. |
| ReplaceFonts | 3 | Заменяет шрифты по мере необходимости, чтобы обеспечить отображение всех символов в тексте. Алгоритм подстановки шрифтов следует этим шагам: |
| UseCustomReplacementFont | 4 | Заменить шрифт на определённый заменяющий шрифт. |

## См. также

* Class [TextEditOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
