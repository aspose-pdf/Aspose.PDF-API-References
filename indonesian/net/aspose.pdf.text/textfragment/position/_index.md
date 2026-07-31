---
title: "TextFragment.Position"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti TextFragment. Mengambil atau mengatur posisi teks untuk teks yang direpresentasikan oleh objek TextFragment."
type: docs
weight: 90
url: /id/net/aspose.pdf.text/textfragment/position/
---
## TextFragment.Position property

Mengambil atau mengatur posisi teks untuk teks yang direpresentasikan oleh objek [`TextFragment`](../).

```csharp
public Position Position { get; set; }
```

## Contoh

Contoh ini menunjukkan cara melihat penempatan teks yang direpresentasikan oleh objek [`TextFragment`](../).

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Lihat teks dan info penempatan dari kemunculan teks pertama.
TextFragment firstOccurrence = absorber.TextFragments[1];

Console.Out.WriteLine(string.Format("fragment text: {0}", firstOccurrence.Text));
Console.Out.WriteLine(string.Format("fragment X indent: {0}", firstOccurrence.Position.XIndent));
Console.Out.WriteLine(string.Format("fragment Y indent: {0}", firstOccurrence.Position.YIndent));

```

### Lihat Juga

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [Position](../../position/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


