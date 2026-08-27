---
title: "Класс TextFragmentState"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Text.TextFragmentState. Представляет состояние текста фрагмента"
type: docs
weight: 11150
url: /ru/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class

Представляет состояние текста фрагмента.

```csharp
public sealed class TextFragmentState : TextState
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | Инициализирует новый экземпляр объекта `TextFragmentState` с указанным объектом [`TextFragment`](../textfragment/). Эта инициализация `TextFragmentState` не поддерживается. TextFragmentState доступен только через свойство [`TextState`](../textfragment/textstate/). |

## Свойства

| Имя | Описание |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | Устанавливает цвет фона текста, представленного объектом [`TextFragment`](../textfragment/) |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | Получает или задает межсимвольный интервал текста, представленного объектом [`TextFragment`](../textfragment/). |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | Получает или задаёт CoordinateOrigin текста. Если CoordinateOrigin имеет значение Descender, координата Y текста соответствует самой нижней точке шрифта. Если CoordinateOrigin имеет значение BaseLine, координата Y текста соответствует базовой линии шрифта. Значение по умолчанию — Descender. Если значение Descent шрифта слишком велико, текст может отображаться выше, чем у других шрифтов. В этом случае можно выбрать CoordinateOrigin BaseLine для лучшего отображения текста. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | Получает или задает флаг отрисовки границы прямоугольника текста. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | Получает или задает шрифт текста, представленного объектом [`TextFragment`](../textfragment/). |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | Получает или задает размер шрифта текста, представленного объектом [`TextFragment`](../textfragment/). |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | Задает стиль шрифта текста, представленного объектом [`TextFragment`](../textfragment/). |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | Получает или задает цвет переднего плана текста, представленного объектом [`TextFragment`](../textfragment/). |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | Получает или задает параметры форматирования. Установка параметров будет действовать только в сценариях генератора. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | Получает или задаёт горизонтальное выравнивание текста. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | Получает или задает горизонтальное масштабирование текста, представленного объектом [`TextFragment`](../textfragment/). |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | Получает или задает невидимость текста. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | Получает или задает межстрочный интервал текста. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | Получает или задает режим отрисовки текста. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | Получает или задаёт угол поворота в градусах. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | Получает или задает зачеркивание текста, представленного объектом [`TextFragment`](../textfragment/). |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | Получает или задает операции обводки цветом при отрисовке [`TextFragment`](../textfragment/) (обводка текста, граница прямоугольника). |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | Получает или задает нижний индекс текста, представленного объектом [`TextFragment`](../textfragment/). |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | Получает или задает верхний индекс текста, представленного объектом [`TextFragment`](../textfragment/). |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | Получает табуляции для текста. |
| [TabTag](../../aspose.pdf.text/textstate/tabtag/) { get; } | Вы можете разместить этот тег в тексте, чтобы объявить табуляцию. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | Получает или задает подчеркивание текста, представляемое объектом [`TextFragment`](../textfragment/). |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | Получает или задает интервал между словами текста. |

## Методы

| Имя | Описание |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | Применяет настройки из другого textState. |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | Проверяет, может ли входная строка быть размещена внутри определённого прямоугольника. |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | Измеряет высоту символа. (2 метода) |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | Измеряет строку. |

## Поля

| Имя | Описание |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Значение по умолчанию табуляции в ширинах символа пробела шрифта по умолчанию. |

## Примечания

Предоставляет способ изменить следующие свойства текста: шрифт (свойство [`Font`](./font/)), размер шрифта (свойство [`FontSize`](./fontsize/)), стиль шрифта (свойство [`FontStyle`](./fontstyle/)), цвет переднего плана (свойство [`ForegroundColor`](./foregroundcolor/)), цвет фона (свойство [`BackgroundColor`](./backgroundcolor/)). Обратите внимание, что изменение свойств `TextFragmentState` может изменить внутреннюю коллекцию [`Segments`](../textfragment/segments/), поскольку TextFragment является агрегатным объектом и может перестраивать внутренние сегменты или объединять их в один сегмент. Если ваша задача — оставить коллекцию [`Segments`](../textfragment/segments/) без изменений, изменяйте внутренние сегменты по отдельности.

## Примеры

Пример демонстрирует, как изменить цвет текста и размер шрифта текста с помощью объекта [`TextState`](../textstate/).

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Изменить цвет переднего плана первого вхождения текста.
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Изменить размер шрифта первого вхождения текста.
absorber.TextFragments[1].TextState.FontSize = 15;

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* class [TextState](../textstate/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


