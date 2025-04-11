---
title: TextFragmentAbsorber.Phrase
second_title: Aspose.PDF for .NET API Reference
description: Properti TextFragmentAbsorber. Mendapatkan atau mengatur frasa yang dicari oleh TextFragmentAbsorber pada dokumen atau halaman PDF
type: docs
weight: 50
url: /id/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## Properti TextFragmentAbsorber.Phrase

Mendapatkan atau mengatur frasa yang dicari oleh [`TextFragmentAbsorber`](../) pada dokumen atau halaman PDF.

```csharp
public string Phrase { get; set; }
```

## Contoh

Contoh ini menunjukkan cara melakukan pencarian teks beberapa kali dan melakukan penggantian teks.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// search another word and replace it
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* kelas [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)