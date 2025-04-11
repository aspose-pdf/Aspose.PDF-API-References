---
title: Font.IsSubset
second_title: Aspose.PDF for .NET API Reference
description: Properti Font. Mengambil atau menetapkan nilai yang menunjukkan apakah font adalah subset. Font yang berdasarkan IFont akan secara otomatis menjadi subset dan disematkan
type: docs
weight: 70
url: /id/net/aspose.pdf.text/font/issubset/
---
## Properti Font.IsSubset

Mengambil atau menetapkan nilai yang menunjukkan apakah font adalah subset. Font yang berdasarkan IFont akan secara otomatis menjadi subset dan disematkan

```csharp
public bool IsSubset { get; set; }
```

## Contoh

Contoh ini menunjukkan cara mencari teks di halaman pertama dan mendapatkan nilai yang menunjukkan apakah font adalah subset.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### Lihat Juga

* kelas [TextFragmentAbsorber](../../textfragmentabsorber/)
* kelas [Document](../../../aspose.pdf/document/)
* kelas [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)