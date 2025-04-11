---
title: TextFragment.Position
second_title: Aspose.PDF for .NET API Reference
description: TextFragment-egenskap. Hämtar eller ställer in textposition för text som representeras med TextFragment-objekt
type: docs
weight: 90
url: /sv/net/aspose.pdf.text/textfragment/position/
---
## TextFragment.Position-egenskap

Hämtar eller ställer in textposition för text, representerad med [`TextFragment`](../) objekt.

```csharp
public Position Position { get; set; }
```

## Exempel

Exemplet visar hur man ser placeringen av en text, representerad av [`TextFragment`](../) objekt.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View text and placement info of first text occurrence
TextFragment firstOccurrence = absorber.TextFragments[1];

Console.Out.WriteLine(string.Format("fragment text: {0}", firstOccurrence.Text));
Console.Out.WriteLine(string.Format("fragment X indent: {0}", firstOccurrence.Position.XIndent));
Console.Out.WriteLine(string.Format("fragment Y indent: {0}", firstOccurrence.Position.YIndent));

```

### Se Även

* klass [TextFragmentAbsorber](../../textfragmentabsorber/)
* klass [Document](../../../aspose.pdf/document/)
* klass [TextSegment](../../textsegment/)
* klass [Position](../../position/)
* klass [TextFragment](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)