---
title: Class EpubLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.EpubLoadOptions. Berisi opsi untuk memuat/mengimpor file EPUB ke dalam dokumen pdf
type: docs
weight: 4050
url: /id/net/aspose.pdf/epubloadoptions/
---
## Kelas EpubLoadOptions

Berisi opsi untuk memuat/mengimpor file EPUB ke dalam dokumen pdf.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | Membuat opsi muat default untuk mengonversi file EPUB ke dalam dokumen pdf. Ukuran halaman pdf default - A4 300dpi 2480 X 3508. |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | Membuat opsi muat dengan ukuran halaman yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | Mendapatkan atau menetapkan Css kustom yang diterapkan saat membuka dokumen Epub. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau menetapkan flag untuk menonaktifkan batasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan untuk melakukan operasi dengan font yang dilarang oleh lisensi font ini, misalnya memungkinkan untuk menyematkan font ke dalam dokumen PDF meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | Mendapatkan referensi pada objek yang mewakili informasi margin. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | Mendapatkan atau menetapkan ukuran halaman keluaran untuk impor. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan baik Lanjutkan atau Hentikan. Lanjutkan adalah tindakan default dan operasi Muat berlanjut, namun pengguna juga dapat mengembalikan Hentikan di mana operasi Muat harus dihentikan. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | Mewakili mode penggunaan area margin - mendefinisikan perlakuan instruksi (jika ada) dari CSS dokumen yang diimpor terkait dengan penggunaan margin. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | PERHATIAN! Fitur diimplementasikan tetapi belum dimasukkan ke API publik karena masalah penghalang di lapisan OSHARED yang terungkap untuk dokumen contoh. Mewakili mode penggunaan ukuran halaman selama konversi. Format (seperti HTML, EPUB, dll), biasanya memiliki desain mengambang, jadi, ini memungkinkan untuk menyesuaikan ukuran halaman yang diperlukan. Tetapi terkadang konten memiliki posisi horizontal atau ukuran yang ditentukan yang tidak memungkinkan untuk menempatkan konten ke dalam ukuran halaman yang diperlukan. Dalam kasus seperti itu, kita dapat mendefinisikan apa yang harus dilakukan dalam kasus ini (yaitu ketika ukuran konten tidak sesuai dengan ukuran halaman awal yang diperlukan dari dokumen PDF hasil). |

## Contoh

Contoh berikut menunjukkan cara mengonversi file EPUB ke file PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your EPUB File.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// Initialize EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your EPUB File.
    Dim epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf")
 
    ' Initialize EpubLoadOptions    
    Dim epubLoadOptions As EpubLoadOptions = New EpubLoadOptions()
 
    Using pdfDocument As Document = New Document(epubFile, epubLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Lihat Juga

* kelas [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)