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
| [TextFragment](textfragment#constructor)() | Инициализирует новый экземпляр объекта[`TextFragment`](../textfragment). |
| [TextFragment](textfragment#constructor_2)(string) | Создает[`TextFragment`](../textfragment)объект с одним[`TextSegment`](../textsegment)объект внутри. Задает текстовую строку внутри сегмента. |
| [TextFragment](textfragment#constructor_1)(TabStops) | Инициализирует новый экземпляр объекта[`TextFragment`](../textfragment)с предопределенным[`TabStops`](../tabstops)позиции. |
| [TextFragment](textfragment#constructor_3)(string, TabStops) | Создает[`TextFragment`](../textfragment)объект с одним[`TextSegment`](../textsegment)объект внутри и предопределенные позиции[`TabStops`](../tabstops). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition) { get; set; } | Получает текстовую позицию для текста, представленного с помощью объекта[`TextFragment`](../textfragment). YIndent структуры Position представляет базовую координату текстового фрагмента. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote) { get; set; } | Получает или задает примечание в конце абзаца. (только для создания pdf) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote) { get; set; } | Получает или устанавливает сноску к абзацу. (только для генерации PDF) |
| [Form](../../aspose.pdf.text/textfragment/form) { get; } | Получает объект формы, который содержит TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment) { get; set; } | Получает или задает горизонтальное выравнивание фрагмента текста. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink) { set; } | Устанавливает гиперссылку фрагмента |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующем столбце. По умолчанию false. (для генерации pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Получает или задает встроенный абзац. По умолчанию false. (для генерации pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Получает или устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. По умолчанию false. (для генерации pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Получает или задает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. По умолчанию false. (для генерации pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Получает или задает внешнее поле для абзаца (для создания pdf) |
| [Page](../../aspose.pdf.text/textfragment/page) { get; } | Получает страницу, содержащую TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position) { get; set; } | Получает или задает позицию текста для текста, представленного объектом[`TextFragment`](../textfragment). |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle) { get; } | Получает прямоугольник TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions) { get; } | Получает параметры замены текста. Опции определяют поведение при замене текста фрагмента на более короткий/длинный. |
| [Segments](../../aspose.pdf.text/textfragment/segments) { get; set; } | Получает текстовые сегменты для текущего[`TextFragment`](../textfragment). |
| [Text](../../aspose.pdf.text/textfragment/text) { get; set; } | Получает или устанавливаетStringтекстовый объект, который[`TextFragment`](../textfragment)объект представляет. |
| [TextState](../../aspose.pdf.text/textfragment/textstate) { get; } | Получает или задает состояние текста для текста, который представляет объект[`TextFragment`](../textfragment). |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment) { get; set; } | Получает или задает вертикальное выравнивание фрагмента текста. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount) { get; set; } | Получает или устанавливает количество строк переноса для этого абзаца (только для генерации PDF) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Получает или задает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone)() | Клонировать фрагмент. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments)() | Клонировать фрагмент со всеми сегментами. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments)(int, int) | Получает[`TextSegment`](../textsegment)(s), представляющий указанную часть[`TextFragment`](../textfragment)текст. |

### Примечания

В нескольких словах,[`TextFragment`](../textfragment)объект содержит список объектов[`TextSegment`](../textsegment). Подробнее: Текст pdf документа вPdfпредставлен двумя базовыми объектами:[`TextFragment`](../textfragment)и[`TextSegment`](../textsegment) Различия между ними в основном зависит от контекста. Рассмотрим следующий сценарий. Пользователь ищет текст «hello world», чтобы работать с ним, изменять его свойства, смотреть и т. д. &lt;code&gt; Document doc = new Document(docFile); Поглотитель TextFragmentAbsorber = новый TextFragmentAbsorber ("привет, мир"); doc.Pages[1].Accept(абсорбер); &lt;/code&gt; Физически представление текста в формате PDF очень сложное. Текст "hello world" может состоять из нескольких физически независимых текстовых сегментов. Текстовая модель Aspose.Pdf в основном устанавливает, что[`TextFragment`](../textfragment)объект предоставляет один набор логических операций над набором физических[`TextSegment`](../textsegment)объектов, представляющих запрос пользователя. В сценарии текстового поиска[`TextFragment`](../textfragment)является логическим текстовым представлением "hello world", Коллекция объектови[`TextSegment`](../textsegment)представляет все физические сегменты, которые создают текстовый объект "hello world". Итак,[`TextFragment`](../textfragment)близок к логическому текстовому представлению. И[`TextSegment`](../textsegment)близок к физическому текстовому представлению. Очевидно, что каждый объект[`TextSegment`](../textsegment)может иметь свой собственный шрифт, цвет, свойства позиционирования. [`TextFragment`](../textfragment)предоставляет простой способ изменить текст с его свойствами:установить шрифт, установить размер шрифта, установить шрифт цвет и т.д. Тем временем[`TextSegment`](../textsegment)объекты доступны и пользователи могут работать с[`TextSegment`](../textsegment)объекты независимо друг от друга. Обратите внимание, что изменение свойств TextFragment может изменить внутреннюю[`Segments`](./segments)коллекцию, поскольку TextFragment является совокупным объектом и он может переставлять внутренние сегменты или объединять их в один сегмент. Если вы хотите оставить коллекцию[`Segments`](./segments)неизменной, измените внутренние сегменты по отдельности.

### Примеры

Пример демонстрирует, как найти текст на первой странице документа PDF и заменить текст и его шрифт .

```csharp
// Открыть документ
ocument doc = new Document(@"D:\Tests\input.pdf");

// Находим шрифт, который будет использоваться для изменения текста документа font
spose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Создаем объект TextFragmentAbsorber для поиска всех вхождений текста «hello world»
extFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Принять поглотитель для первой страницы
oc.Pages[1].Accept(absorber);

// Изменяем текст и шрифт первого текста вхождения
bsorber.TextFragments[1].Text = "hi world";
bsorber.TextFragments[1].TextState.Font = font;

// Сохранить документ
oc.Save(@"D:\Tests\output.pdf");  
```

### Смотрите также

* class [BaseParagraph](../../aspose.pdf/baseparagraph)
* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
