---
title: TextFragmentAbsorber.TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: Properti TextFragmentAbsorber. Mengambil atau mengatur opsi pencarian. Opsi ini memungkinkan pencarian menggunakan ekspresi reguler
type: docs
weight: 110
url: /id/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## Properti TextFragmentAbsorber.TextSearchOptions

Mengambil atau mengatur opsi pencarian. Opsi ini memungkinkan pencarian menggunakan ekspresi reguler.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## Contoh

Contoh ini menunjukkan cara melakukan pencarian teks menggunakan ekspresi reguler.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// make the absorber to search all words starting 'h' and ending 'o' using regular expression.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Lihat Juga

* kelas [TextSearchOptions](../../textsearchoptions/)
* kelas [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)