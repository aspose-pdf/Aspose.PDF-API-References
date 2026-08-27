---
title: "Класс Heading"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Heading. Представляет заголовок"
type: docs
weight: 5590
url: /ru/net/aspose.pdf/heading/
---
## Heading class

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
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Получает позицию текста, представленного объектом [`TextFragment`](../../aspose.pdf.text/textfragment/). Поле YIndent структуры Position представляет координату базовой линии фрагмента текста. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | Получает целевую страницу. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Получает или задает конец абзаца (только для генерации PDF). |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Получает или задает сноску абзаца (только для генерации PDF). |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Получает объект формы, содержащий `TextFragment`. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Получает или задает горизонтальное выравнивание фрагмента текста. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Устанавливает гиперссылку фрагмента. |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | Получает, следует ли автоматически нумеровать заголовок. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующей колонке. По умолчанию false. (для pdf‑генерации) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или задает, является ли абзац встроенным. По умолчанию false. (для pdf‑генерации) |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | Получает, должен ли заголовок быть в списке оглавления. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или задает логическое значение, принуждающее этот абзац генерироваться на новой Page. По умолчанию false. (для pdf‑генерации) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или задает логическое значение, указывающее, остаётся ли текущий абзац на той же Page вместе со следующим абзацем. По умолчанию false. (для pdf‑генерации) |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | Получает уровень. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или задает внешний отступ для абзаца (для генерации PDF) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Получает страницу, содержащую `TextFragment`. |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Получает или задает позицию текста, представленного объектом [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Получает прямоугольник `TextFragment`. |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Получает параметры замены текста. Параметры определяют поведение при замене текста фрагмента на более короткий/длинный. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Получает сегменты текста для текущего [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | Получает начальный номер заголовка. |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | Получает или задает стиль. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Получает или задает объект String текста, который представляет объект [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Получает или задает параметры редактирования текста. Параметры определяют особое поведение, когда требуемый символ нельзя отобразить шрифтом. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Получает или задает состояние текста для текста, который представляет объект [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | Получает страницу, содержащую этот заголовок. |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | Получает верхнюю координату Y этих заголовков. |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | Получает или задает пользовательскую метку. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание фрагмента текста. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Получает или задает количество строк переноса для этого абзаца (только для генерации PDF). |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещён над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещён позади текста на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | Клонировать заголовок. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | Клонировать заголовок со всеми сегментами. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Получает [`TextSegment`](../../aspose.pdf.text/textsegment/), представляющие указанную часть текста [`TextFragment`](../../aspose.pdf.text/textfragment/). |

### См. также

* class [TextFragment](../../aspose.pdf.text/textfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


