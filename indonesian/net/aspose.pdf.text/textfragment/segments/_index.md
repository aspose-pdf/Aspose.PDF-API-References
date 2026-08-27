---
title: "TextFragment.Segments"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti TextFragment. Mengambil segmen teks untuk TextFragment saat ini"
type: docs
weight: 120
url: /id/net/aspose.pdf.text/textfragment/segments/
---
## TextFragment.Segments property

Mengambil segmen teks untuk [`TextFragment`](../) saat ini.

```csharp
public TextSegmentCollection Segments { get; set; }
```

## Catatan

Singkatnya, objek [`TextSegment`](../../textsegment/) adalah anak dari objek [`TextFragment`](../). Pengguna lanjutan dapat mengakses segmen secara langsung untuk melakukan skenario penyuntingan teks yang lebih kompleks. Untuk detail, silakan lihat deskripsi objek [`TextFragment`](../).

## Contoh

Contoh ini menunjukkan cara menavigasi semua objek [`TextSegment`](../../textsegment/) di dalam [`TextFragment`](../).

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Navigasikan semua segmen teks dan keluarkan teks serta info penempatannya.
foreach (TextSegment segment in absorber.TextFragments[1].Segments)
{
    Console.Out.WriteLine(string.Format("segment text: {0}", segment.Text));
    Console.Out.WriteLine(string.Format("segment X indent: {0}", segment.Position.XIndent));
    Console.Out.WriteLine(string.Format("segment Y indent: {0}", segment.Position.YIndent));
}

```

### Lihat Juga

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [TextSegmentCollection](../../textsegmentcollection/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


