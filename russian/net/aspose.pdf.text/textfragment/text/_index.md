---
title: TextFragment.Text
second_title: Aspose.PDF for .NET API Reference
description: Свойство TextFragment. Получает или задает объект строки текста, который представляет объект TextFragment
type: docs
weight: 130
url: /ru/net/aspose.pdf.text/textfragment/text/
---
## Свойство TextFragment.Text

Получает или задает объект строки текста, который представляет [`TextFragment`](../) объект.

```csharp
public string Text { get; set; }
```

## Примеры

Пример демонстрирует, как искать текст и заменять первое вхождение, представленное объектом [`TextFragment`](../).

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### См. также

* класс [TextFragmentAbsorber](../../textfragmentabsorber/)
* класс [Document](../../../aspose.pdf/document/)
* класс [TextFragment](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)