---
title: "Font.IsEmbedded"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti Font. Mendapatkan atau mengatur nilai yang menunjukkan apakah font tersemat. Font berbasis IFont akan secara otomatis menjadi subset dan tersemat."
type: docs
weight: 60
url: /id/net/aspose.pdf.text/font/isembedded/
---
## Font.IsEmbedded property

Mendapatkan atau mengatur nilai yang menunjukkan apakah font disematkan. Font berbasis IFont akan secara otomatis menjadi subset dan disematkan.

```csharp
public bool IsEmbedded { get; set; }
```

## Contoh

Contoh berikut menunjukkan cara menemukan font, menandainya sebagai tersemat, mencari teks pada halaman dokumen, dan mengganti font teks.

```csharp
// Buat font dan tandai agar disematkan
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// ubah font untuk kemunculan teks pertama
absorber.TextFragments[1].TextState.Font = font;

// simpan dokumen
doc.Save(@"D:\Tests\output.pdf"); 
```

### Lihat Juga

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [FontRepository](../../fontrepository/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


