---
title: TextFragment.Segments
second_title: Aspose.PDF for .NET API Reference
description: TextFragment property. Gets text segments for current TextFragment
type: docs
weight: 120
url: /net/aspose.pdf.text/textfragment/segments/
---
## TextFragment.Segments property

Gets text segments for current [`TextFragment`](../).

```csharp
public TextSegmentCollection Segments { get; set; }
```

## Remarks

In a few words, [`TextSegment`](../../textsegment/) objects are children of [`TextFragment`](../) object. Advanced users may access segments directly to perform more complex text edit scenarios. For details, please look at [`TextFragment`](../) object description.

## Examples

The example demonstrates how to navigate all [`TextSegment`](../../textsegment/) objects inside [`TextFragment`](../).

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

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [TextSegmentCollection](../../textsegmentcollection/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


