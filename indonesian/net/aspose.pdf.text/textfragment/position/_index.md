---
title: TextFragment.Position
second_title: Aspose.PDF for .NET API Reference
description: Properti TextFragment. Mendapatkan atau mengatur posisi teks untuk teks yang diwakili dengan objek TextFragment
type: docs
weight: 90
url: /id/net/aspose.pdf.text/textfragment/position/
---
## Properti TextFragment.Position

Mendapatkan atau mengatur posisi teks untuk teks, yang diwakili dengan objek [`TextFragment`](../).

```csharp
public Position Position { get; set; }
```

## Contoh

Contoh ini menunjukkan cara melihat penempatan teks, yang diwakili oleh objek [`TextFragment`](../).

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

### Lihat Juga

* kelas [TextFragmentAbsorber](../../textfragmentabsorber/)
* kelas [Document](../../../aspose.pdf/document/)
* kelas [TextSegment](../../textsegment/)
* kelas [Position](../../position/)
* kelas [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)