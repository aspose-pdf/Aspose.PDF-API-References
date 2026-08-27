---
title: "Font.IsSubset"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti Font. Mendapatkan atau mengatur nilai yang menunjukkan apakah font merupakan subset. Font berbasis IFont akan secara otomatis menjadi subset dan tersemat."
type: docs
weight: 70
url: /id/net/aspose.pdf.text/font/issubset/
---
## Font.IsSubset property

Mendapatkan atau mengatur nilai yang menunjukkan apakah font merupakan subset. Font berbasis IFont akan secara otomatis menjadi subset dan disematkan.

```csharp
public bool IsSubset { get; set; }
```

## Contoh

Contoh ini menunjukkan cara mencari teks pada halaman pertama dan mendapatkan nilai yang menunjukkan apakah font merupakan subset.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Lihat nilai IsSubset font dari kemunculan teks pertama
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### Lihat Juga

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


