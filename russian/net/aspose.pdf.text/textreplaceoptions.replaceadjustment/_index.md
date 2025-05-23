---
title: Enum TextReplaceOptions.ReplaceAdjustment
second_title: Aspose.PDF for .NET API Reference
description: Enum TextReplaceOptions.ReplaceAdjustment Aspose.Pdf.Text. Определяет действие, которое будет выполнено после замены текстового фрагмента на более короткий. None - без действия, замененный текст может перекрывать остальную часть строки; AdjustSpaceWidth - пытается отрегулировать пробелы между словами, чтобы сохранить длину строки; WholeWordsHyphenation - пытается распределить слова между строками абзаца, чтобы сохранить правильное поле абзаца; ShiftRestOfLine - сдвигает остальную часть строки в соответствии с изменяющейся длиной текста, длина строки может изменяться; Значение по умолчанию - ShiftRestOfLine.
type: docs
weight: 11020
url: /ru/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## Перечисление TextReplaceOptions.ReplaceAdjustment

Определяет действие, которое будет выполнено после замены текстового фрагмента на более короткий. None - без действия, замененный текст может перекрывать остальную часть строки; AdjustSpaceWidth - пытается отрегулировать пробелы между словами, чтобы сохранить длину строки; WholeWordsHyphenation - пытается распределить слова между строками абзаца, чтобы сохранить правильное поле абзаца; ShiftRestOfLine - сдвигает остальную часть строки в соответствии с изменяющейся длиной текста, длина строки может изменяться; Значение по умолчанию - ShiftRestOfLine.

```csharp
[Flags]
public enum ReplaceAdjustment
```

### Значения

| Название | Значение | Описание |
| --- | --- | --- |
| None | `0` | Без действия, замененный текст может перекрывать остальную часть строки |
| AdjustSpaceWidth | `1` | Пытается отрегулировать пробелы между словами, чтобы сохранить длину строки |
| WholeWordsHyphenation | `2` | Пытается распределить слова между строками абзаца, чтобы сохранить правильное поле абзаца |
| IsFormFillingMode | `4` | Пытается распределить слова в доступном белом пространстве, используя ширину абзаца. Если текст выходит за пределы, он будет скрыт. |
| ShiftRestOfLine | `8` | (По умолчанию) Сдвигает остальную часть строки в соответствии с изменяющейся длиной текста, длина строки может изменяться |

### См. также

* класс [TextReplaceOptions](../textreplaceoptions/)
* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)