---
title: TextSegment
second_title: Aspose.PDF для справочника API .NET
description: Представляет сегмент текста Pdf.
type: docs
weight: 7210
url: /ru/net/aspose.pdf.text/textsegment/
---
## TextSegment class

Представляет сегмент текста Pdf.

```csharp
public sealed class TextSegment
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextSegment](textsegment#constructor)() | Создает объект TextSegment. |
| [TextSegment](textsegment#constructor_1)(string) | Создает объект TextSegment. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition) { get; set; } | Получает текстовую позицию для текста, представленного с помощью[`TextSegment`](../textsegment) object. YIndent структуры Position представляет базовую координату текстового сегмента. |
| [Characters](../../aspose.pdf.text/textsegment/characters) { get; } | Получает коллекцию объектов CharInfo, представляющих информацию о символах в текстовом сегменте. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex) { get; } | Получает индекс конечного символа текущего сегмента в сегменте оператора отображения текста (Tj, TJ). |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink) { get; set; } | Получает или задает гиперссылку сегмента (для генератора pdf). |
| [Position](../../aspose.pdf.text/textsegment/position) { get; set; } | Получает текстовую позицию для текста, представленного с помощью[`TextSegment`](../textsegment) объект. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle) { get; } | Получает прямоугольник TextSegment |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex) { get; } | Получает индекс начального символа текущего сегмента в сегменте оператора отображения текста (Tj, TJ). |
| [Text](../../aspose.pdf.text/textsegment/text) { get; set; } | Получает или устанавливаетString текстовый объект, который[`TextSegment`](../textsegment) объект представляет. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions) { get; set; } | Получает или задает параметры редактирования текста. Параметры определяют особое поведение, когда запрошенный символ не может быть написан шрифтом. |
| [TextState](../../aspose.pdf.text/textsegment/textstate) { get; set; } | Получает или задает состояние текста для текста,[`TextSegment`](../textsegment) объект представляет. |

## Методы

| Имя | Описание |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode)(string) | Кодирует строку как html. |

### Примечания

В двух словах,[`TextSegment`](../textsegment) объекты являются детьми[`TextFragment`](../textfragment) object. Подробнее: Текст pdf документа вPdf представлен двумя базовыми объектами:[`TextFragment`](../textfragment) а также[`TextSegment`](../textsegment) Различия между ними в основном зависят от контекста. Рассмотрим следующий сценарий. Пользователь ищет текст «hello world», чтобы работать с ним, изменять его свойства, смотреть и т. д. Физически представление текста в формате PDF очень сложное. Текст "hello world" может состоять из нескольких физически независимых текстовых сегментов. Текстовая модель Aspose.Pdf в основном устанавливает, что[`TextFragment`](../textfragment) object обеспечивает единую логическую операцию над физическим[`TextSegment`](../textsegment) набор объектов, представляющих запрос пользователя. В сценарии текстового поиска[`TextFragment`](../textfragment) является логическим текстовым представлением "hello world", и[`TextSegment`](../textsegment)коллекция объектов представляет все физические сегменты, из которых создается текстовый объект «hello world». Итак,[`TextFragment`](../textfragment) близко к логическому текстовому представлению. И[`TextSegment`](../textsegment) близко к физическому текстовому представлению. Очевидно, что каждый[`TextSegment`](../textsegment) объект может иметь свой собственный шрифт, цвет, свойства позиционирования. [`TextFragment`](../textfragment) предоставляет простой способ изменить текст с его свойствами: установить шрифт, установить размер шрифта, установить цвет шрифта и т. д. Между тем[`TextSegment`](../textsegment) объекты доступны, и пользователи могут работать с[`TextSegment`](../textsegment) объекты независимо друг от друга.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

### Примеры

Пример демонстрирует, как изменить цвет текста и размер шрифта текста с помощью[`TextState`](./textstate) объект[`TextSegment`](../textsegment) объект.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создаем объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Принять поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Изменяем цвет переднего плана первого текстового сегмента первого вхождения текста
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Изменяем размер шрифта первого сегмента текста первого вхождения текста
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### Смотрите также

* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
