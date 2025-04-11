---
title: Class ImagePlacementAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.ImagePlacementAbsorber. Mewakili objek absorber dari objek penempatan gambar. Melakukan pencarian penggunaan gambar dan memberikan akses ke hasil pencarian melalui koleksi [`ImagePlacements`](./imageplacements/).
type: docs
weight: 5910
url: /id/net/aspose.pdf/imageplacementabsorber/
---
## Kelas ImagePlacementAbsorber

Mewakili objek absorber dari objek penempatan gambar. Melakukan pencarian penggunaan gambar dan memberikan akses ke hasil pencarian melalui koleksi [`ImagePlacements`](./imageplacements/).

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
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | Mendapatkan/mengatur mode hanya baca untuk koleksi operasi parsing. Ini dapat membantu menghindari pengecualian kehabisan memori. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Dokumen) | Melakukan pencarian pada dokumen yang ditentukan. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Halaman) | Melakukan pencarian pada halaman yang ditentukan. |

## Catatan

Objek `ImagePlacementAbsorber` pada dasarnya digunakan dalam skenario pencarian gambar. Ketika pencarian selesai, kejadian diwakili dengan objek [`ImagePlacement`](../imageplacement/) yang terdapat dalam koleksi [`ImagePlacements`](./imageplacements/). Objek [`ImagePlacement`](../imageplacement/) memberikan akses ke properti penempatan gambar: dimensi, resolusi, dll. Rotasi positif gambar adalah berlawanan arah jarum jam, untuk halaman, adalah searah jarum jam. Di sini, kita perlu mewakili sudut rotasi gambar, jadi kita mengurangi sudut halaman dari sudut gambar.

## Contoh

Contoh ini menunjukkan cara menemukan gambar di halaman pertama dokumen PDF dan mendapatkan properti penempatan gambar.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Display image placement properties for all placements
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