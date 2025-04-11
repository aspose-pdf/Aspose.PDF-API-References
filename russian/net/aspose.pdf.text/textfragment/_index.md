---
title: Class TextFragment
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Text.TextFragment. Представляет фрагмент текста Pdf
type: docs
weight: 10940
url: /ru/net/aspose.pdf.text/textfragment/
---
## Класс TextFragment

Представляет фрагмент текста Pdf.

```csharp
public class TextFragment : BaseParagraph
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | Инициализирует новый экземпляр объекта `TextFragment`. |
| [TextFragment](textfragment/#constructor_2)(string) | Создает объект `TextFragment` с одним объектом [`TextSegment`](../textsegment/) внутри. Указывает строку текста внутри сегмента. |
| [TextFragment](textfragment/#constructor_1)(TabStops) | Инициализирует новый экземпляр объекта `TextFragment` с предопределенными позициями [`TabStops`](../tabstops/). |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | Создает объект `TextFragment` с одним объектом [`TextSegment`](../textsegment/) внутри и предопределенными позициями [`TabStops`](../tabstops/). |

## Свойства

| Имя | Описание |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Получает позицию текста для текста, представленного объектом `TextFragment`. YIndent структуры Position представляет координату базовой линии текстового фрагмента. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Получает или устанавливает конец примечания абзаца. (только для генерации pdf) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Получает или устанавливает сноску абзаца. (только для генерации pdf) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Получает объект формы, который содержит TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Получает или устанавливает горизонтальное выравнивание текстового фрагмента. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Устанавливает гиперссылку фрагмента |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или устанавливает логическое значение, указывающее, будет ли этот абзац в следующем столбце. По умолчанию false. (для генерации pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или устанавливает, является ли абзац встроенным. По умолчанию false. (для генерации pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или устанавливает логическое значение, которое заставляет этот абзац генерироваться на новой странице. По умолчанию false. (для генерации pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или устанавливает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе с следующим абзацем. По умолчанию false. (для генерации pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или устанавливает внешний отступ для абзаца (для генерации pdf) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Получает страницу, которая содержит TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Получает или устанавливает позицию текста для текста, представленного объектом `TextFragment`. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Получает прямоугольник TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Получает параметры замены текста. Параметры определяют поведение при замене текста фрагмента на более короткий/длинный. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Получает текстовые сегменты для текущего `TextFragment`. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Получает или устанавливает объект строки текста, который представляет объект `TextFragment`. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Получает или устанавливает параметры редактирования текста. Параметры определяют специальное поведение, когда запрашиваемый символ не может быть записан шрифтом. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Получает или устанавливает состояние текста для текста, который представляет объект `TextFragment`. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Получает или устанавливает вертикальное выравнивание текстового фрагмента. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Получает или устанавливает количество обернутых строк для этого абзаца (только для генерации pdf) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или устанавливает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещен поверх графика с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен позади текста на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | Клонирует фрагмент. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | Клонирует фрагмент со всеми сегментами. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Получает [`TextSegment`](../textsegment/)(ы), представляющие указанную часть текста `TextFragment`. |

## Замечания

В нескольких словах, объект `TextFragment` содержит список объектов [`TextSegment`](../textsegment/). В деталях: текст pdf-документа в Pdf представлен двумя основными объектами: `TextFragment` и [`TextSegment`](../textsegment/). Различия между ними в основном зависят от контекста. Рассмотрим следующий сценарий. Пользователь ищет текст "hello world", чтобы работать с ним, изменять его свойства, просматривать и т.д.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Физическое представление текста pdf очень сложное. Текст "hello world" может состоять из нескольких физически независимых текстовых сегментов. Модель текста Aspose.Pdf в основном устанавливает, что объект `TextFragment` предоставляет единый набор логических операций над физическими объектами [`TextSegment`](../textsegment/), которые представляют запрос пользователя. В сценарии поиска текста `TextFragment` является логическим представлением текста "hello world", а коллекция объектов [`TextSegment`](../textsegment/) представляет все физические сегменты, которые составляют текстовый объект "hello world". Таким образом, `TextFragment` близок к логическому представлению текста. А [`TextSegment`](../textsegment/) близок к физическому представлению текста. Очевидно, что каждый объект [`TextSegment`](../textsegment/) может иметь свой собственный шрифт, цвет, свойства позиционирования. `TextFragment` предоставляет простой способ изменить текст с его свойствами: установить шрифт, установить размер шрифта, установить цвет шрифта и т.д. Тем временем объекты [`TextSegment`](../textsegment/) доступны, и пользователи могут работать с объектами [`TextSegment`](../textsegment/) независимо. Обратите внимание, что изменение свойств TextFragment может изменить внутреннюю коллекцию [`Segments`](./segments/), поскольку TextFragment является агрегатным объектом и может переставить внутренние сегменты или объединить их в один сегмент. Если ваше требование состоит в том, чтобы оставить коллекцию [`Segments`](./segments/) неизменной, пожалуйста, изменяйте внутренние сегменты индивидуально.

## Примеры

Пример демонстрирует, как найти текст на первой странице PDF-документа и заменить текст и его шрифт.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* класс [BaseParagraph](../../aspose.pdf/baseparagraph/)
* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)