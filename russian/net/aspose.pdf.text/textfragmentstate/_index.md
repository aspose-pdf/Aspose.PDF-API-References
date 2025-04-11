---
title: Class TextFragmentState
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Text.TextFragmentState. Представляет состояние текста фрагмента текста
type: docs
weight: 10970
url: /ru/net/aspose.pdf.text/textfragmentstate/
---
## Класс TextFragmentState

Представляет состояние текста фрагмента текста.

```csharp
public sealed class TextFragmentState : TextState
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | Инициализирует новый экземпляр объекта `TextFragmentState` с указанным объектом [`TextFragment`](../textfragment/). Эта инициализация `TextFragmentState` не поддерживается. TextFragmentState доступен только с свойством [`TextState`](../textfragment/textstate/). |

## Свойства

| Имя | Описание |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | Устанавливает цвет фона текста, представленного объектом [`TextFragment`](../textfragment/) |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | Получает или устанавливает межсимвольный интервал текста, представленного объектом [`TextFragment`](../textfragment/). |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | Получает или устанавливает начальную точку текста. Если начальная точка - Descender, координата Y текста соответствует самой низкой точке шрифта. Если начальная точка - BaseLine, координата Y текста соответствует базовой линии шрифта. Значение по умолчанию - Descender. Если значение Descent шрифта слишком велико, текст может отображаться выше других шрифтов. В этом случае для лучшего отображения текста можно выбрать начальную точку BaseLine. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | Получает или устанавливает флаг рисования границы текстового прямоугольника. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | Получает или устанавливает шрифт текста, представленного объектом [`TextFragment`](../textfragment/) |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | Получает или устанавливает размер шрифта текста, представленного объектом [`TextFragment`](../textfragment/) |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | Устанавливает стиль шрифта текста, представленного объектом [`TextFragment`](../textfragment/) |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | Получает или устанавливает цвет переднего плана текста, представленного объектом [`TextFragment`](../textfragment/) |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | Получает или устанавливает параметры форматирования. Установка параметров будет эффективна только в сценариях генератора. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | Получает или устанавливает горизонтальное выравнивание текста. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | Получает или устанавливает горизонтальное масштабирование текста, представленного объектом [`TextFragment`](../textfragment/). |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | Получает или устанавливает невидимость текста. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | Получает или устанавливает межстрочный интервал текста. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | Получает или устанавливает режим отображения текста. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | Получает или устанавливает угол поворота в градусах. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | Получает или устанавливает зачеркивание текста, представленного объектом [`TextFragment`](../textfragment/) |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | Получает или устанавливает цвет операций обводки рендеринга [`TextFragment`](../textfragment/) (обводка текста, граница прямоугольника) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | Получает или устанавливает подстрочный текст, представленный объектом [`TextFragment`](../textfragment/). |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | Получает или устанавливает надстрочный текст, представленный объектом [`TextFragment`](../textfragment/). |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | Получает табуляции для текста. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | Получает или устанавливает подчеркивание текста, представленного объектом [`TextFragment`](../textfragment/) |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | Получает или устанавливает межсловной интервал текста. |

## Методы

| Имя | Описание |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | Применяет настройки из другого textState. |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | Проверяет, может ли входная строка быть помещена внутри определенного прямоугольника. |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | Измеряет высоту символа. (2 метода) |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | Измеряет строку. |

## Поля

| Имя | Описание |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Значение по умолчанию для табуляции в ширинах пробела символа по умолчанию. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | Вы можете разместить этот тег в тексте, чтобы объявить табуляцию. |

## Замечания

Предоставляет способ изменить следующие свойства текста: шрифт ([`Font`](./font/) свойство) размер шрифта ([`FontSize`](./fontsize/) свойство) стиль шрифта ([`FontStyle`](./fontstyle/) свойство) цвет переднего плана ([`ForegroundColor`](./foregroundcolor/) свойство) цвет фона ([`BackgroundColor`](./backgroundcolor/) свойство) Обратите внимание, что изменение свойств `TextFragmentState` может изменить внутреннюю коллекцию [`Segments`](../textfragment/segments/), поскольку TextFragment является агрегатным объектом и может переставить внутренние сегменты или объединить их в один сегмент. Если ваше требование состоит в том, чтобы оставить коллекцию [`Segments`](../textfragment/segments/) без изменений, пожалуйста, изменяйте внутренние сегменты по отдельности.

## Примеры

Пример демонстрирует, как изменить цвет текста и размер шрифта текста с объектом [`TextState`](../textstate/).

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* класс [TextFragmentAbsorber](../textfragmentabsorber/)
* класс [Document](../../aspose.pdf/document/)
* класс [TextState](../textstate/)
* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)