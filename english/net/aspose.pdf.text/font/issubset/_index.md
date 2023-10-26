---
title: Font.IsSubset
second_title: Aspose.PDF for .NET API Reference
description: Font property. Gets or sets a value that indicates whether the font is a subset. Font based on IFont will automatically be subset and embedded
type: docs
weight: 70
url: /net/aspose.pdf.text/font/issubset/
---
## Font.IsSubset property

Gets or sets a value that indicates whether the font is a subset. Font based on IFont will automatically be subset and embedded

```csharp
public bool IsSubset { get; set; }
```

## Examples

The example demonstrates how to search text on first page and get the value that indicates whether the font is a subset.

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

### See Also

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


