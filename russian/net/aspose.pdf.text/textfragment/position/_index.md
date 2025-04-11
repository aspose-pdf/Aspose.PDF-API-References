---
title: TextFragment.Position
second_title: Aspose.PDF for .NET API Reference
description: Свойство TextFragment. Получает или устанавливает позицию текста для текста, представленного объектом TextFragment
type: docs
weight: 90
url: /ru/net/aspose.pdf.text/textfragment/position/
---
## Свойство TextFragment.Position

Получает или устанавливает позицию текста для текста, представленного объектом [`TextFragment`](../).

```csharp
public Position Position { get; set; }
```

## Примеры

Пример демонстрирует, как просмотреть размещение текста, представленного объектом [`TextFragment`](../).

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View text and placement info of first text occurrence
TextFragment firstOccurrence = absorber.TextFragments[1];

Console.Out.WriteLine(string.Format("fragment text: {0}", firstOccurrence.Text));
Console.Out.WriteLine(string.Format("fragment X indent: {0}", firstOccurrence.Position.XIndent));
Console.Out.WriteLine(string.Format("fragment Y indent: {0}", firstOccurrence.Position.YIndent));

```

### См. также

* класс [TextFragmentAbsorber](../../textfragmentabsorber/)
* класс [Document](../../../aspose.pdf/document/)
* класс [TextSegment](../../textsegment/)
* класс [Position](../../position/)
* класс [TextFragment](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)