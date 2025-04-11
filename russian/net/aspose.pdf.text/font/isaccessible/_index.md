---
title: Font.IsAccessible
second_title: Aspose.PDF for .NET API Reference
description: Свойство шрифта. Получает информацию о том, установлен ли шрифт в системе
type: docs
weight: 50
url: /ru/net/aspose.pdf.text/font/isaccessible/
---
## Свойство Font.IsAccessible

Получает информацию о том, установлен ли шрифт в системе.

```csharp
public bool IsAccessible { get; }
```

## Примечания

Некоторые операции недоступны для шрифтов, которые не были найдены в системе.

## Примеры

Пример демонстрирует, как искать текст на первой странице и получить значение, указывающее, установлен ли шрифт в системе.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### См. также

* класс [TextFragmentAbsorber](../../textfragmentabsorber/)
* класс [Document](../../../aspose.pdf/document/)
* класс [Font](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)