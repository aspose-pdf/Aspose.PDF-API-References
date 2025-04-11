---
title: TextFragment.Segments
second_title: Aspose.PDF for .NET API Reference
description: Свойство TextFragment. Получает текстовые сегменты для текущего TextFragment
type: docs
weight: 120
url: /ru/net/aspose.pdf.text/textfragment/segments/
---
## Свойство TextFragment.Segments

Получает текстовые сегменты для текущего [`TextFragment`](../).

```csharp
public TextSegmentCollection Segments { get; set; }
```

## Примечания

В нескольких словах, объекты [`TextSegment`](../../textsegment/) являются дочерними элементами объекта [`TextFragment`](../). Продвинутые пользователи могут получить доступ к сегментам напрямую для выполнения более сложных сценариев редактирования текста. Для получения подробной информации, пожалуйста, посмотрите описание объекта [`TextFragment`](../).

## Примеры

Пример демонстрирует, как пройтись по всем объектам [`TextSegment`](../../textsegment/) внутри [`TextFragment`](../).

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Navigate all text segments and out their text and placement info
foreach (TextSegment segment in absorber.TextFragments[1].Segments)
{
    Console.Out.WriteLine(string.Format("segment text: {0}", segment.Text));
    Console.Out.WriteLine(string.Format("segment X indent: {0}", segment.Position.XIndent));
    Console.Out.WriteLine(string.Format("segment Y indent: {0}", segment.Position.YIndent));
}

```

### См. также

* класс [TextFragmentAbsorber](../../textfragmentabsorber/)
* класс [Document](../../../aspose.pdf/document/)
* класс [TextSegment](../../textsegment/)
* класс [TextSegmentCollection](../../textsegmentcollection/)
* класс [TextFragment](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)