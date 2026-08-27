---
title: "Kelas ImagePlacement"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.ImagePlacement. Mewakili karakteristik gambar yang ditempatkan pada halaman dokumen Pdf"
type: docs
weight: 6030
url: /id/net/aspose.pdf/imageplacement/
---
## ImagePlacement class

Mewakili karakteristik gambar yang ditempatkan pada halaman dokumen Pdf.

```csharp
public sealed class ImagePlacement
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | Mendapatkan parameter komposit dari keadaan grafik yang aktif untuk gambar yang ditempatkan pada halaman. |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | Mendapatkan objek sumber daya XImage yang terkait. |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | Matriks transformasi saat ini untuk gambar ini. |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | Operator yang digunakan untuk menampilkan gambar. |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | Mendapatkan halaman yang berisi gambar. |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | Mendapatkan persegi panjang gambar. |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | Mendapatkan resolusi gambar. |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | Mendapatkan sudut rotasi gambar. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | Hapus gambar dari halaman. |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | Ganti gambar dalam koleksi dengan gambar lain. |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | Menyimpan gambar dengan transformasi yang sesuai: skala, rotasi, dan resolusi. |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | Menyimpan gambar dengan transformasi yang sesuai: skala, rotasi, dan resolusi. |

## Catatan

Ketika sebuah gambar ditempatkan pada halaman, gambar tersebut mungkin memiliki dimensi yang berbeda dari dimensi fisik yang didefinisikan dalam [`Resources`](../resources/). Objek `ImagePlacement` dimaksudkan untuk menyediakan informasi tersebut seperti dimensi, resolusi, dan sebagainya.

## Contoh

Contoh ini menunjukkan cara menemukan gambar pada halaman pertama dokumen PDF dan mendapatkan gambar sebagai bitmap dengan dimensi yang terlihat.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek ImagePlacementAbsorber untuk melakukan pencarian penempatan gambar
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(abs);

// Mengambil gambar dengan dimensi yang terlihat
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // Mengambil gambar dari sumber daya
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // Buat bitmap baru dengan dimensi sebenarnya
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


