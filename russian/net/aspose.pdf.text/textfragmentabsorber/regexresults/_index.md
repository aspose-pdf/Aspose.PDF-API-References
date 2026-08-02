---
title: "TextFragmentAbsorber.RegexResults"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство TextFragmentAbsorber. Получает словарь поисковых вхождений, где ключом является класс System.Text.RegularExpressions.Regex, а значением — TextFragment."
type: docs
weight: 60
url: /ru/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## TextFragmentAbsorber.RegexResults property

Получает словарь поисковых вхождений, где ключом является класс System.Text.RegularExpressions.Regex, а значением — [`TextFragment`](../../textfragment/).

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## Примеры

В примере демонстрируется, как найти текст с помощью массива регулярных выражений на первой странице PDF‑документа.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Создайте объект TextFragmentAbsorber, который ищет все слова, начинающиеся на 'h' и заканчивающиеся на 'o', используя регулярное выражение.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Получить результаты
var results = absorber.RegexResults;
```

### См. также

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


