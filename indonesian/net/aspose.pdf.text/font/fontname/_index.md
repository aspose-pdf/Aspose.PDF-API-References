---
title: "Font.FontName"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti Font. Mendapatkan nama font dari objek Font"
type: docs
weight: 30
url: /id/net/aspose.pdf.text/font/fontname/
---
## Font.FontName property

Mendapatkan nama font dari objek [`Font`](../).

```csharp
public string FontName { get; }
```

## Contoh

Contoh ini menunjukkan cara mencari teks pada halaman pertama dan melihat nama font dari kemunculan teks pertama.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Lihat nama font dari kemunculan teks pertama
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### Lihat Juga

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


