---
title: "Font.IsAccessible"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti Font. Mendapatkan indikasi apakah font terpasang di sistem."
type: docs
weight: 50
url: /id/net/aspose.pdf.text/font/isaccessible/
---
## Font.IsAccessible property

Mendapatkan indikasi apakah font tersedia (terpasang) di sistem.

```csharp
public bool IsAccessible { get; }
```

## Catatan

Beberapa operasi tidak tersedia untuk font yang tidak dapat ditemukan di sistem.

## Contoh

Contoh ini menunjukkan cara mencari teks pada halaman pertama dan mendapatkan nilai yang menunjukkan apakah font terpasang di sistem.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Lihat nilai IsSubset font dari kemunculan teks pertama
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### Lihat Juga

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


