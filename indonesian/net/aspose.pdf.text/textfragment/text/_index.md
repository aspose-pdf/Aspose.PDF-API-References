---
title: "TextFragment.Text"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti TextFragment. Mendapatkan atau mengatur objek teks String yang direpresentasikan oleh objek TextFragment."
type: docs
weight: 130
url: /id/net/aspose.pdf.text/textfragment/text/
---
## TextFragment.Text property

Mendapatkan atau mengatur objek teks String yang direpresentasikan oleh objek [`TextFragment`](../).

```csharp
public string Text { get; set; }
```

## Contoh

Contoh ini menunjukkan cara mencari teks dan mengganti kemunculan pertama yang direpresentasikan dengan objek [`TextFragment`](../).

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Ubah font pada kemunculan teks pertama
absorber.TextFragments[1].Text = "hi world";

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf"); 
```

### Lihat Juga

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


