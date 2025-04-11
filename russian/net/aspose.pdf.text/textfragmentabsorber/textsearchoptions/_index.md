---
title: TextFragmentAbsorber.TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: Свойство TextFragmentAbsorber. Получает или задает параметры поиска. Параметры позволяют выполнять поиск с использованием регулярных выражений
type: docs
weight: 110
url: /ru/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## Свойство TextFragmentAbsorber.TextSearchOptions

Получает или задает параметры поиска. Параметры позволяют выполнять поиск с использованием регулярных выражений.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## Примеры

Пример демонстрирует, как выполнить поиск текста с использованием регулярного выражения.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// make the absorber to search all words starting 'h' and ending 'o' using regular expression.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### См. также

* класс [TextSearchOptions](../../textsearchoptions/)
* класс [TextFragmentAbsorber](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)