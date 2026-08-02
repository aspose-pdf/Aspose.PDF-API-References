---
title: "Класс TextState"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Text.TextState. Представляет состояние текста"
type: docs
weight: 11260
url: /ru/net/aspose.pdf.text/textstate/
---
## TextState class

Представляет состояние текста

```csharp
public class TextState
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextState](textstate/#constructor)() | Создаёт объект состояния текста. |
| [TextState](textstate/#constructor_2)(Color) | Создаёт объект состояния текста с указанием цвета переднего плана. |
| [TextState](textstate/#constructor_1)(double) | Создаёт объект состояния текста с указанием размера шрифта. |
| [TextState](textstate/#constructor_4)(string) | Создаёт объект состояния текста с указанием семейства шрифта. |
| [TextState](textstate/#constructor_3)(Color, double) | Создаёт объект состояния текста с указанием цвета переднего плана и размера шрифта. |
| [TextState](textstate/#constructor_6)(string, double) | Создаёт объект состояния текста с указанием семейства шрифта и размера шрифта. |
| [TextState](textstate/#constructor_5)(string, bool, bool) | Создаёт объект состояния текста с указанием семейства шрифта и стиля шрифта. |

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [BackgroundColor](../../aspose.pdf.text/textstate/backgroundcolor/) { get; set; } | Устанавливает цвет фона текста. |
| virtual [CharacterSpacing](../../aspose.pdf.text/textstate/characterspacing/) { get; set; } | Получает или задаёт межсимвольный интервал текста. |
| virtual [CoordinateOrigin](../../aspose.pdf.text/textstate/coordinateorigin/) { get; set; } | Получает или задаёт CoordinateOrigin текста. Если CoordinateOrigin имеет значение Descender, координата Y текста соответствует самой нижней точке шрифта. Если CoordinateOrigin имеет значение BaseLine, координата Y текста соответствует базовой линии шрифта. Значение по умолчанию — Descender. Если значение Descent шрифта слишком велико, текст может отображаться выше, чем у других шрифтов. В этом случае можно выбрать CoordinateOrigin BaseLine для лучшего отображения текста. |
| virtual [Font](../../aspose.pdf.text/textstate/font/) { get; set; } | Получает или задаёт шрифт текста. |
| virtual [FontSize](../../aspose.pdf.text/textstate/fontsize/) { get; set; } | Получает или задаёт размер шрифта текста. |
| virtual [FontStyle](../../aspose.pdf.text/textstate/fontstyle/) { get; set; } | Устанавливает стиль шрифта текста. |
| virtual [ForegroundColor](../../aspose.pdf.text/textstate/foregroundcolor/) { get; set; } | Получает или задаёт цвет переднего плана текста. |
| virtual [HorizontalAlignment](../../aspose.pdf.text/textstate/horizontalalignment/) { get; set; } | Получает или задаёт горизонтальное выравнивание текста. |
| virtual [HorizontalScaling](../../aspose.pdf.text/textstate/horizontalscaling/) { get; set; } | Получает или задаёт горизонтальное масштабирование текста. |
| virtual [Invisible](../../aspose.pdf.text/textstate/invisible/) { get; set; } | Получает или задаёт невидимость текста. По сути это отражает состояние [`RenderingMode`](./renderingmode/), за исключением некоторых особых случаев (например, обрезка). |
| virtual [LineSpacing](../../aspose.pdf.text/textstate/linespacing/) { get; set; } | Получает или задает межстрочный интервал текста. |
| virtual [RenderingMode](../../aspose.pdf.text/textstate/renderingmode/) { get; set; } | Получает или задает режим отображения текста. |
| virtual [StrikeOut](../../aspose.pdf.text/textstate/strikeout/) { get; set; } | Получает или задает зачеркивание текста, представляемое объектом [`TextSegment`](../textsegment/). |
| virtual [StrokingColor](../../aspose.pdf.text/textstate/strokingcolor/) { get; set; } | Получает или задаёт цвет переднего плана текста. |
| virtual [Subscript](../../aspose.pdf.text/textstate/subscript/) { get; set; } | Получает или задает нижний индекс текста. |
| virtual [Superscript](../../aspose.pdf.text/textstate/superscript/) { get; set; } | Получает или задает верхний индекс текста. |
| [TabTag](../../aspose.pdf.text/textstate/tabtag/) { get; } | Вы можете разместить этот тег в тексте, чтобы объявить табуляцию. |
| virtual [Underline](../../aspose.pdf.text/textstate/underline/) { get; set; } | Получает или задает подчеркивание текста, представляемое объектом [`TextFragment`](../textfragment/). |
| virtual [WordSpacing](../../aspose.pdf.text/textstate/wordspacing/) { get; set; } | Получает или задает интервал между словами текста. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [ApplyChangesFrom](../../aspose.pdf.text/textstate/applychangesfrom/)(TextState) | Применяет настройки из другого textState. |
| [MeasureHeight](../../aspose.pdf.text/textstate/measureheight/)(char) | Измеряет высоту символа. |
| virtual [MeasureString](../../aspose.pdf.text/textstate/measurestring/)(string) | Измеряет строку. |

## Поля

| Имя | Описание |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Значение по умолчанию табуляции в ширинах символа пробела шрифта по умолчанию. |

### См. также

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


