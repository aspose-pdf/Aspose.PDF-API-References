---
title: Class TextReplaceOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Text.TextReplaceOptions. Представляет параметры замены текста
type: docs
weight: 11010
url: /ru/net/aspose.pdf.text/textreplaceoptions/
---
## Класс TextReplaceOptions

Представляет параметры замены текста

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | Инициализирует новый экземпляр объекта `TextReplaceOptions` для указанного действия после замены. |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | Инициализирует новый экземпляр объекта `TextReplaceOptions` для указанной области. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | Получает или задает значение межстрочного интервала, которое используется, если корректировка замены вынуждена создать новую строку текста. Ожидаемое значение - множитель размера шрифта заменяемого текста. По умолчанию 1.2. |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | Получает или задает значение, указывающее, следует ли игнорировать отдельные абзацы при корректировке текста на странице после замены текста. |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | Устанавливает или получает левую позицию корректировки для замененного текста при использовании TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | Получает или задает действие, которое будет выполнено после замены фрагмента текста на более короткий. |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | Получает или задает область, в которой применяется операция замены текста |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | Устанавливает или получает правую позицию корректировки для замененного текста при использовании TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### См. также

* класс [TextOptions](../textoptions/)
* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)