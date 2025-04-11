---
title: TextFragmentAbsorber.TextFragments
second_title: Aspose.PDF for .NET API Reference
description: Properti TextFragmentAbsorber. Mendapatkan koleksi kejadian pencarian yang disajikan dengan objek TextFragment
type: docs
weight: 90
url: /id/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## Properti TextFragmentAbsorber.TextFragments

Mendapatkan koleksi kejadian pencarian yang disajikan dengan objek [`TextFragment`](../../textfragment/) .

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## Contoh

Contoh ini menunjukkan cara menemukan teks di halaman pertama dokumen PDF dan mengganti semua kejadian pencarian dengan teks baru.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* kelas [TextFragmentCollection](../../textfragmentcollection/)
* kelas [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)