---
title: TextFragment.Segments
second_title: Aspose.PDF for .NET API Reference
description: Properti TextFragment. Mendapatkan segmen teks untuk TextFragment saat ini
type: docs
weight: 120
url: /id/net/aspose.pdf.text/textfragment/segments/
---
## Properti TextFragment.Segments

Mendapatkan segmen teks untuk [`TextFragment`](../) saat ini.

```csharp
public TextSegmentCollection Segments { get; set; }
```

## Catatan

Dalam beberapa kata, objek [`TextSegment`](../../textsegment/) adalah anak dari objek [`TextFragment`](../). Pengguna yang lebih mahir dapat mengakses segmen secara langsung untuk melakukan skenario pengeditan teks yang lebih kompleks. Untuk detail lebih lanjut, silakan lihat deskripsi objek [`TextFragment`](../).

## Contoh

Contoh ini menunjukkan cara menavigasi semua objek [`TextSegment`](../../textsegment/) di dalam [`TextFragment`](../).

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

### Lihat Juga

* kelas [TextFragmentAbsorber](../../textfragmentabsorber/)
* kelas [Document](../../../aspose.pdf/document/)
* kelas [TextSegment](../../textsegment/)
* kelas [TextSegmentCollection](../../textsegmentcollection/)
* kelas [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)