---
title: "Aspose::Pdf::Text::TextReplaceOptions class"
linktitle: "TextReplaceOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::TextReplaceOptions class. Представляет параметры замены текста в C++."
type: docs
weight: 4900
url: /ru/cpp/aspose.pdf.text/textreplaceoptions/
---
## TextReplaceOptions class


Представляет параметры замены текста.

```cpp
class TextReplaceOptions : public Aspose::Pdf::Text::TextOptions
```

## Enums

| Перечисление | Описание |
| --- | --- |
| [FontSizeAdjustment](./fontsizeadjustment/) | Указывает политику того, как размер шрифта текста должен корректироваться, чтобы вписаться в ограничивающую область. |
| [ReplaceAdjustment](./replaceadjustment/) | Определяет действие, которое будет выполнено после замены фрагмента текста на более короткий. None — без действия, заменённый текст может перекрывать остальную часть строки; AdjustSpaceWidth — пытается скорректировать пробелы между словами, чтобы сохранить длину строки; WholeWordsHyphenation — пытается распределить слова между строками абзаца, чтобы сохранить правое поле абзаца; ShiftRestOfLine — смещает остальную часть строки в соответствии с изменением длины текста, длина строки может измениться; Значение по умолчанию — ShiftRestOfLine. |
| [Scope](./scope/) | [Scope](./scope/) где применяется операция замены текста, по умолчанию REPLACE_FIRST. Этот устаревший параметр сохранён для совместимости. Он влияет на PdfContentEditor и не оказывает влияния на [TextFragmentAbsorber](../textfragmentabsorber/). |
## Методы

| Метод | Описание |
| --- | --- |
| [get_AdjustmentNewLineSpacing](./get_adjustmentnewlinespacing/)() const | Возвращает значение межстрочного интервала, которое используется, если принудительно создаётся новая строка текста при замене. Ожидаемое значение — множитель размера шрифта заменённого текста. По умолчанию 1.2. |
| [get_FontSizeAdjustmentAction](./get_fontsizeadjustmentaction/)() const | Получает политику регулирования размера шрифта, чтобы он помещался в границы, определённые [TextReplaceOptions::Rectangle](../). |
| [get_IgnoreParagraphs](./get_ignoreparagraphs/)() const | Получает значение, указывающее, следует ли игнорировать отдельные абзацы при корректировке текста на странице после замены текста. |
| [get_LeftAdjustment](./get_leftadjustment/)() const | Устанавливает или получает корректировку левого положения заменённого текста при использовании [TextReplaceOptions](./): |
| [get_Rectangle](./get_rectangle/)() const | Получает прямоугольник, в который помещается текст после замены. |
| [get_ReplaceAdjustmentAction](./get_replaceadjustmentaction/)() const | Получает действие, которое будет выполнено после сокращения фрагмента текста. |
| [get_ReplaceScope](./get_replacescope/)() const | Получает область, в которой применяется операция замены текста. |
| [get_RightAdjustment](./get_rightadjustment/)() const | Устанавливает или получает корректировку правого положения заменённого текста при использовании [TextReplaceOptions](./): |
| [set_AdjustmentNewLineSpacing](./set_adjustmentnewlinespacing/)(double) | Устанавливает значение межстрочного интервала, используемого, если корректировка замены принудительно создаёт новую строку текста. Ожидаемое значение — множитель размера шрифта заменённого текста. По умолчанию 1,2. |
| [set_FontSizeAdjustmentAction](./set_fontsizeadjustmentaction/)(TextReplaceOptions::FontSizeAdjustment) | Устанавливает политику регулирования размера шрифта, чтобы он помещался в границы, определённые [TextReplaceOptions::Rectangle](../). |
| [set_IgnoreParagraphs](./set_ignoreparagraphs/)(bool) | Устанавливает значение, указывающее, следует ли игнорировать отдельные абзацы при корректировке текста на странице после замены текста. |
| [set_LeftAdjustment](./set_leftadjustment/)(double) | Устанавливает или получает корректировку левого положения заменённого текста при использовании [TextReplaceOptions](./): |
| [set_Rectangle](./set_rectangle/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Устанавливает прямоугольник, в который помещается текст после замены. |
| [set_ReplaceAdjustmentAction](./set_replaceadjustmentaction/)(TextReplaceOptions::ReplaceAdjustment) | Устанавливает действие, которое будет выполнено после сокращения фрагмента текста. |
| [set_ReplaceScope](./set_replacescope/)(TextReplaceOptions::Scope) | Устанавливает область, в которой применяется операция замены текста. |
| [set_RightAdjustment](./set_rightadjustment/)(double) | Устанавливает или получает корректировку правого положения заменённого текста при использовании [TextReplaceOptions](./): |
| [TextReplaceOptions](./textreplaceoptions/)(TextReplaceOptions::Scope) | Инициализирует новый экземпляр объекта [TextReplaceOptions](./) для указанной области. |
| [TextReplaceOptions](./textreplaceoptions/)(TextReplaceOptions::ReplaceAdjustment) | Инициализирует новый экземпляр объекта [TextReplaceOptions](./) для указанного действия после замены. |
## См. также

* Class [TextOptions](../textoptions/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
