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
| [TextFragmentState](textfragmentstate)(TextFragment) | Инициализирует новый экземпляр[`TextFragmentState`](../textfragmentstate) объект с указанным[`TextFragment`](../textfragment) object. Это[`TextFragmentState`](../textfragmentstate) инициализация не поддерживается. TextFragmentState доступен только с[`TextState`](../textfragment/textstate) свойство. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor) { get; set; } | Устанавливает цвет фона текста, представленного[`TextFragment`](../textfragment) объект |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing) { get; set; } | Получает или задает межсимвольный интервал в тексте, представленном[`TextFragment`](../textfragment) объект. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder) { get; set; } | Получает или задает флаг нарисованной границы текстового прямоугольника. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font) { get; set; } | Получает или задает шрифт текста, представленного[`TextFragment`](../textfragment) объект |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize) { get; set; } | Получает или задает размер шрифта текста, представленного[`TextFragment`](../textfragment) объект |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle) { get; set; } | Устанавливает стиль шрифта текста, представленного[`TextFragment`](../textfragment) объект |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor) { get; set; } | Получает или задает цвет переднего плана текста, представленного[`TextFragment`](../textfragment) объект |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions) { get; set; } | Получает или задает параметры форматирования. Установка параметров будет эффективна только в сценариях генератора. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment) { get; set; } | Получает или задает горизонтальное выравнивание текста. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling) { get; set; } | Получает или задает горизонтальное масштабирование текста, представленного[`TextFragment`](../textfragment) объект. |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible) { get; set; } | Получает или устанавливает невидимость текста. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing) { get; set; } | Получает или задает межстрочный интервал текста. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode) { get; set; } | Получает или задает режим рендеринга текста. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation) { get; set; } | Получает или задает угол поворота в градусах. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout) { set; } | Зачеркивает текст, представленный[`TextFragment`](../textfragment) объект |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor) { get; set; } | Получает или задает операции обводки цветом[`TextFragment`](../textfragment) рендеринг (обводка текста, граница прямоугольника) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript) { get; set; } | Получает или задает нижний индекс текста, представленного[`TextFragment`](../textfragment) объект. |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript) { get; set; } | Получает или задает верхний индекс текста, представленного[`TextFragment`](../textfragment) объект. |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops) { get; } | Получает позиции табуляции для текста. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline) { get; set; } | Получает или задает подчеркивание текста, представленного[`TextFragment`](../textfragment) объект |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing) { get; set; } | Получает или задает межсловный интервал в тексте. |

## Методы

| Имя | Описание |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom)(TextState) | Применяет настройки из другого textState. |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring)(string) | Измеряет строку. |

## Поля

| Имя | Описание |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue) | Значение по умолчанию табуляции в ширине пробела шрифта по умолчанию. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag) | Вы можете поместить этот тег в текст, чтобы объявить табуляцию. |

### Примечания

Позволяет изменить следующие свойства текста: шрифт ([`Font`](./font) свойство) размер шрифта ([`FontSize`](./fontsize) свойство) стиль шрифта ([`FontStyle`](./fontstyle) свойство) цвет переднего плана ([`ForegroundColor`](./foregroundcolor) свойство) цвет фона ([`BackgroundColor`](./backgroundcolor) property) Обратите внимание, что изменение[`TextFragmentState`](../textfragmentstate) свойства могут измениться внутри[`Segments`](../textfragment/segments) потому что TextFragment является совокупным объектом и может переупорядочивать внутренние сегменты или объединять их в один сегмент. Если вам нужно оставить[`Segments`](../textfragment/segments) Коллекция без изменений, пожалуйста, меняйте внутренние сегменты по отдельности.

### Примеры

Пример демонстрирует, как изменить цвет текста и размер шрифта текста с помощью[`TextState`](../textstate) объект.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создаем объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Принять поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Изменяем цвет переднего плана первого вхождения текста
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Изменяем размер шрифта первого вхождения текста
absorber.TextFragments[1].TextState.FontSize = 15;

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### Смотрите также

* class [TextFragmentAbsorber](../textfragmentabsorber)
* class [Document](../../aspose.pdf/document)
* class [TextState](../textstate)
* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
