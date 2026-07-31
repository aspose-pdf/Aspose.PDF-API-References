---
title: "TextFragmentAbsorber.Phrase"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti TextFragmentAbsorber. Mendapatkan atau mengatur frasa yang dicari oleh TextFragmentAbsorber pada document PDF atau page."
type: docs
weight: 50
url: /id/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## TextFragmentAbsorber.Phrase property

Mendapatkan atau mengatur frasa yang dicari oleh [`TextFragmentAbsorber`](../) pada document PDF atau page.

```csharp
public string Phrase { get; set; }
```

## Contoh

Contoh ini menunjukkan cara melakukan pencarian teks beberapa kali dan melakukan penggantian teks.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// cari kata lain dan ganti
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


