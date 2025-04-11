---
title: Class TextState
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Text.TextState. Представляет состояние текста текста
type: docs
weight: 11070
url: /ru/net/aspose.pdf.text/textstate/
---
## Класс TextState

Представляет состояние текста текста

```csharp
public class TextState
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextState](textstate/#constructor)() | Создает объект состояния текста. |
| [TextState](textstate/#constructor_2)(Color) | Создает объект состояния текста с указанием цвета переднего плана. |
| [TextState](textstate/#constructor_1)(double) | Создает объект состояния текста с указанием размера шрифта. |
| [TextState](textstate/#constructor_4)(string) | Создает объект состояния текста с указанием семейства шрифтов. |
| [TextState](textstate/#constructor_3)(Color, double) | Создает объект состояния текста с указанием цвета переднего плана и размера шрифта. |
| [TextState](textstate/#constructor_6)(string, double) | Создает объект состояния текста с указанием семейства шрифтов и размера шрифта. |
| [TextState](textstate/#constructor_5)(string, bool, bool) | Создает объект состояния текста с указанием семейства шрифтов и стиля шрифта. |

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [BackgroundColor](../../aspose.pdf.text/textstate/backgroundcolor/) { get; set; } | Устанавливает цвет фона текста. |
| virtual [CharacterSpacing](../../aspose.pdf.text/textstate/characterspacing/) { get; set; } | Получает или устанавливает межсимвольный интервал текста. |
| virtual [CoordinateOrigin](../../aspose.pdf.text/textstate/coordinateorigin/) { get; set; } | Получает или устанавливает координаты начала текста. Если CoordinateOrigin равен Descender, координата Y текста соответствует самой низкой точке шрифта. Если CoordinateOrigin равен BaseLine, координата Y текста соответствует базовой линии шрифта. Значение по умолчанию - Descender. Если значение Descent шрифта слишком велико, текст может отображаться выше других шрифтов. В этом случае можно выбрать CoordinateOrigin BaseLine для лучшего отображения текста. |
| virtual [Font](../../aspose.pdf.text/textstate/font/) { get; set; } | Получает или устанавливает шрифт текста. |
| virtual [FontSize](../../aspose.pdf.text/textstate/fontsize/) { get; set; } | Получает или устанавливает размер шрифта текста. |
| virtual [FontStyle](../../aspose.pdf.text/textstate/fontstyle/) { get; set; } | Устанавливает стиль шрифта текста. |
| virtual [ForegroundColor](../../aspose.pdf.text/textstate/foregroundcolor/) { get; set; } | Получает или устанавливает цвет переднего плана текста. |
| virtual [HorizontalAlignment](../../aspose.pdf.text/textstate/horizontalalignment/) { get; set; } | Получает или устанавливает горизонтальное выравнивание текста. |
| virtual [HorizontalScaling](../../aspose.pdf.text/textstate/horizontalscaling/) { get; set; } | Получает или устанавливает горизонтальное масштабирование текста. |
| virtual [Invisible](../../aspose.pdf.text/textstate/invisible/) { get; set; } | Получает или устанавливает невидимость текста. Это в основном отражает состояние [`RenderingMode`](./renderingmode/), за исключением некоторых особых случаев (например, обрезки). |
| virtual [LineSpacing](../../aspose.pdf.text/textstate/linespacing/) { get; set; } | Получает или устанавливает межстрочный интервал текста. |
| virtual [RenderingMode](../../aspose.pdf.text/textstate/renderingmode/) { get; set; } | Получает или устанавливает режим рендеринга текста. |
| virtual [StrikeOut](../../aspose.pdf.text/textstate/strikeout/) { get; set; } | Получает или устанавливает зачеркивание текста, представленное объектом [`TextSegment`](../textsegment/). |
| virtual [StrokingColor](../../aspose.pdf.text/textstate/strokingcolor/) { get; set; } | Получает или устанавливает цвет переднего плана текста. |
| virtual [Subscript](../../aspose.pdf.text/textstate/subscript/) { get; set; } | Получает или устанавливает нижний индекс текста. |
| virtual [Superscript](../../aspose.pdf.text/textstate/superscript/) { get; set; } | Получает или устанавливает верхний индекс текста. |
| virtual [Underline](../../aspose.pdf.text/textstate/underline/) { get; set; } | Получает или устанавливает подчеркивание текста, представленное объектом [`TextFragment`](../textfragment/). |
| virtual [WordSpacing](../../aspose.pdf.text/textstate/wordspacing/) { get; set; } | Получает или устанавливает интервал между словами текста. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [ApplyChangesFrom](../../aspose.pdf.text/textstate/applychangesfrom/)(TextState) | Применяет настройки из другого textState. |
| [MeasureHeight](../../aspose.pdf.text/textstate/measureheight/)(char) | Измеряет высоту символа. |
| virtual [MeasureString](../../aspose.pdf.text/textstate/measurestring/)(string) | Измеряет строку. |

## Поля

| Имя | Описание |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Значение по умолчанию для табуляции в ширинах символа пробела по умолчанию. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | Вы можете разместить этот тег в тексте, чтобы объявить табуляцию. |

### См. также

* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)