---
title: TextFragmentState
second_title: Aspose.PDF для справочника API .NET
description: Представляет текстовое состояние текстового фрагмента.
type: docs
weight: 7130
url: /ru/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class

Представляет текстовое состояние текстового фрагмента.

```csharp
public sealed class TextFragmentState : TextState
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextFragmentState](textfragmentstate)(TextFragment) | Инициализирует новый экземпляр объекта[`TextFragmentState`](../textfragmentstate)с указанным[`TextFragment`](../textfragment)объект. Эта инициализация[`TextFragmentState`](../textfragmentstate)не поддерживается. TextFragmentState доступен только со свойством[`TextState`](../textfragment/textstate). |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor) { get; set; } | Устанавливает цвет фона текста, представленного объектом[`TextFragment`](../textfragment) |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing) { get; set; } | Получает или задает межсимвольный интервал в тексте, представленном объектом[`TextFragment`](../textfragment). |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder) { get; set; } | Получает или устанавливает флаг, если граница текстового прямоугольника нарисована. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font) { get; set; } | Получает или задает шрифт текста, представленного объектом[`TextFragment`](../textfragment) |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize) { get; set; } | Получает или задает размер шрифта текста, представленного объектом[`TextFragment`](../textfragment) |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle) { get; set; } | Устанавливает стиль шрифта текста, представленного объектом[`TextFragment`](../textfragment) |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor) { get; set; } | Получает или задает цвет переднего плана текста, представленного объектом[`TextFragment`](../textfragment) |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions) { get; set; } | Получает или задает параметры форматирования. Настройка параметров будет эффективна только в сценариях с генератором. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment) { get; set; } | Получает или задает горизонтальное выравнивание текста. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling) { get; set; } | Получает или задает горизонтальное масштабирование текста, представленного объектом[`TextFragment`](../textfragment). |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible) { get; set; } | Получает или устанавливает невидимость текста. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing) { get; set; } | Получает или задает межстрочный интервал текста. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode) { get; set; } | Получает или устанавливает режим рендеринга текста. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation) { get; set; } | Получает или задает угол поворота в градусах. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout) { set; } | Устанавливает зачеркивание для текста, представленного объектом[`TextFragment`](../textfragment) |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor) { get; set; } | Получает или задает операции обводки цветом[`TextFragment`](../textfragment)рендеринг (обводка текста, граница прямоугольника) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript) { get; set; } | Получает или задает индекс текста, представленный объектом[`TextFragment`](../textfragment). |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript) { get; set; } | Получает или задает верхний индекс текста, представленный объектом[`TextFragment`](../textfragment). |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops) { get; } | Получает позиции табуляции для текста. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline) { get; set; } | Получает или устанавливает подчеркивание для текста, представленного[`TextFragment`](../textfragment)объектом |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing) { get; set; } | Получает или задает интервал между словами в тексте. |

## Методы

| Имя | Описание |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom)(TextState) | Применяет настройки из другого textState. |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring)(string) | Измеряет строку. |

## Поля

| Имя | Описание |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue) | Значение по умолчанию табуляции в ширине символа пробела шрифта по умолчанию. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag) | Вы можете поместить этот тег в текст, чтобы объявить табуляцию. |

### Примечания

Позволяет изменить следующие свойства текста: font ([`Font`](./font)свойство) размер шрифта ([`FontSize`](./fontsize)свойство) стиль шрифта ([`FontStyle`](./fontstyle)свойство) цвет переднего плана ([`ForegroundColor`](./foregroundcolor)свойство) цвет фона ([`BackgroundColor`](./backgroundcolor)свойство) Обратите внимание, что изменение свойств[`TextFragmentState`](../textfragmentstate)может изменить внутренние[`Segments`](../textfragment/segments)collection, потому что TextFragment является агрегатным объектом и может переупорядочивать внутренние сегменты или объединять их в один сегмент. Если вы хотите оставить коллекцию[`Segments`](../textfragment/segments)неизменной, измените внутренние сегменты по отдельности.

### Примеры

В примере показано, как изменить цвет текста и размер шрифта текста с помощью[`TextState`](../textstate)объект.

```csharp
// Открыть документ
ocument doc = new Document(@"D:\Tests\input.pdf");

// Создаем объект TextFragmentAbsorber для поиска всех вхождений текста «hello world»
extFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Принять поглотитель для первой страницы
oc.Pages[1].Accept(absorber);

// Изменяем цвет переднего плана первого текста вхождения
bsorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Изменить размер шрифта первого текста вхождения
bsorber.TextFragments[1].TextState.FontSize = 15;

// Сохранить документ
oc.Save(@"D:\Tests\output.pdf");  
```

### Смотрите также

* class [TextFragmentAbsorber](../textfragmentabsorber)
* class [Document](../../aspose.pdf/document)
* class [TextState](../textstate)
* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
