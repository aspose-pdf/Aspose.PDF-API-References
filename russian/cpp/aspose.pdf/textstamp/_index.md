---
title: "Aspose::Pdf::TextStamp class"
linktitle: "TextStamp"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::TextStamp. Представляет текстовую печать в C++."
type: docs
weight: 18400
url: /ru/cpp/aspose.pdf/textstamp/
---
## TextStamp class


Представляет текстовый штамп.

```cpp
class TextStamp : public Aspose::Pdf::Stamp
```

## Enums

| Перечисление | Описание |
| --- | --- |
| [NoCharacterAction](./nocharacteraction/) | Действие, которое следует выполнить, если шрифт не содержит требуемый символ. |
## Методы

| Метод | Описание |
| --- | --- |
| [get_AutoAdjustFontSizePrecision](./get_autoadjustfontsizeprecision/)() const | Автоматически корректировать точность размера шрифта. Значение по умолчанию: 0.1;. |
| [get_AutoAdjustFontSizeToFitStampRectangle](./get_autoadjustfontsizetofitstamprectangle/)() const | Если включено, размер шрифта будет автоматически скорректирован, чтобы вписаться в прямоугольник печати размером: [Width](../) и [Height](../). Ширина и высота по умолчанию берутся из прямоугольника страницы. |
| [get_Draw](./get_draw/)() const | Это свойство определяет, как печать отображается на странице. Если Draw = true, печать рисуется как графические операторы, а если draw = false, то печать отображается как текст. |
| [get_FontSize](./get_fontsize/)() | Фактический размер шрифта после размещения печати. (Может отличаться от исходного размера шрифта, указанного в конструкторе, если включена опция 'AutoAdjustFontSizeToFitStampRectangle'.) |
| [get_Height](./get_height/)() override | Желаемая высота штампа на странице. |
| [get_Justify](./get_justify/)() | Определяет выравнивание текста. Если это свойство установлено в true, обе границы текста (левая и правая) выравниваются. Значение по умолчанию: false. |
| [get_MaxRowWidth](./get_maxrowwidth/)() const | Максимальная высота строки для опции WordWrap. |
| [get_NoCharacterBehavior](./get_nocharacterbehavior/)() const | Получает режим, определяющий поведение в случае, если шрифты не содержат требуемые символы. |
| [get_ReplacementFont](./get_replacementfont/)() const | Получает шрифт, используемый для замены, если пользовательский шрифт не содержит требуемый символ. |
| [get_Scale](./get_scale/)() const | Определяет масштабирование текста. Если это свойство установлено в true и указано значение Width, текст будет масштабироваться, чтобы соответствовать указанной ширине. |
| [get_TextAlignment](./get_textalignment/)() const | Выравнивание текста внутри печати. |
| [get_TextState](./get_textstate/)() const | Получает свойства текста печати. См. **TextState** для подробностей. |
| [get_TreatYIndentAsBaseLine](./get_treatyindentasbaseline/)() const | Определяет начало координат для размещения текста. Если TreatYIndentAsBaseLine = true (по умолчанию, когда Draw = true), значение YIndent будет рассматриваться как базовая линия текста. Если TreatYIndentAsBaseLine = false (по умолчанию, когда Draw = false), значение YIndent будет рассматриваться как нижняя (линия спуска) текста. |
| [get_Value](./get_value/)() | Получает строковое значение, используемое в качестве печати на странице. |
| [get_Width](./get_width/)() override | Желаемая ширина штампа на странице. |
| [get_WordWrap](./get_wordwrap/)() const | Определяет перенос слов. Если это свойство установлено в true и указано значение Width, текст будет разбит на несколько строк, чтобы вписаться в указанную ширину. Значение по умолчанию: false. |
| [get_WordWrapMode](./get_wordwrapmode/)() const | Получает режим переноса слов для отображения текста. |
| [Put](./put/)(System::SharedPtr\<Page\>) override | Добавляет текстовую печать на страницу. |
| [set_AutoAdjustFontSizePrecision](./set_autoadjustfontsizeprecision/)(float) | Автоматически корректировать точность размера шрифта. Значение по умолчанию: 0.1;. |
| [set_AutoAdjustFontSizeToFitStampRectangle](./set_autoadjustfontsizetofitstamprectangle/)(bool) | Если включено, размер шрифта будет автоматически скорректирован, чтобы вписаться в прямоугольник печати размером: [Width](../) и [Height](../). Ширина и высота по умолчанию берутся из прямоугольника страницы. |
| [set_Draw](./set_draw/)(bool) | Это свойство определяет, как печать отображается на странице. Если Draw = true, печать рисуется как графические операторы, а если draw = false, то печать отображается как текст. |
| [set_Height](./set_height/)(double) override | Желаемая высота штампа на странице. |
| [set_Justify](./set_justify/)(bool) | Определяет выравнивание текста. Если это свойство установлено в true, обе границы текста (левая и правая) выравниваются. Значение по умолчанию: false. |
| [set_MaxRowWidth](./set_maxrowwidth/)(double) | Максимальная высота строки для опции WordWrap. |
| [set_NoCharacterBehavior](./set_nocharacterbehavior/)(TextStamp::NoCharacterAction) | Устанавливает режим, определяющий поведение в случае, если шрифты не содержат запрашиваемые символы. |
| [set_ReplacementFont](./set_replacementfont/)(const System::SharedPtr\<Text::Font\>\&) | Устанавливает шрифт, используемый для замены, если пользовательский шрифт не содержит требуемый символ. |
| [set_Scale](./set_scale/)(bool) | Определяет масштабирование текста. Если это свойство установлено в true и указано значение Width, текст будет масштабироваться, чтобы соответствовать указанной ширине. |
| [set_TextAlignment](./set_textalignment/)(Aspose::Pdf::HorizontalAlignment) | Выравнивание текста внутри печати. |
| [set_TreatYIndentAsBaseLine](./set_treatyindentasbaseline/)(bool) | Определяет начало координат для размещения текста. Если TreatYIndentAsBaseLine = true (по умолчанию, когда Draw = true), значение YIndent будет рассматриваться как базовая линия текста. Если TreatYIndentAsBaseLine = false (по умолчанию, когда Draw = false), значение YIndent будет рассматриваться как нижняя (линия спуска) текста. |
| [set_Value](./set_value/)(const System::String\&) | Устанавливает строковое значение, используемое в качестве печати на странице. |
| [set_Width](./set_width/)(double) override | Желаемая ширина штампа на странице. |
| [set_WordWrap](./set_wordwrap/)(bool) | Определяет перенос слов. Если это свойство установлено в true и указано значение Width, текст будет разбит на несколько строк, чтобы вписаться в указанную ширину. Значение по умолчанию: false. |
| [set_WordWrapMode](./set_wordwrapmode/)(Aspose::Pdf::Text::TextFormattingOptions::WordWrapMode) | Устанавливает режим переноса слов для отображения текста. |
| [TextStamp](./textstamp/)(const System::String\&) | Инициализирует новый экземпляр класса [TextStamp](./). |
| [TextStamp](./textstamp/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextState\>\&) | Инициализирует новый экземпляр класса [TextStamp](./). |
| [TextStamp](./textstamp/)(const System::SharedPtr\<Facades::FormattedText\>\&) | Инициализирует новый экземпляр класса [TextStamp](./) с объектом formattedText. |
## См. также

* Class [Stamp](../stamp/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
