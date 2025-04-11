---
title: Class Image
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Image. Mewakili gambar
type: docs
weight: 5860
url: /id/net/aspose.pdf/image/
---
## Kelas Gambar

Mewakili gambar.

```csharp
public sealed class Image : BaseParagraph
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Image](image/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BitmapInfo](../../aspose.pdf/image/bitmapinfo/) { get; set; } | Mendapatkan atau mengatur byte gambar yang tidak terkompresi. |
| [BitmapSize](../../aspose.pdf/image/bitmapsize/) { get; } | Mendapatkan ukuran bitmap gambar. |
| [File](../../aspose.pdf/image/file/) { get; set; } | Mendapatkan atau mengatur file gambar. |
| [FileType](../../aspose.pdf/image/filetype/) { get; set; } | Mendapatkan atau mengatur tipe file gambar. |
| [FixHeight](../../aspose.pdf/image/fixheight/) { get; set; } | Mendapatkan atau mengatur tinggi gambar. |
| [FixWidth](../../aspose.pdf/image/fixwidth/) { get; set; } | Mendapatkan atau mengatur lebar gambar. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal paragraf |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Mendapatkan atau mengatur hyperlink fragmen (untuk generator pdf). |
| [ImageScale](../../aspose.pdf/image/imagescale/) { get; set; } | Mendapatkan atau mengatur skala gambar. |
| [ImageStream](../../aspose.pdf/image/imagestream/) { get; set; } | Mendapatkan atau mengatur aliran gambar. |
| [IsApplyResolution](../../aspose.pdf/image/isapplyresolution/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah gambar menggunakan resolusi selama pembuatan |
| [IsBlackWhite](../../aspose.pdf/image/isblackwhite/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah gambar dipaksa menjadi hitam-putih. Jika gambar TIFF dari subformat CCITT digunakan, properti ini harus diatur ke true. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Default adalah false. (untuk pembuatan pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau mengatur paragraf sebagai inline. Default adalah false. (untuk pembuatan pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan di halaman baru. Default adalah false. (untuk pembuatan pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap di halaman yang sama bersama dengan paragraf berikutnya. Default adalah false. (untuk pembuatan pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau mengatur margin luar untuk paragraf (untuk pembuatan pdf) |
| [Title](../../aspose.pdf/image/title/) { get; set; } | Mendapatkan atau mengatur nilai string yang menunjukkan judul gambar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal paragraf |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau mengatur nilai int yang menunjukkan urutan Z dari grafik. Grafik dengan ZIndex yang lebih besar akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex dapat negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks di halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Clone](../../aspose.pdf/image/clone/)() | Mengkloning gambar. |
| static [GetMimeType](../../aspose.pdf/image/getmimetype/)(Image) | Mengembalikan tipe mime untuk gambar. |

## Contoh

Contoh berikut menunjukkan cara mengonversi gambar (PNG, JPEG, GIF, BMP, atau format gambar lainnya) menjadi file PDF.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your image (bmp, png, gif, jpeg, etc.) File.
	string imageFile = Path.Combine(dataDir, "Image-to-PDF.png");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf");

	//Initialize empty PDF document
	using(Document pdfDocument = new Document()) 
	{
	  pdfDocument.Pages.Add();
	  Image image = new Image();

	  // Load sample image file
	  image.File = imageFile;
	  pdfDocument.Pages[1].Paragraphs.Add(image);

	  // Save output PDF document
	  pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir = "YOUR_DATA_DIRECTORY"

    ' The path to your image (bmp, png, gif, jpeg, etc.) File.
    Dim imageFile = Path.Combine(dataDir, "Image-to-PDF.png")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf")
 
    'Initialize empty PDF document
    Using pdfDocument As Document = New Document()
        pdfDocument.Pages.Add()
        Dim image As Image = New Image()
 
        ' Load sample image file
        image.File = imageFile
        pdfDocument.Pages(1).Paragraphs.Add(image)
 
        ' Save output PDF document
        pdfDocument.Save(pdfFile)
    End Using
```

### Lihat Juga

* kelas [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)