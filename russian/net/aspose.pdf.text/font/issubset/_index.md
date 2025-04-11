---
title: Font.IsSubset
second_title: Aspose.PDF for .NET API Reference
description: Свойство шрифта. Получает или устанавливает значение, указывающее, является ли шрифт подмножеством. Шрифт на основе IFont будет автоматически подмножеством и встроенным
type: docs
weight: 70
url: /ru/net/aspose.pdf.text/font/issubset/
---
## Свойство Font.IsSubset

Получает или устанавливает значение, указывающее, является ли шрифт подмножеством. Шрифт на основе IFont будет автоматически подмножеством и встроенным

```csharp
public bool IsSubset { get; set; }
```

## Примеры

Пример демонстрирует, как искать текст на первой странице и получить значение, указывающее, является ли шрифт подмножеством.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### См. также

* класс [TextFragmentAbsorber](../../textfragmentabsorber/)
* класс [Document](../../../aspose.pdf/document/)
* класс [Font](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)