---
title: "Kelas Image"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Image kelas. Mewakili gambar."
type: docs
weight: 5990
url: /id/net/aspose.pdf/image/
---
## Image class

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
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Mendapatkan atau mengatur hyperlink fragmen (untuk pdf generator). |
| [ImageScale](../../aspose.pdf/image/imagescale/) { get; set; } | Mendapatkan atau mengatur skala gambar. |
| [ImageStream](../../aspose.pdf/image/imagestream/) { get; set; } | Mendapatkan atau mengatur aliran gambar. |
| [IsApplyResolution](../../aspose.pdf/image/isapplyresolution/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah gambar menggunakan resolusi selama pembuatan. |
| [IsBlackWhite](../../aspose.pdf/image/isblackwhite/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah gambar dipaksa menjadi hitam-putih. Jika gambar TIFF subformat CCITT digunakan, properti ini harus diatur ke true. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Defaultnya false. (untuk pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau mengatur paragraf menjadi inline. Defaultnya false. (untuk pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan pada halaman baru. Defaultnya false. (untuk pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap berada di halaman yang sama bersama paragraf berikutnya. Defaultnya false. (untuk pdf generation) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau mengatur margin luar untuk paragraf (untuk pembuatan PDF) |
| [Title](../../aspose.pdf/image/title/) { get; set; } | Mendapatkan atau mengatur nilai string yang menunjukkan judul gambar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal paragraf. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau mengatur nilai integer yang menunjukkan urutan Z grafik. Grafik dengan ZIndex lebih besar akan ditempatkan di atas grafik dengan ZIndex lebih kecil. ZIndex dapat bernilai negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks pada halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Clone](../../aspose.pdf/image/clone/)() | Gandakan gambar. |
| static [GetMimeType](../../aspose.pdf/image/getmimetype/)(Image) | Mengembalikan tipe mime untuk gambar. |

## Contoh

Contoh berikut menunjukkan cara mengonversi gambar (PNG, JPEG, GIF, BMP, atau format gambar lainnya) ke file PDF.

```csharp
[C#]
	// Jalur ke direktori dokumen.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Jalur ke gambar Anda (bmp, png, gif, jpeg, dll.) File.
	string imageFile = Path.Combine(dataDir, "Image-to-PDF.png");

	// Jalur ke file PDF output.
	string pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf");

	//Inisialisasi dokumen PDF kosong
	using(Document pdfDocument = new Document()) 
	{
	  pdfDocument.Pages.Add();
	  Image image = new Image();

	  // Muat file gambar contoh
	  image.File = imageFile;
	  pdfDocument.Pages[1].Paragraphs.Add(image);

	  // Simpan dokumen PDF output
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

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


