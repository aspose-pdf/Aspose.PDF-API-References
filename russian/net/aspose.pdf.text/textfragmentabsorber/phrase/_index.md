---
title: TextFragmentAbsorber.Phrase
second_title: Aspose.PDF for .NET API Reference
description: Свойство TextFragmentAbsorber. Получает или устанавливает фразу, которую TextFragmentAbsorber ищет в PDF-документе или на странице
type: docs
weight: 50
url: /ru/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## Свойство TextFragmentAbsorber.Phrase

Получает или устанавливает фразу, которую [`TextFragmentAbsorber`](../) ищет в PDF-документе или на странице.

```csharp
public string Phrase { get; set; }
```

## Примеры

Пример демонстрирует, как выполнять поиск текста несколько раз и выполнять замены текста.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// search another word and replace it
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* класс [TextFragmentAbsorber](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)