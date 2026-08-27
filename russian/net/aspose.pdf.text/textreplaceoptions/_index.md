---
title: "Класс TextReplaceOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Text.TextReplaceOptions. Представляет параметры замены текста"
type: docs
weight: 11190
url: /ru/net/aspose.pdf.text/textreplaceoptions/
---
## TextReplaceOptions class

Представляет параметры замены текста

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | Инициализирует новый экземпляр объекта `TextReplaceOptions` для указанного действия после замены. |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | Инициализирует новый экземпляр объекта `TextReplaceOptions` для указанного диапазона. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | Получает или задает значение межстрочного интервала, используемого, если корректировка замены принудительно создает новую строку текста. Ожидаемое значение — множитель размера шрифта заменяемого текста. По умолчанию 1,2. |
| [FontSizeAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/fontsizeadjustmentaction/) { get; set; } | Получает или задает политику корректировки размера шрифта, чтобы он помещался в границы, определённые элементом [`Rectangle`](./rectangle/). |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | Получает или задает значение, указывающее, следует ли игнорировать отдельные абзацы при корректировке текста на странице после замены текста. |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | Устанавливает или получает корректировку левого положения заменённого текста при использовании TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [Rectangle](../../aspose.pdf.text/textreplaceoptions/rectangle/) { get; set; } | Получает или задает прямоугольник, в который будет помещён текст после замены. |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | Получает или задает действие, которое будет выполнено после замены фрагмента текста на более короткий. |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | Получает или задает область, в которой применяется операция замены текста |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | Устанавливает или получает корректировку правого положения заменённого текста при использовании TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### См. также

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


