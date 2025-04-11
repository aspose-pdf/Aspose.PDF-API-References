---
title: TextFragmentAbsorber.TextFragments
second_title: Aspose.PDF for .NET API Reference
description: Свойство TextFragmentAbsorber. Получает коллекцию поисковых вхождений, которые представлены объектами TextFragment
type: docs
weight: 90
url: /ru/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## Свойство TextFragmentAbsorber.TextFragments

Получает коллекцию поисковых вхождений, которые представлены объектами [`TextFragment`](../../textfragment/).

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## Примеры

Пример демонстрирует, как найти текст на первой странице PDF-документа и заменить все поисковые вхождения новым текстом.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* класс [TextFragmentCollection](../../textfragmentcollection/)
* класс [TextFragmentAbsorber](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)