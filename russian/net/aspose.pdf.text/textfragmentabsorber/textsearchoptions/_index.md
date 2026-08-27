---
title: "TextFragmentAbsorber.TextSearchOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство TextFragmentAbsorber. Получает или задает параметры поиска. Параметры позволяют выполнять поиск с использованием регулярных выражений."
type: docs
weight: 110
url: /ru/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## TextFragmentAbsorber.TextSearchOptions property

Получает или задает параметры поиска. Параметры позволяют выполнять поиск с использованием регулярных выражений.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## Примеры

Пример демонстрирует, как выполнять поиск текста с использованием регулярного выражения.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// заставьте поглотитель искать все слова, начинающиеся на «h» и заканчивающиеся на «o», используя регулярное выражение.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// Мы должны найти слово "hello" и заменить его на "Hi".
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf"); 
```

### См. также

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


