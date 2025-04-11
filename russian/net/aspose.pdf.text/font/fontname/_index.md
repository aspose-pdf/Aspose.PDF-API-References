---
title: Font.FontName
second_title: Aspose.PDF for .NET API Reference
description: Свойство шрифта. Получает имя шрифта объекта Font
type: docs
weight: 30
url: /ru/net/aspose.pdf.text/font/fontname/
---
## Свойство Font.FontName

Получает имя шрифта объекта [`Font`](../).

```csharp
public string FontName { get; }
```

## Примеры

Пример демонстрирует, как искать текст на первой странице и просматривать имя шрифта первого вхождения текста.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font name of first text occurrence
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### См. также

* класс [TextFragmentAbsorber](../../textfragmentabsorber/)
* класс [Document](../../../aspose.pdf/document/)
* класс [Font](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)