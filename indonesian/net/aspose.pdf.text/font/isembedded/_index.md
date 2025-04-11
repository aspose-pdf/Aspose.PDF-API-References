---
title: Font.IsEmbedded
second_title: Aspose.PDF for .NET API Reference
description: Properti Font. Mengambil atau mengatur nilai yang menunjukkan apakah font disematkan. Font yang berdasarkan IFont akan secara otomatis disubset dan disematkan
type: docs
weight: 60
url: /id/net/aspose.pdf.text/font/isembedded/
---
## Properti Font.IsEmbedded

Mengambil atau mengatur nilai yang menunjukkan apakah font disematkan. Font yang berdasarkan IFont akan secara otomatis disubset dan disematkan

```csharp
public bool IsEmbedded { get; set; }
```

## Contoh

Contoh berikut menunjukkan cara menemukan font, menandainya sebagai disematkan, mencari teks di halaman dokumen dan mengganti font teks.

```csharp
// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// open document
Document doc = new Document(@"D:\Tests\input.pdf");

// create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// change font for the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Lihat Juga

* kelas [TextFragmentAbsorber](../../textfragmentabsorber/)
* kelas [FontRepository](../../fontrepository/)
* kelas [Document](../../../aspose.pdf/document/)
* kelas [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)