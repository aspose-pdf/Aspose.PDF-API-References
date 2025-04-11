---
title: Font.IsAccessible
second_title: Aspose.PDF for .NET API Reference
description: Properti Font. Mendapatkan indikasi apakah font terpasang di sistem
type: docs
weight: 50
url: /id/net/aspose.pdf.text/font/isaccessible/
---
## Properti Font.IsAccessible

Mendapatkan indikasi apakah font ada (terpasang) di sistem.

```csharp
public bool IsAccessible { get; }
```

## Catatan

Beberapa operasi tidak tersedia dengan font yang tidak dapat ditemukan di sistem.

## Contoh

Contoh ini menunjukkan cara mencari teks di halaman pertama dan mendapatkan nilai yang menunjukkan apakah font terpasang di sistem.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### Lihat Juga

* kelas [TextFragmentAbsorber](../../textfragmentabsorber/)
* kelas [Document](../../../aspose.pdf/document/)
* kelas [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)