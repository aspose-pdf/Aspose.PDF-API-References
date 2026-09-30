---
title: "TextFragmentAbsorber.Phrase"
linktitle: "Phrase"
articleTitle: "Phrase"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextFragmentAbsorber property. Gets or sets phrase that the TextFragmentAbsorber searches on the PDF document or page."
type: docs
weight: 230
url: "/net/aspose.pdf.text/textfragmentabsorber/phrase/"
product_version: "26.9.0"
---
## TextFragmentAbsorber.Phrase property

Gets or sets phrase that the [`TextFragmentAbsorber`](../../../aspose.pdf.text/textfragmentabsorber/) searches on the PDF document or page.

```csharp
public string Phrase { get; set; }
```

## Examples

The example demonstrates how to perform search text several times and perform text replacements.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// search another word and replace it
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### See Also

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

