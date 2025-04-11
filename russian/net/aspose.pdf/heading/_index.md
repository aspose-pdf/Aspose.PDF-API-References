---
title: Class Heading
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Heading. Представляет заголовок
type: docs
weight: 5470
url: /ru/net/aspose.pdf/heading/
---
## Класс заголовка

Представляет заголовок.

```csharp
public sealed class Heading : TextFragment
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Heading](heading/)(int) | Инициализирует новый экземпляр класса Cell. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Получает позицию текста для текста, представленного объектом [`TextFragment`](../../aspose.pdf.text/textfragment/). YIndent структуры Position представляет базовую координату текстового фрагмента. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | Получает целевую страницу. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Получает или задает примечание в конце абзаца. (только для генерации pdf) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Получает или задает сноску абзаца. (только для генерации pdf) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Получает объект формы, который содержит TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Получает или задает горизонтальное выравнивание текстового фрагмента. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Устанавливает гиперссылку фрагмента |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | Получает, должен ли заголовок нумероваться автоматически. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующем столбце. По умолчанию false. (для генерации pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или задает, является ли абзац встроенным. По умолчанию false. (для генерации pdf) |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | Получает, должен ли заголовок быть в списке оглавления. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или задает логическое значение, которое заставляет этот абзац генерироваться на новой странице. По умолчанию false. (для генерации pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе с следующим абзацем. По умолчанию false. (для генерации pdf) |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | Получает уровень. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или задает внешний отступ для абзаца (для генерации pdf) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Получает страницу, которая содержит TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Получает или задает позицию текста для текста, представленного объектом [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Получает прямоугольник TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Получает параметры замены текста. Параметры определяют поведение, когда текст фрагмента заменяется на более короткий/длинный. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Получает текстовые сегменты для текущего [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | Получает начальный номер заголовка. |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | Получает или задает стиль. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Получает или задает строковый текстовый объект, который представляет объект [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Получает или задает параметры редактирования текста. Параметры определяют специальное поведение, когда запрашиваемый символ не может быть записан шрифтом. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Получает или задает состояние текста для текста, который представляет объект [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | Получает страницу, которая содержит этот заголовок. |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | Получает верхнюю Y этого заголовка. |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | Получает или задает пользовательскую метку. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание текстового фрагмента. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Получает или задает количество обернутых строк для этого абзаца (только для генерации pdf) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещен поверх графика с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен позади текста на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | Клонирует заголовок. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | Клонирует заголовок со всеми сегментами. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Получает [`TextSegment`](../../aspose.pdf.text/textsegment/)(ы), представляющие указанную часть текста [`TextFragment`](../../aspose.pdf.text/textfragment/). |

### См. также

* класс [TextFragment](../../aspose.pdf.text/textfragment/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)