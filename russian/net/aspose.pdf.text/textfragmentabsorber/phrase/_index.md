---
title: "TextFragmentAbsorber.Phrase"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство TextFragmentAbsorber. Получает или задает фразу, которую TextFragmentAbsorber ищет в документе PDF или на странице."
type: docs
weight: 50
url: /ru/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## TextFragmentAbsorber.Phrase property

Получает или задает фразу, которую [`TextFragmentAbsorber`](../) ищет в документе PDF или на странице.

```csharp
public string Phrase { get; set; }
```

## Примеры

Пример демонстрирует, как выполнять поиск текста несколько раз и выполнять замену текста.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TextFragmentAbsorber, чтобы найти все вхождения текста "hello"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// найдите другое слово и замените его
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


