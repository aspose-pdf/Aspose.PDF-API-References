---
title: TextFragment
second_title: Aspose.PDF для справочника API .NET
description: Представляет фрагмент текста Pdf.
type: docs
weight: 7100
url: /ru/net/aspose.pdf.text/textfragment/
---
## TextFragment class

Представляет фрагмент текста Pdf.

```csharp
public class TextFragment : BaseParagraph
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextFragment](textfragment#constructor)() | Инициализирует новый экземпляр[`TextFragment`](../textfragment) объект. |
| [TextFragment](textfragment#constructor_2)(string) | Создает[`TextFragment`](../textfragment) объект с одним[`TextSegment`](../textsegment) объект внутри. Задает текстовую строку внутри сегмента. |
| [TextFragment](textfragment#constructor_1)(TabStops) | Инициализирует новый экземпляр[`TextFragment`](../textfragment) объект с предустановленным[`TabStops`](../tabstops) позиции. |
| [TextFragment](textfragment#constructor_3)(string, TabStops) | Создает[`TextFragment`](../textfragment) объект с одним[`TextSegment`](../textsegment) объект внутри и предопределенный[`TabStops`](../tabstops) позиции. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition) { get; set; } | Получает текстовую позицию для текста, представленного с помощью[`TextFragment`](../textfragment) object. YIndent структуры Position представляет базовую координату текстового фрагмента. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote) { get; set; } | Получает или задает примечание в конце абзаца. (только для создания PDF-файлов) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote) { get; set; } | Получает или задает примечание к абзацу (только для создания PDF-файлов) |
| [Form](../../aspose.pdf.text/textfragment/form) { get; } | Получает объект формы, содержащий TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment) { get; set; } | Получает или задает горизонтальное выравнивание фрагмента текста. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink) { set; } | Устанавливает гиперссылку фрагмента |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. Значение по умолчанию — false. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Получает или задает встроенный абзац. Значение по умолчанию — false. (для создания pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Получает или задает логическое значение, которое заставляет этот абзац создаваться на новой странице. Значение по умолчанию — false. |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Получает или задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. Значение по умолчанию — false. (для создания PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Получает или задает внешнее поле для абзаца (для создания PDF-файла) |
| [Page](../../aspose.pdf.text/textfragment/page) { get; } | Получает страницу, содержащую TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position) { get; set; } | Получает или задает позицию текста для текста, представленного[`TextFragment`](../textfragment) объект. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle) { get; } | Получает прямоугольник TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions) { get; } | Получает параметры замены текста. Параметры определяют поведение при замене текста фрагмента на более короткий/длинный. |
| [Segments](../../aspose.pdf.text/textfragment/segments) { get; set; } | Получает текстовые сегменты для текущего[`TextFragment`](../textfragment) . |
| [Text](../../aspose.pdf.text/textfragment/text) { get; set; } | Получает или устанавливаетString текстовый объект, который[`TextFragment`](../textfragment) объект представляет. |
| [TextState](../../aspose.pdf.text/textfragment/textstate) { get; } | Получает или задает состояние текста для текста,[`TextFragment`](../textfragment) объект представляет. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment) { get; set; } | Получает или задает вертикальное выравнивание текстового фрагмента. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount) { get; set; } | Получает или задает количество строк переноса для этого абзаца (только для создания PDF) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Получает или задает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone)() | Клонировать фрагмент. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments)() | Клонировать фрагмент со всеми сегментами. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments)(int, int) | получает[`TextSegment`](../textsegment) (s) представляющие указанную часть[`TextFragment`](../textfragment) текст. |

### Примечания

В двух словах,[`TextFragment`](../textfragment) объект содержит список[`TextSegment`](../textsegment) objects. Подробнее: Текст pdf документа вPdf представлен двумя базовыми объектами:[`TextFragment`](../textfragment) а также[`TextSegment`](../textsegment) Различия между ними в основном зависят от контекста. Рассмотрим следующий сценарий. Пользователь ищет текст «hello world», чтобы работать с ним, изменять его свойства, смотреть и т. д. Физически представление текста в формате PDF очень сложное. Текст "hello world" может состоять из нескольких физически независимых текстовых сегментов. Текстовая модель Aspose.Pdf в основном устанавливает, что[`TextFragment`](../textfragment) object обеспечивает единую логическую операцию над физическим[`TextSegment`](../textsegment) набор объектов, представляющих запрос пользователя. В сценарии текстового поиска[`TextFragment`](../textfragment) является логическим текстовым представлением "hello world", и[`TextSegment`](../textsegment)коллекция объектов представляет все физические сегменты, из которых создается текстовый объект «hello world». Итак,[`TextFragment`](../textfragment) близко к логическому текстовому представлению. И[`TextSegment`](../textsegment) близко к физическому текстовому представлению. Очевидно, что каждый[`TextSegment`](../textsegment) объект может иметь свой собственный шрифт, цвет, свойства позиционирования. [`TextFragment`](../textfragment) предоставляет простой способ изменить текст с его свойствами: установить шрифт, установить размер шрифта, установить цвет шрифта и т. д. Между тем[`TextSegment`](../textsegment) объекты доступны, и пользователи могут работать с[`TextSegment`](../textsegment) объекты независимо друг от друга. Обратите внимание, что изменение свойств TextFragment может изменить внутренний[`Segments`](./segments) потому что TextFragment является совокупным объектом и может переупорядочивать внутренние сегменты или объединять их в один сегмент. Если вам нужно оставить[`Segments`](./segments)Коллекция без изменений, пожалуйста, меняйте внутренние сегменты по отдельности.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

### Примеры

Пример демонстрирует, как найти текст на первой странице документа PDF и заменить текст и его шрифт.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Находим шрифт, который будет использоваться для изменения шрифта текста документа
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Создаем объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Принять поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Изменяем текст и шрифт первого вхождения текста
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### Смотрите также

* class [BaseParagraph](../../aspose.pdf/baseparagraph)
* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
