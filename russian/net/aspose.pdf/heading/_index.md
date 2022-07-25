---
title: Heading
second_title: Aspose.PDF для справочника API .NET
description: Представляет заголовок.
type: docs
weight: 3360
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
| [Heading](heading)(int) | Инициализирует новый экземпляр класса Cell. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition) { get; set; } | Получает текстовую позицию для текста, представленного с помощью[`TextFragment`](../../aspose.pdf.text/textfragment) object. YIndent структуры Position представляет базовую координату текстового фрагмента. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage) { get; set; } | Получает целевую страницу. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote) { get; set; } | Получает или задает примечание в конце абзаца. (только для создания PDF-файлов) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote) { get; set; } | Получает или задает примечание к абзацу (только для создания PDF-файлов) |
| [Form](../../aspose.pdf.text/textfragment/form) { get; } | Получает объект формы, содержащий TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment) { get; set; } | Получает или задает горизонтальное выравнивание фрагмента текста. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink) { set; } | Устанавливает гиперссылку фрагмента |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence) { get; set; } | Получает, что заголовок должен быть пронумерован автоматически. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. Значение по умолчанию — false. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Получает или задает встроенный абзац. Значение по умолчанию — false. (для создания pdf) |
| [IsInList](../../aspose.pdf/heading/isinlist) { get; set; } | Получает, что заголовок должен быть в toc list. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Получает или задает логическое значение, которое заставляет этот абзац создаваться на новой странице. Значение по умолчанию — false. |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Получает или задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. Значение по умолчанию — false. (для создания PDF) |
| [Level](../../aspose.pdf/heading/level) { get; set; } | Получает уровень. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Получает или задает внешнее поле для абзаца (для создания PDF-файла) |
| [Page](../../aspose.pdf.text/textfragment/page) { get; } | Получает страницу, содержащую TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position) { get; set; } | Получает или задает позицию текста для текста, представленного[`TextFragment`](../../aspose.pdf.text/textfragment) объект. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle) { get; } | Получает прямоугольник TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions) { get; } | Получает параметры замены текста. Параметры определяют поведение при замене текста фрагмента на более короткий/длинный. |
| [Segments](../../aspose.pdf.text/textfragment/segments) { get; set; } | Получает текстовые сегменты для текущего[`TextFragment`](../../aspose.pdf.text/textfragment) . |
| [StartNumber](../../aspose.pdf/heading/startnumber) { get; set; } | Получает начальный номер заголовка. |
| [Style](../../aspose.pdf/heading/style) { get; set; } | Получает или задает стиль. |
| [Text](../../aspose.pdf.text/textfragment/text) { get; set; } | Получает или устанавливаетString текстовый объект, который[`TextFragment`](../../aspose.pdf.text/textfragment) объект представляет. |
| [TextState](../../aspose.pdf.text/textfragment/textstate) { get; } | Получает или задает состояние текста для текста,[`TextFragment`](../../aspose.pdf.text/textfragment) объект представляет. |
| [TocPage](../../aspose.pdf/heading/tocpage) { get; set; } | Получает страницу, содержащую этот заголовок. |
| [Top](../../aspose.pdf/heading/top) { get; set; } | Получает верхнюю Y этих заголовков. |
| [UserLabel](../../aspose.pdf/heading/userlabel) { get; set; } | Получает или устанавливает метку пользователя. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment) { get; set; } | Получает или задает вертикальное выравнивание текстового фрагмента. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount) { get; set; } | Получает или задает количество строк переноса для этого абзаца (только для создания PDF) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Получает или задает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone)() | Клонировать заголовок. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments)() | Клонировать заголовок со всеми сегментами. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments)(int, int) | получает[`TextSegment`](../../aspose.pdf.text/textsegment) (s) представляющие указанную часть[`TextFragment`](../../aspose.pdf.text/textfragment) текст. |

### Смотрите также

* class [TextFragment](../../aspose.pdf.text/textfragment)
* пространство имен [Aspose.Pdf](../../aspose.pdf)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
