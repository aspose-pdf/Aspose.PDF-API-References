---
title: "TextFragmentAbsorber.TextFragments"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti TextFragmentAbsorber. Mendapatkan koleksi kejadian pencarian yang disajikan dengan objek TextFragment."
type: docs
weight: 90
url: /id/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## TextFragmentAbsorber.TextFragments property

Mendapatkan koleksi kejadian pencarian yang disajikan dengan objek [`TextFragment`](../../textfragment/).

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## Contoh

Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti semua kejadian pencarian dengan teks baru.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Temukan font yang akan digunakan untuk mengubah font teks dokumen
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Ubah teks pada semua hasil pencarian
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


