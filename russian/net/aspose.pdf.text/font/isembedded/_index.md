---
title: Font.IsEmbedded
second_title: Aspose.PDF for .NET API Reference
description: Свойство шрифта. Получает или устанавливает значение, указывающее, встроен ли шрифт. Шрифт на основе IFont будет автоматически подмножен и встроен
type: docs
weight: 60
url: /ru/net/aspose.pdf.text/font/isembedded/
---
## Свойство Font.IsEmbedded

Получает или устанавливает значение, указывающее, встроен ли шрифт. Шрифт на основе IFont будет автоматически подмножен и встроен

```csharp
public bool IsEmbedded { get; set; }
```

## Примеры

Следующий пример демонстрирует, как найти шрифт, отметить его как встроенный, искать текст на странице документа и заменить шрифт текста.

```csharp
// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// open document
Document doc = new Document(@"D:\Tests\input.pdf");

// create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// change font for the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### См. также

* класс [TextFragmentAbsorber](../../textfragmentabsorber/)
* класс [FontRepository](../../fontrepository/)
* класс [Document](../../../aspose.pdf/document/)
* класс [Font](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)