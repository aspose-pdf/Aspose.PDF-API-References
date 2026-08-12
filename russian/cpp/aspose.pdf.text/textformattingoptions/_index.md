---
title: "Aspose::Pdf::Text::TextFormattingOptions класс"
linktitle: "TextFormattingOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::TextFormattingOptions класс. Представляет параметры форматирования текста в C++."
type: docs
weight: 4200
url: /ru/cpp/aspose.pdf.text/textformattingoptions/
---
## TextFormattingOptions class


Представляет параметры форматирования текста.

```cpp
class TextFormattingOptions : public Aspose::Pdf::Text::TextOptions
```

## Enums

| Перечисление | Описание |
| --- | --- |
| [LineSpacingMode](./linespacingmode/) | Определяет особенности межстрочного интервала. |
| [WordWrapMode](./wordwrapmode/) | Определяет стратегии переноса слов. |
## Методы

| Метод | Описание |
| --- | --- |
| [get_FirstLineIndent](./get_firstlineindent/)() const | Получает значение отступа первой строки. |
| [get_HyphenSymbol](./get_hyphensymbol/)() const | Получает символ дефиса, используемый в процессе переноса слов. |
| [get_LineSpacing](./get_linespacing/)() const | Получает режим межстрочного интервала. Значение по умолчанию — [LineSpacingMode.FontSize](./linespacingmode/). |
| [get_SubsequentLinesIndent](./get_subsequentlinesindent/)() const | Получает значение отступа последующих строк. |
| [get_WrapMode](./get_wrapmode/)() const | Получает режим переноса слов. Значение по умолчанию — [WordWrapMode.NoWrap](./wordwrapmode/). |
| [set_FirstLineIndent](./set_firstlineindent/)(float) | Устанавливает значение отступа первой строки. |
| [set_HyphenSymbol](./set_hyphensymbol/)(const System::String\&) | Устанавливает символ дефиса, используемый в процессе переноса слов. |
| [set_LineSpacing](./set_linespacing/)(TextFormattingOptions::LineSpacingMode) | Устанавливает режим межстрочного интервала. Значение по умолчанию — [LineSpacingMode.FontSize](./linespacingmode/). |
| [set_SubsequentLinesIndent](./set_subsequentlinesindent/)(float) | Устанавливает значение отступа последующих строк. |
| [set_WrapMode](./set_wrapmode/)(TextFormattingOptions::WordWrapMode) | Устанавливает режим переноса слов. Значение по умолчанию — [WordWrapMode.NoWrap](./wordwrapmode/). |
| [TextFormattingOptions](./textformattingoptions/)(TextFormattingOptions::WordWrapMode) | Создаёт новый экземпляр объекта [TextFormattingOptions](./) для указанного режима переноса слов. |
| [TextFormattingOptions](./textformattingoptions/)() | Создаёт новый экземпляр объекта [TextFormattingOptions](./) с неопределённым режимом переноса слов. |
## См. также

* Class [TextOptions](../textoptions/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
