---
title: TextFragment.TextState
second_title: Aspose.PDF for .NET API Reference
description: Properti TextFragment. Mengambil atau mengatur status teks untuk teks yang diwakili oleh objek TextFragment
type: docs
weight: 150
url: /id/net/aspose.pdf.text/textfragment/textstate/
---
## Properti TextFragment.TextState

Mengambil atau mengatur status teks untuk teks yang diwakili oleh [`TextFragment`](../) objek.

```csharp
public TextFragmentState TextState { get; }
```

## Catatan

Memberikan cara untuk mengubah properti berikut dari teks: Font UkuranFont GayaFont WarnaDepan WarnaLatarBelakang

## Contoh

Contoh ini menunjukkan cara mengubah warna teks dan ukuran font dari teks dengan objek `TextState`.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* kelas [TextFragmentAbsorber](../../textfragmentabsorber/)
* kelas [Document](../../../aspose.pdf/document/)
* kelas [TextFragmentState](../../textfragmentstate/)
* kelas [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)