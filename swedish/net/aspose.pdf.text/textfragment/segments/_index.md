---
title: TextFragment.Segments
second_title: Aspose.PDF for .NET API Reference
description: TextFragment-egenskap. Hämtar textsegment för nuvarande TextFragment
type: docs
weight: 120
url: /sv/net/aspose.pdf.text/textfragment/segments/
---
## TextFragment.Segments-egenskap

Hämtar textsegment för nuvarande [`TextFragment`](../).

```csharp
public TextSegmentCollection Segments { get; set; }
```

## Kommentarer

Med några få ord är [`TextSegment`](../../textsegment/) objekt barn till [`TextFragment`](../) objekt. Avancerade användare kan få tillgång till segment direkt för att utföra mer komplexa textredigeringsscenarier. För detaljer, vänligen se beskrivningen av [`TextFragment`](../) objektet.

## Exempel

Exemplet visar hur man navigerar alla [`TextSegment`](../../textsegment/) objekt inuti [`TextFragment`](../).

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

### Se Även

* klass [TextFragmentAbsorber](../../textfragmentabsorber/)
* klass [Document](../../../aspose.pdf/document/)
* klass [TextSegment](../../textsegment/)
* klass [TextSegmentCollection](../../textsegmentcollection/)
* klass [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)