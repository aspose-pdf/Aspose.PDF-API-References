---
title: Class ImagePlacement
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.ImagePlacement. Mewakili karakteristik gambar yang ditempatkan pada halaman dokumen Pdf
type: docs
weight: 5900
url: /id/net/aspose.pdf/imageplacement/
---
## Kelas ImagePlacement

Mewakili karakteristik gambar yang ditempatkan pada halaman dokumen Pdf.

```csharp
public sealed class ImagePlacement
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | Mendapatkan parameter komposit dari status grafik yang aktif untuk gambar yang ditempatkan di halaman. |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | Mendapatkan objek sumber XImage yang terkait. |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | Matriks transformasi saat ini untuk gambar ini. |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | Operator yang digunakan untuk menampilkan gambar. |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | Mendapatkan halaman yang berisi gambar. |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | Mendapatkan persegi panjang dari Gambar. |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | Mendapatkan resolusi dari Gambar. |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | Mendapatkan sudut rotasi dari Gambar. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | Menghapus gambar dari halaman. |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | Mengganti gambar dalam koleksi dengan gambar lain. |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | Menyimpan gambar dengan transformasi yang sesuai: penskalaan, rotasi, dan resolusi. |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | Menyimpan gambar dengan transformasi yang sesuai: penskalaan, rotasi, dan resolusi. |

## Catatan

Ketika sebuah gambar ditempatkan pada sebuah halaman, mungkin memiliki dimensi yang berbeda dari dimensi fisik yang didefinisikan dalam [`Resources`](../resources/). Objek `ImagePlacement` dimaksudkan untuk memberikan informasi seperti dimensi, resolusi, dan sebagainya.

## Contoh

Contoh ini menunjukkan cara menemukan gambar pada halaman pertama dokumen PDF dan mendapatkan gambar sebagai bitmap dengan dimensi yang terlihat.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Retrieve images with visible dimensions
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // Retrieve image from resources
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // Create new bitmap with actual dimensions
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)