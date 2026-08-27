---
title: "Класс TextFragment"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Text.TextFragment. Представляет фрагмент текста Pdf"
type: docs
weight: 11120
url: /ru/net/aspose.pdf.text/textfragment/
---
## TextFragment class

Представляет фрагмент текста PDF.

```csharp
public class TextFragment : BaseParagraph
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | Инициализирует новый экземпляр объекта `TextFragment`. |
| [TextFragment](textfragment/#constructor_2)(string) | Создает объект `TextFragment` с одним вложенным объектом [`TextSegment`](../textsegment/). Указывает строку текста внутри сегмента. |
| [TextFragment](textfragment/#constructor_1)(TabStops) | Инициализирует новый экземпляр объекта `TextFragment` с предопределенными позициями [`TabStops`](../tabstops/). |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | Создает объект `TextFragment` с одним вложенным объектом [`TextSegment`](../textsegment/) и предопределенными позициями [`TabStops`](../tabstops/). |

## Свойства

| Имя | Описание |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Получает позицию текста, представленного объектом `TextFragment`. Поле YIndent структуры Position представляет координату базовой линии фрагмента текста. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Получает или задает конец абзаца (только для генерации PDF). |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Получает или задает сноску абзаца (только для генерации PDF). |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Получает объект формы, содержащий `TextFragment`. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Получает или задает горизонтальное выравнивание фрагмента текста. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Устанавливает гиперссылку фрагмента. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующей колонке. По умолчанию false. (для pdf‑генерации) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или задает, является ли абзац встроенным. По умолчанию false. (для pdf‑генерации) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или задает логическое значение, принуждающее этот абзац генерироваться на новой Page. По умолчанию false. (для pdf‑генерации) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или задает логическое значение, указывающее, остаётся ли текущий абзац на той же Page вместе со следующим абзацем. По умолчанию false. (для pdf‑генерации) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или задает внешний отступ для абзаца (для генерации PDF) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Получает страницу, содержащую `TextFragment`. |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Получает или задает позицию текста, представленного объектом `TextFragment`. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Получает прямоугольник `TextFragment`. |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Получает параметры замены текста. Параметры определяют поведение при замене текста фрагмента на более короткий/длинный. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Получает текстовые сегменты текущего `TextFragment`. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Получает или задает объект строки текста, который представляет объект `TextFragment`. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Получает или задает параметры редактирования текста. Параметры определяют особое поведение, когда требуемый символ нельзя отобразить шрифтом. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Получает или задает состояние текста для текста, представленного объектом `TextFragment`. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание фрагмента текста. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Получает или задает количество строк переноса для этого абзаца (только для генерации PDF). |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещён над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещён позади текста на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | Клонирует фрагмент. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | Клонирует фрагмент со всеми сегментами. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Получает [`TextSegment`](../textsegment/), представляющие указанную часть текста `TextFragment`. |

## Примечания

В нескольких словах, объект `TextFragment` содержит список объектов [`TextSegment`](../textsegment/). Подробно: текст PDF‑документа в Pdf представляется двумя базовыми объектами: `TextFragment` и [`TextSegment`](../textsegment/). Различия между ними в основном зависят от контекста. Рассмотрим следующую ситуацию. Пользователь ищет текст \"hello world\" для работы с ним, изменения его свойств, просмотра и т.д.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Физическое представление текста PDF очень сложное. Текст \"hello world\" может состоять из нескольких физически независимых текстовых сегментов. Текстовая модель Aspose.Pdf в основном устанавливает, что объект `TextFragment` предоставляет единый логический набор операций над физическими объектами [`TextSegment`](../textsegment/), представляющими запрос пользователя. В сценарии поиска текста `TextFragment` является логическим представлением текста \"hello world\", а коллекция объектов [`TextSegment`](../textsegment/) представляет все физические сегменты, из которых состоит объект текста \"hello world\". Таким образом, `TextFragment` близок к логическому представлению текста, а [`TextSegment`](../textsegment/) — к физическому представлению текста. Очевидно, каждый объект [`TextSegment`](../textsegment/) может иметь собственный шрифт, цвет, свойства позиционирования. `TextFragment` предоставляет простой способ изменить текст вместе с его свойствами: установить шрифт, размер шрифта, цвет шрифта и т.д. При этом объекты [`TextSegment`](../textsegment/) доступны, и пользователи могут работать с ними независимо. Обратите внимание, что изменение свойств `TextFragment` может изменить внутреннюю коллекцию [`Segments`](./segments/), поскольку `TextFragment` является агрегатным объектом и может перестраивать внутренние сегменты или объединять их в один сегмент. Если требуется оставить коллекцию [`Segments`](./segments/) без изменений, изменяйте внутренние сегменты по отдельности.

## Примеры

Пример демонстрирует, как найти текст на первой странице PDF‑документа и заменить текст и его шрифт.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Найдите шрифт, который будет использоваться для изменения шрифта текста документа
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Создайте объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Измените текст и шрифт первого вхождения текста
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


