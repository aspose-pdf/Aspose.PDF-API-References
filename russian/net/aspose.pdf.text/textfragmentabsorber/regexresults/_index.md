---
title: TextFragmentAbsorber.RegexResults
second_title: Aspose.PDF for .NET API Reference
description: Свойство TextFragmentAbsorber. Получает словарь поисковых вхождений, которые представлены классом System.Text.RegularExpressions.Regex в качестве ключа и TextFragment в качестве значения
type: docs
weight: 60
url: /ru/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## Свойство TextFragmentAbsorber.RegexResults

Получает словарь поисковых вхождений, которые представлены классом System.Text.RegularExpressions.Regex в качестве ключа и [`TextFragment`](../../textfragment/) в качестве значения.

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## Примеры

Пример демонстрирует, как найти текст с помощью массива регулярных выражений на первой странице PDF-документа.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Get results
var results = absorber.RegexResults;
```

### См. также

* класс [TextFragmentCollection](../../textfragmentcollection/)
* класс [TextFragmentAbsorber](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)