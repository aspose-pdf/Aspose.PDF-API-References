---
title: "TextFragment.TextState"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti TextFragment. Mengambil atau mengatur status teks untuk teks yang direpresentasikan oleh objek TextFragment."
type: docs
weight: 150
url: /id/net/aspose.pdf.text/textfragment/textstate/
---
## TextFragment.TextState property

Mengambil atau mengatur status teks untuk teks yang direpresentasikan oleh objek [`TextFragment`](../).

```csharp
public TextFragmentState TextState { get; }
```

## Catatan

Menyediakan cara untuk mengubah properti teks berikut: Font FontSize FontStyle ForegroundColor BackgroundColor

## Contoh

Contoh ini menunjukkan cara mengubah warna teks dan ukuran font teks dengan objek `TextState`.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Ubah warna latar depan pada kemunculan teks pertama
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// Ubah ukuran font pada kemunculan teks pertama
absorber.TextFragments[1].TextState.FontSize = 15;

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentState](../../textfragmentstate/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


