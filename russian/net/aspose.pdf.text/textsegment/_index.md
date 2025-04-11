---
title: Class TextSegment
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Text.TextSegment. Представляет сегмент текста Pdf
type: docs
weight: 11050
url: /ru/net/aspose.pdf.text/textsegment/
---
## Класс TextSegment

Представляет сегмент текста Pdf.

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
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | Получает позицию текста для текста, представленного объектом `TextSegment`. YIndent структуры Position представляет базовую координату сегмента текста. |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | Получает коллекцию объектов CharInfo, которые представляют информацию о символах в сегменте текста. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | Получает конечный индекс символа текущего сегмента в операторе отображения текста (Tj, TJ). |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | Получает или устанавливает гиперссылку сегмента (для генератора pdf). |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | Получает позицию текста для текста, представленного объектом `TextSegment`. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | Получает прямоугольник сегмента TextSegment |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | Получает начальный индекс символа текущего сегмента в операторе отображения текста (Tj, TJ). |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | Получает или устанавливает объект строки текста, который представляет объект `TextSegment`. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | Получает или устанавливает параметры редактирования текста. Параметры определяют специальное поведение, когда запрашиваемый символ не может быть записан шрифтом. |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | Получает или устанавливает состояние текста для текста, который представляет объект `TextSegment`. |

## Методы

| Имя | Описание |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | Кодирует строку как html. |

## Замечания

В нескольких словах, объекты `TextSegment` являются дочерними элементами объекта [`TextFragment`](../textfragment/). Подробно: Текст pdf-документа в Pdf представлен двумя основными объектами: [`TextFragment`](../textfragment/) и `TextSegment`. Различия между ними в основном зависят от контекста. Рассмотрим следующий сценарий. Пользователь ищет текст "hello world", чтобы работать с ним, изменять его свойства, просматривать и т.д.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Физическое представление текста pdf очень сложное. Текст "hello world" может состоять из нескольких физически независимых сегментов текста. Модель текста Aspose.Pdf в основном устанавливает, что объект [`TextFragment`](../textfragment/) предоставляет единый набор логических операций над набором физических объектов `TextSegment`, которые представляют запрос пользователя. В сценарии поиска текста объект [`TextFragment`](../textfragment/) является логическим представлением текста "hello world", а коллекция объектов `TextSegment` представляет все физические сегменты, которые составляют объект текста "hello world". Таким образом, [`TextFragment`](../textfragment/) близок к логическому представлению текста. А `TextSegment` близок к физическому представлению текста. Очевидно, что каждый объект `TextSegment` может иметь свой собственный шрифт, цвет, свойства позиционирования. [`TextFragment`](../textfragment/) предоставляет простой способ изменить текст с его свойствами: установить шрифт, установить размер шрифта, установить цвет шрифта и т.д. Тем временем объекты `TextSegment` доступны, и пользователи могут работать с объектами `TextSegment` независимо.

## Примеры

Пример демонстрирует, как изменить цвет текста и размер шрифта текста с помощью объекта [`TextState`](./textstate/) объекта `TextSegment`.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)