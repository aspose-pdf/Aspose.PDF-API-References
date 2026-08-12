---
title: "Aspose::Pdf::Text::TextState класс"
linktitle: "TextState"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::TextState класс. Представляет состояние текста в C++."
type: docs
weight: 5300
url: /ru/cpp/aspose.pdf.text/textstate/
---
## TextState class


Представляет состояние текста.

```cpp
class TextState : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [ApplyChangesFrom](./applychangesfrom/)(const System::SharedPtr\<TextState\>\&) | Применяет настройки из другого textState. |
| virtual [get_BackgroundColor](./get_backgroundcolor/)() | Устанавливает цвет фона текста. |
| virtual [get_CharacterSpacing](./get_characterspacing/)() | Получает межсимвольный интервал текста. |
| virtual [get_CoordinateOrigin](./get_coordinateorigin/)() | Получает текст [CoordinateOrigin](../coordinateorigin/). Если [CoordinateOrigin](../coordinateorigin/) имеет значение Descender, координата Y текста соответствует самой нижней точке шрифта. Если [CoordinateOrigin](../coordinateorigin/) имеет значение BaseLine, координата Y текста соответствует базовой линии шрифта. Значение по умолчанию — Descender. Если значение Descent шрифта слишком велико, текст может отображаться выше, чем другие шрифты. В этом случае можно выбрать [CoordinateOrigin](../coordinateorigin/) BaseLine для лучшего отображения текста. |
| virtual [get_Font](./get_font/)() | Получает шрифт текста. |
| virtual [get_FontSize](./get_fontsize/)() | Получает размер шрифта текста. |
| virtual [get_FontStyle](./get_fontstyle/)() | Устанавливает стиль шрифта текста. |
| virtual [get_ForegroundColor](./get_foregroundcolor/)() | Получает цвет переднего плана текста. |
| virtual [get_HorizontalAlignment](./get_horizontalalignment/)() | Получает горизонтальное выравнивание текста. |
| virtual [get_HorizontalScaling](./get_horizontalscaling/)() | Получает горизонтальное масштабирование текста. |
| virtual [get_Invisible](./get_invisible/)() | Получает невидимость текста. Это в основном отражает состояние [RenderingMode](../), за исключением некоторых особых случаев (например, обрезки). |
| virtual [get_LineSpacing](./get_linespacing/)() | Получает межстрочный интервал текста. |
| virtual [get_RenderingMode](./get_renderingmode/)() | Получает режим отображения текста. |
| virtual [get_StrikeOut](./get_strikeout/)() | Получает перечёркивание текста, представленного объектом [TextSegment](../textsegment/). |
| virtual [get_StrokingColor](./get_strokingcolor/)() | Получает цвет переднего плана текста. |
| virtual [get_Subscript](./get_subscript/)() | Получает нижний индекс текста. |
| virtual [get_Superscript](./get_superscript/)() | Получает верхний индекс текста. |
| [get_TabTag](./get_tabtag/)() | Вы можете разместить этот тег в тексте, чтобы объявить табуляцию. |
| virtual [get_Underline](./get_underline/)() | Получает подчеркивание текста, представленного объектом [TextFragment](../textfragment/). |
| virtual [get_WordSpacing](./get_wordspacing/)() | Получает межсловный интервал текста. |
| [MeasureHeight](./measureheight/)(char16_t) | Измеряет высоту символа. |
| virtual [MeasureString](./measurestring/)(const System::String\&) | Измеряет строку. |
| virtual [set_BackgroundColor](./set_backgroundcolor/)(System::SharedPtr\<Color\>) | Устанавливает цвет фона текста. |
| virtual [set_CharacterSpacing](./set_characterspacing/)(float) | Устанавливает межсимвольный интервал текста. |
| virtual [set_CoordinateOrigin](./set_coordinateorigin/)(Aspose::Pdf::Text::CoordinateOrigin) | Устанавливает текстовый [CoordinateOrigin](../coordinateorigin/). Если [CoordinateOrigin](../coordinateorigin/) имеет значение Descender, координата Y текста соответствует самой нижней точке шрифта. Если [CoordinateOrigin](../coordinateorigin/) имеет значение BaseLine, координата Y текста соответствует базовой линии шрифта. Значение по умолчанию — Descender. Если значение Descent шрифта слишком велико, текст может отображаться выше, чем другие шрифты. В этом случае можно выбрать [CoordinateOrigin](../coordinateorigin/) BaseLine для более корректного отображения текста. |
| virtual [set_Font](./set_font/)(System::SharedPtr\<Aspose::Pdf::Text::Font\>) | Устанавливает шрифт текста. |
| virtual [set_FontSize](./set_fontsize/)(float) | Устанавливает размер шрифта текста. |
| virtual [set_FontStyle](./set_fontstyle/)(FontStyles) | Устанавливает стиль шрифта текста. |
| virtual [set_ForegroundColor](./set_foregroundcolor/)(System::SharedPtr\<Color\>) | Устанавливает цвет переднего плана текста. |
| virtual [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Устанавливает горизонтальное выравнивание текста. |
| virtual [set_HorizontalScaling](./set_horizontalscaling/)(float) | Устанавливает горизонтальное масштабирование текста. |
| virtual [set_Invisible](./set_invisible/)(bool) | Устанавливает невидимость текста. Это в основном отражает состояние [RenderingMode](../), за исключением некоторых особых случаев (например, обрезки). |
| virtual [set_LineSpacing](./set_linespacing/)(float) | Устанавливает межстрочный интервал текста. |
| virtual [set_RenderingMode](./set_renderingmode/)(TextRenderingMode) | Устанавливает режим рендеринга текста. |
| virtual [set_StrikeOut](./set_strikeout/)(bool) | Устанавливает зачеркивание текста, представленного объектом [TextSegment](../textsegment/). |
| virtual [set_StrokingColor](./set_strokingcolor/)(System::SharedPtr\<Color\>) | Устанавливает цвет переднего плана текста. |
| virtual [set_Subscript](./set_subscript/)(bool) | Устанавливает нижний индекс текста. |
| virtual [set_Superscript](./set_superscript/)(bool) | Устанавливает верхний индекс текста. |
| virtual [set_Underline](./set_underline/)(bool) | Устанавливает подчеркивание текста, представленного объектом [TextFragment](../textfragment/). |
| virtual [set_WordSpacing](./set_wordspacing/)(float) | Устанавливает межсловный интервал текста. |
| [TextState](./textstate/)() | Создает объект состояния текста. |
| [TextState](./textstate/)(double) | Создает объект состояния текста с указанием размера шрифта. |
| [TextState](./textstate/)(System::Drawing::Color) | Создает объект состояния текста с указанием цвета переднего плана. |
| [TextState](./textstate/)(System::Drawing::Color, double) | Создает объект состояния текста с указанием цвета переднего плана и размера шрифта. |
| [TextState](./textstate/)(const System::String\&) | Создает объект состояния текста с указанием семейства шрифта. |
| [TextState](./textstate/)(const System::String\&, bool, bool) | Создает объект состояния текста с указанием семейства шрифта и стиля шрифта. |
| [TextState](./textstate/)(const System::String\&, double) | Создает объект состояния текста с указанием семейства шрифта и размера шрифта. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
