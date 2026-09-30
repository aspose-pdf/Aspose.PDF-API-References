---
title: "TextFragment.Segments"
linktitle: "Segments"
articleTitle: "Segments"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextFragment property. Gets text segments for current TextFragment."
type: docs
weight: 140
url: "/net/aspose.pdf.text/textfragment/segments/"
product_version: "26.9.0"
---
## TextFragment.Segments property

Gets text segments for current [`TextFragment`](../../../aspose.pdf.text/textfragment/).

In a few words, [`TextSegment`](../../../aspose.pdf.text/textsegment/) objects are children of [`TextFragment`](../../../aspose.pdf.text/textfragment/) object.
 Advanced users may access segments directly to perform more complex text edit scenarios.
 For details, please look at [`TextFragment`](../../../aspose.pdf.text/textfragment/) object description.

```csharp
public TextSegmentCollection Segments { get; set; }
```

## Examples

The example demonstrates how to navigate all [`TextSegment`](../../../aspose.pdf.text/textsegment/) objects inside [`TextFragment`](../../../aspose.pdf.text/textfragment/).

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Navigate all text segments and out their text and placement info
foreach (TextSegment segment in absorber.TextFragments[1].Segments)
{
    Console.Out.WriteLine(string.Format("segment text: {0}", segment.Text));
    Console.Out.WriteLine(string.Format("segment X indent: {0}", segment.Position.XIndent));
    Console.Out.WriteLine(string.Format("segment Y indent: {0}", segment.Position.YIndent));
}
```

### See Also

* [TextFragmentAbsorber](../textfragmentabsorber/)
* [Document](../document/)
* [TextSegment](../textsegment/)
* class [TextSegmentCollection](../../../aspose.pdf.text/textsegmentcollection/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

