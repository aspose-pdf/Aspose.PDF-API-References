---
title: Font.FontName
second_title: Aspose.PDF for .NET API Reference
description: Properti Font. Mendapatkan nama font dari objek Font
type: docs
weight: 30
url: /id/net/aspose.pdf.text/font/fontname/
---
## Properti Font.FontName

Mendapatkan nama font dari objek [`Font`](../).

```csharp
public string FontName { get; }
```

## Contoh

Contoh ini menunjukkan cara mencari teks di halaman pertama dan melihat nama font dari kemunculan teks pertama.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font name of first text occurrence
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### Lihat Juga

* kelas [TextFragmentAbsorber](../../textfragmentabsorber/)
* kelas [Document](../../../aspose.pdf/document/)
* kelas [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)