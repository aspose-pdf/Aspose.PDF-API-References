---
title: Font.FontName
second_title: Aspose.PDF for .NET API Reference
description: Font property. Gets font name of the Font object
type: docs
weight: 30
url: /net/aspose.pdf.text/font/fontname/
---
## Font.FontName property

Gets font name of the [`Font`](../) object.

```csharp
public string FontName { get; }
```

## Examples

The example demonstrates how to search text on first page and view font name of a first text occurrence.

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

### See Also

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


