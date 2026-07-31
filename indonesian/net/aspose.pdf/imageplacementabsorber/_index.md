---
title: "Kelas ImagePlacementAbsorber"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.ImagePlacementAbsorber. Mewakili objek absorber dari objek penempatan gambar. Melakukan pencarian penggunaan gambar dan menyediakan akses ke hasil pencarian melalui koleksi ImagePlacements"
type: docs
weight: 6040
url: /id/net/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber class

Mewakili objek absorber dari objek penempatan gambar. Melakukan pencarian penggunaan gambar dan menyediakan akses ke hasil pencarian melalui koleksi [`ImagePlacements`](./imageplacements/).

```csharp
public sealed class ImagePlacementAbsorber
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ImagePlacementAbsorber](imageplacementabsorber/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | Mendapatkan koleksi kejadian penempatan gambar yang disajikan dengan objek [`ImagePlacement`](../imageplacement/). |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | Mendapatkan/mengatur mode hanya-baca untuk koleksi operasi parsing. Ini dapat membantu mencegah pengecualian kehabisan memori. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | Melakukan pencarian pada dokumen yang ditentukan. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | Melakukan pencarian pada halaman yang ditentukan. |

## Catatan

Objek `ImagePlacementAbsorber` pada dasarnya digunakan dalam skenario pencarian gambar. Ketika pencarian selesai, kejadian-kejadian tersebut direpresentasikan dengan objek [`ImagePlacement`](../imageplacement/) yang terdapat dalam koleksi [`ImagePlacements`](./imageplacements/). Objek [`ImagePlacement`](../imageplacement/) menyediakan akses ke properti penempatan gambar: dimensi, resolusi, dll. Rotasi positif gambar berlawanan arah jarum jam, sedangkan untuk halaman berarah jarum jam. Di sini, kita perlu merepresentasikan sudut rotasi gambar, sehingga kami mengurangkan sudut halaman dari sudut gambar.

## Contoh

Contoh ini menunjukkan cara menemukan gambar pada halaman pertama dokumen PDF dan mendapatkan properti penempatan gambar.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek ImagePlacementAbsorber untuk melakukan pencarian penempatan gambar
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(abs);

// Tampilkan properti penempatan gambar untuk semua penempatan
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{     
    Console.Out.WriteLine("image width:" + imagePlacement.Rectangle.Width);
    Console.Out.WriteLine("image height:" + imagePlacement.Rectangle.Height);
    Console.Out.WriteLine("image LLX:" + imagePlacement.Rectangle.LLX);
    Console.Out.WriteLine("image LLY:" + imagePlacement.Rectangle.LLY);
    Console.Out.WriteLine("image horizontal resolution:" + imagePlacement.Resolution.X);
    Console.Out.WriteLine("image vertical resolution:" + imagePlacement.Resolution.Y);
}
```

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


