---
title: "Класс TextSegment"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Text.TextSegment. Представляет сегмент текста Pdf"
type: docs
weight: 11240
url: /ru/net/aspose.pdf.text/textsegment/
---
## TextSegment class

Представляет сегмент текста PDF.

```csharp
public sealed class TextSegment
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextSegment](textsegment/#constructor)() | Создает объект TextSegment. |
| [TextSegment](textsegment/#constructor_1)(string) | Создает объект TextSegment. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | Получает позицию текста, представленного объектом `TextSegment`. YIndent структуры Position представляет координату базовой линии текстового сегмента. |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | Получает коллекцию объектов CharInfo, представляющих информацию о символах в текстовом сегменте. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | Получает индекс конечного символа текущего сегмента в операторе отображения текста (Tj, TJ). |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | Получает или задает гиперссылку сегмента (для генератора pdf). |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | Получает позицию текста, представленного объектом `TextSegment`. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | Получает прямоугольник TextSegment. |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | Получает индекс начального символа текущего сегмента в операторе отображения текста (Tj, TJ). |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | Получает или задает объект String текста, который представляет объект `TextSegment`. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | Получает или задает параметры редактирования текста. Параметры определяют особое поведение, когда требуемый символ нельзя отобразить шрифтом. |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | Получает или задает состояние текста для текста, представленного объектом `TextSegment`. |

## Методы

| Имя | Описание |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | Кодирует строку как html. |

## Примечания

В нескольких словах, объекты `TextSegment` являются дочерними по отношению к объекту [`TextFragment`](../textfragment/). Подробно: текст PDF‑документа в Pdf представлен двумя базовыми объектами: [`TextFragment`](../textfragment/) и `TextSegment`. Различия между ними в основном зависят от контекста. Рассмотрим следующую ситуацию. Пользователь ищет текст "hello world", чтобы работать с ним, изменять его свойства, просматривать и т.д.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Физическое представление текста pdf очень сложное. Текст "hello world" может состоять из нескольких физически независимых текстовых сегментов. Модель текста Aspose.Pdf в основном устанавливает, что объект [`TextFragment`](../textfragment/) предоставляет единый логический набор операций над набором физических объектов `TextSegment`, представляющих запрос пользователя. В сценарии поиска текста объект [`TextFragment`](../textfragment/) является логическим представлением текста "hello world", а коллекция объектов `TextSegment` представляет все физические сегменты, составляющие объект текста "hello world". Таким образом, [`TextFragment`](../textfragment/) близок к логическому представлению текста, а `TextSegment` — к физическому представлению текста. Очевидно, каждый объект `TextSegment` может иметь собственный шрифт, цвет и свойства позиционирования. [`TextFragment`](../textfragment/) предоставляет простой способ изменить текст и его свойства: задать шрифт, размер шрифта, цвет шрифта и т.д. При этом объекты `TextSegment` доступны, и пользователи могут работать с объектами `TextSegment` независимо.

## Примеры

Пример демонстрирует, как изменить цвет текста и размер шрифта текста с помощью объекта [`TextState`](./textstate/) объекта `TextSegment`.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Изменить цвет переднего плана первого текстового сегмента первого вхождения текста
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Изменить размер шрифта первого текстового сегмента первого вхождения текста
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


