---
title: TextFragment.Text
second_title: Aspose.PDF for .NET API Reference
description: Properti TextFragment. Mendapatkan atau mengatur objek teks String yang diwakili oleh objek TextFragment
type: docs
weight: 130
url: /id/net/aspose.pdf.text/textfragment/text/
---
## Properti TextFragment.Text

Mendapatkan atau mengatur objek teks String yang diwakili oleh objek [`TextFragment`](../).

```csharp
public string Text { get; set; }
```

## Contoh

Contoh ini menunjukkan cara mencari teks dan mengganti kemunculan pertama yang diwakili dengan objek [`TextFragment`](../).

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Lihat Juga

* kelas [TextFragmentAbsorber](../../textfragmentabsorber/)
* kelas [Document](../../../aspose.pdf/document/)
* kelas [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)