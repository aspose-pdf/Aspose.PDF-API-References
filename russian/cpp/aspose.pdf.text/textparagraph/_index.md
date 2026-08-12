---
title: "Aspose::Pdf::Text::TextParagraph класс"
linktitle: "TextParagraph"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::TextParagraph класс. Представляет текстовые абзацы как многострочный текстовый объект в C++."
type: docs
weight: 4800
url: /ru/cpp/aspose.pdf.text/textparagraph/
---
## TextParagraph class


Представляет абзацы текста как многострочный объект текста.

```cpp
class TextParagraph : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [AppendLine](./appendline/)(const System::String\&) | Добавляет строку текста. |
| [AppendLine](./appendline/)(const System::String\&, float) | Добавляет строку текста. |
| [AppendLine](./appendline/)(const System::String\&, const System::SharedPtr\<TextState\>\&) | Добавляет строку текста с параметрами состояния текста. |
| [AppendLine](./appendline/)(const System::String\&, const System::SharedPtr\<TextState\>\&, float) | Добавляет строку текста с параметрами состояния текста. |
| [AppendLine](./appendline/)(const System::SharedPtr\<TextFragment\>\&) | Добавляет строку текста с параметрами состояния текста. |
| [AppendLine](./appendline/)(const System::SharedPtr\<TextFragment\>\&, const System::SharedPtr\<TextState\>\&) | Добавляет строку текста с параметрами состояния текста. |
| [AppendLine](./appendline/)(const System::SharedPtr\<TextFragment\>\&, const System::SharedPtr\<TextState\>\&, float) | Добавляет строку текста с параметрами состояния текста. |
| [BeginEdit](./beginedit/)() | Начинает редактирование [TextParagraph](./). |
| [EndEdit](./endedit/)() | Завершает редактирование [TextParagraph](./). |
| [get_FirstLineIndent](./get_firstlineindent/)() const | Получает значение отступа последующих строк. Если установить ненулевое значение, оно имеет преимущество перед значением FormattingOptions.SubsequentLinesIndent. |
| [get_FormattingOptions](./get_formattingoptions/)() const | Получает параметры форматирования. |
| [get_HorizontalAlignment](./get_horizontalalignment/)() const | Получает горизонтальное выравнивание текста внутри [Rectangle](../../aspose.pdf/rectangle/) абзаца. |
| [get_Justify](./get_justify/)() | Получает значение, выравнивается ли текст по ширине. |
| [get_Margin](./get_margin/)() const | Получает отступ. |
| [get_Position](./get_position/)() const | Получает позицию абзаца. |
| [get_Rectangle](./get_rectangle/)() const | Получает прямоугольник абзаца. |
| [get_Rotation](./get_rotation/)() const | Получает угол вращения в градусах. |
| [get_SubsequentLinesIndent](./get_subsequentlinesindent/)() const | Получает значение отступа последующих строк. Если установить ненулевое значение, оно имеет преимущество перед значением FormattingOptions.SubsequentLinesIndent. |
| [get_TextRectangle](./get_textrectangle/)() | Получает прямоугольник текста, размещённого в абзаце. |
| [get_VerticalAlignment](./get_verticalalignment/)() const | Получает вертикальное выравнивание текста внутри [Rectangle](../../aspose.pdf/rectangle/) абзаца. |
| [set_FirstLineIndent](./set_firstlineindent/)(float) | Устанавливает значение отступа последующих строк. Если установить ненулевое значение, оно имеет преимущество перед значением FormattingOptions.SubsequentLinesIndent. |
| [set_FormattingOptions](./set_formattingoptions/)(const System::SharedPtr\<TextFormattingOptions\>\&) | Устанавливает параметры форматирования. |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Устанавливает горизонтальное выравнивание текста внутри [Rectangle](../../aspose.pdf/rectangle/) абзаца. |
| [set_Justify](./set_justify/)(bool) | Устанавливает значение, выравнивается ли текст по ширине. |
| [set_Margin](./set_margin/)(const System::SharedPtr\<MarginInfo\>\&) | Устанавливает отступ. |
| [set_Position](./set_position/)(const System::SharedPtr\<Aspose::Pdf::Text::Position\>\&) | Устанавливает позицию абзаца. |
| [set_Rectangle](./set_rectangle/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Устанавливает прямоугольник абзаца. |
| [set_Rotation](./set_rotation/)(double) | Устанавливает угол поворота в градусах. |
| [set_SubsequentLinesIndent](./set_subsequentlinesindent/)(float) | Устанавливает значение отступа последующих строк. Если установить ненулевое значение, оно имеет преимущество перед значением FormattingOptions.SubsequentLinesIndent. |
| [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Устанавливает вертикальное выравнивание текста внутри [Rectangle](../../aspose.pdf/rectangle/) абзаца. |
| [TextParagraph](./textparagraph/)() | Создаёт объект [TextParagraph](./). |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
