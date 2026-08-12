---
title: "Aspose::Pdf::Text::TextFragmentState класс"
linktitle: "TextFragmentState"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::TextFragmentState класс. Представляет состояние текста фрагмента текста в C++."
type: docs
weight: 4600
url: /ru/cpp/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class


Представляет состояние текста фрагмента.

```cpp
class TextFragmentState : public Aspose::Pdf::Text::TextState
```

## Методы

| Метод | Описание |
| --- | --- |
| [ApplyChangesFrom](./applychangesfrom/)(const System::SharedPtr\<TextState\>\&) override | Применяет настройки из другого textState. |
| [get_BackgroundColor](./get_backgroundcolor/)() override | Устанавливает цвет фона текста, представленного объектом [TextFragment](../textfragment/). |
| [get_CharacterSpacing](./get_characterspacing/)() override | Получает межсимвольный интервал текста, представленного объектом [TextFragment](../textfragment/). |
| [get_CoordinateOrigin](./get_coordinateorigin/)() override | Получает текст [CoordinateOrigin](../coordinateorigin/). Если [CoordinateOrigin](../coordinateorigin/) имеет значение Descender, координата Y текста соответствует самой нижней точке шрифта. Если [CoordinateOrigin](../coordinateorigin/) имеет значение BaseLine, координата Y текста соответствует базовой линии шрифта. Значение по умолчанию — Descender. Если значение Descent шрифта слишком велико, текст может отображаться выше, чем другие шрифты. В этом случае можно выбрать [CoordinateOrigin](../coordinateorigin/) BaseLine для лучшего отображения текста. |
| [get_DrawTextRectangleBorder](./get_drawtextrectangleborder/)() const | Получает флаг, указывающий, нарисована ли граница прямоугольника текста. |
| [get_Font](./get_font/)() override | Получает шрифт текста, представленного объектом [TextFragment](../textfragment/). |
| [get_FontSize](./get_fontsize/)() override | Получает размер шрифта текста, представленного объектом [TextFragment](../textfragment/). |
| [get_FontStyle](./get_fontstyle/)() override | Устанавливает стиль шрифта текста, представленного объектом [TextFragment](../textfragment/). |
| [get_ForegroundColor](./get_foregroundcolor/)() override | Получает цвет переднего плана текста, представленного объектом [TextFragment](../textfragment/). |
| [get_FormattingOptions](./get_formattingoptions/)() const | Получает параметры форматирования. Установка параметров будет действовать только в сценариях генератора. |
| [get_HorizontalAlignment](./get_horizontalalignment/)() override | Получает горизонтальное выравнивание текста. |
| [get_HorizontalScaling](./get_horizontalscaling/)() override | Получает горизонтальное масштабирование текста, представленного объектом [TextFragment](../textfragment/). |
| [get_Invisible](./get_invisible/)() override | Получает невидимость текста. |
| [get_LineSpacing](./get_linespacing/)() override | Получает межстрочный интервал текста. |
| [get_RenderingMode](./get_renderingmode/)() override | Получает режим рендеринга текста. |
| [get_Rotation](./get_rotation/)() | Получает угол вращения в градусах. |
| [get_StrikeOut](./get_strikeout/)() override | Получает перечёркивание текста, представленного объектом [TextFragment](../textfragment/). |
| [get_StrokingColor](./get_strokingcolor/)() override | Получает операции обводки цветом при рендеринге [TextFragment](../textfragment/) (обводка текста, граница прямоугольника) |
| [get_Subscript](./get_subscript/)() override | Получает нижний индекс текста, представленного объектом [TextFragment](../textfragment/). |
| [get_Superscript](./get_superscript/)() override | Получает верхний индекс текста, представленного объектом [TextFragment](../textfragment/). |
| [get_TabStops](./get_tabstops/)() const | Получает табуляции для текста. |
| [get_Underline](./get_underline/)() override | Получает подчеркивание текста, представленного объектом [TextFragment](../textfragment/). |
| [get_WordSpacing](./get_wordspacing/)() override | Получает межсловный интервал текста. |
| [IsFitRectangle](./isfitrectangle/)(const System::String\&, const System::SharedPtr\<Rectangle\>\&) | Проверяет, может ли входная строка быть размещена внутри определённого прямоугольника. |
| [MeasureHeight](./measureheight/)(char16_t) | Измеряет высоту символа. |
| [MeasureString](./measurestring/)(const System::String\&) override | Измеряет строку. |
| [set_BackgroundColor](./set_backgroundcolor/)(System::SharedPtr\<Color\>) override | Устанавливает цвет фона текста, представленного объектом [TextFragment](../textfragment/). |
| [set_CharacterSpacing](./set_characterspacing/)(float) override | Устанавливает межсимвольный интервал текста, представленного объектом [TextFragment](../textfragment/). |
| [set_CoordinateOrigin](./set_coordinateorigin/)(Aspose::Pdf::Text::CoordinateOrigin) override | Устанавливает текстовый [CoordinateOrigin](../coordinateorigin/). Если [CoordinateOrigin](../coordinateorigin/) имеет значение Descender, координата Y текста соответствует самой нижней точке шрифта. Если [CoordinateOrigin](../coordinateorigin/) имеет значение BaseLine, координата Y текста соответствует базовой линии шрифта. Значение по умолчанию — Descender. Если значение Descent шрифта слишком велико, текст может отображаться выше, чем другие шрифты. В этом случае можно выбрать [CoordinateOrigin](../coordinateorigin/) BaseLine для более корректного отображения текста. |
| [set_DrawTextRectangleBorder](./set_drawtextrectangleborder/)(bool) | Устанавливает флаг, указывающий, нарисована ли граница прямоугольника текста. |
| [set_Font](./set_font/)(System::SharedPtr\<Aspose::Pdf::Text::Font\>) override | Устанавливает шрифт текста, представленного объектом [TextFragment](../textfragment/). |
| [set_FontSize](./set_fontsize/)(float) override | Устанавливает размер шрифта текста, представленного объектом [TextFragment](../textfragment/). |
| [set_FontStyle](./set_fontstyle/)(FontStyles) override | Устанавливает стиль шрифта текста, представленного объектом [TextFragment](../textfragment/). |
| [set_ForegroundColor](./set_foregroundcolor/)(System::SharedPtr\<Color\>) override | Устанавливает цвет переднего плана текста, представленного объектом [TextFragment](../textfragment/). |
| [set_FormattingOptions](./set_formattingoptions/)(const System::SharedPtr\<TextFormattingOptions\>\&) | Устанавливает параметры форматирования. Настройка параметров будет действовать только в сценариях генератора. |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) override | Устанавливает горизонтальное выравнивание текста. |
| [set_HorizontalScaling](./set_horizontalscaling/)(float) override | Устанавливает горизонтальное масштабирование текста, представленного объектом [TextFragment](../textfragment/). |
| [set_Invisible](./set_invisible/)(bool) override | Устанавливает невидимость текста. |
| [set_LineSpacing](./set_linespacing/)(float) override | Устанавливает межстрочный интервал текста. |
| [set_RenderingMode](./set_renderingmode/)(TextRenderingMode) override | Устанавливает режим рендеринга текста. |
| [set_Rotation](./set_rotation/)(double) | Устанавливает угол поворота в градусах. |
| [set_StrikeOut](./set_strikeout/)(bool) override | Устанавливает зачеркивание текста, представленного объектом [TextFragment](../textfragment/). |
| [set_StrokingColor](./set_strokingcolor/)(System::SharedPtr\<Color\>) override | Устанавливает операции обводки цветом при рендеринге [TextFragment](../textfragment/) (обводка текста, граница прямоугольника) |
| [set_Subscript](./set_subscript/)(bool) override | Устанавливает нижний индекс текста, представленного объектом [TextFragment](../textfragment/). |
| [set_Superscript](./set_superscript/)(bool) override | Устанавливает верхний индекс текста, представленного объектом [TextFragment](../textfragment/). |
| [set_Underline](./set_underline/)(bool) override | Устанавливает подчеркивание текста, представленного объектом [TextFragment](../textfragment/). |
| [set_WordSpacing](./set_wordspacing/)(float) override | Устанавливает межсловный интервал текста. |
| [TextFragmentState](./textfragmentstate/)(const System::SharedPtr\<TextFragment\>\&) | Инициализирует новый экземпляр объекта [TextFragmentState](./) с указанным объектом [TextFragment](../textfragment/). Эта инициализация [TextFragmentState](./) не поддерживается. [TextFragmentState](./) доступен только через свойство [TextFragment::TextState](../). |
## Примечания


Предоставляет способ изменить следующие свойства текста: шрифт ([TextFragmentState::Font](../) свойство) размер шрифта ([TextFragmentState::FontSize](../) свойство) стиль шрифта ([TextFragmentState::FontStyle](../) свойство) цвет переднего плана ([TextFragmentState::ForegroundColor](../) свойство) цвет фона ([TextFragmentState::BackgroundColor](../) свойство)

[Note](../../aspose.pdf/note/) that changing [TextFragmentState](./) properties may change inner [TextFragment::Segments](../) collection because [TextFragment](../textfragment/) is an aggregate object and it may rearrange internal segments or merge them into single segment. If your requirement is to leave the [TextFragment::Segments](../) collection unchanged, please change inner segments individually. 


## См. также

* Class [TextState](../textstate/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
