---
title: Phrase
second_title: Aspose.PDF для справочника API .NET
description: Получает или задает фразу которуюTextFragmentAbsorberaspose.pdf.text/textfragmentabsorber поиск в документе PDF или на странице.
type: docs
weight: 50
url: /ru/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## TextFragmentAbsorber.Phrase property

Получает или задает фразу, которую[`TextFragmentAbsorber`](../../textfragmentabsorber) поиск в документе PDF или на странице.

```csharp
public string Phrase { get; set; }
```

### Примеры

В примере показано, как выполнить поиск текста несколько раз и выполнить замену текста.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создаем объект TextFragmentAbsorber для поиска всех вхождений текста "hello"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// ищем другое слово и заменяем его
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### Смотрите также

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* пространство имен [Aspose.Pdf.Text](../../textfragmentabsorber)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
