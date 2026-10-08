---
title: "TextFragment.Text"
linktitle: "Text"
articleTitle: "Text"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextFragment property. Gets or sets String text object that the TextFragment object represents."
type: docs
weight: 90
url: "/net/aspose.pdf.text/textfragment/text/"
product_version: "26.9"
---
## TextFragment.Text property

Gets or sets `String` text object that the [`TextFragment`](../) object represents.

```csharp
public string Text { get; set; }
```

## Examples

The example demonstrates how to search a text and replace first occurrence represented with [`TextFragment`](../../../aspose.pdf.text/textfragment/) object .

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### See Also

* [TextFragmentAbsorber](../textfragmentabsorber/)
* [Document](../document/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

