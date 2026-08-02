---
title: "Перечисление TextEditOptions.NoCharacterAction"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Перечисление Aspose.Pdf.Text.TextEditOptionsNoCharacterAction. Действие, которое следует выполнить, если шрифт не содержит требуемый символ."
type: docs
weight: 11040
url: /ru/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## TextEditOptions.NoCharacterAction enumeration

Действие, которое следует выполнить, если шрифт не содержит требуемый символ

```csharp
public enum NoCharacterAction
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| ThrowException | `0` | Выбросить исключение |
| UseStandardFont | `1` | Заменить шрифт на стандартный шрифт, который содержит требуемый символ |
| ReplaceAnyway | `2` | Все равно заменить текст без замены шрифта |
| ReplaceFonts | `3` | Заменяет шрифты при необходимости, чтобы обеспечить отображение всех символов текста. Алгоритм подстановки шрифтов выполняет следующие шаги: 1. Если пользователь явно задаёт свойство Font, проверяется, может ли указанный шрифт отображать требуемые символы. 2. Если пользовательский шрифт не задан, производится поиск шрифтов, добавленных через [`Sources`](../fontrepository/sources/). 3. Анализируется текст для определения его алфавита или письменности и предлагаются соответствующие названия шрифтов. Пытаются найти и использовать эти шрифты в системе. 4. При необходимости выполняется поиск в системе любого шрифта, способного отображать требуемые символы. |
| UseCustomReplacementFont | `4` | Заменить шрифт на определённый заменяющий шрифт |

### См. также

* class [TextEditOptions](../texteditoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


