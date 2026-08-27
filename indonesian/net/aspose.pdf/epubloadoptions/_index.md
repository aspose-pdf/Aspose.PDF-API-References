---
title: "Kelas EpubLoadOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.EpubLoadOptions. Berisi opsi untuk memuat/mengimpor file EPUB ke dalam pdf document"
type: docs
weight: 4170
url: /id/net/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions class

Berisi opsi untuk memuat/mengimpor file EPUB ke dalam dokumen pdf.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | Membuat opsi muat default untuk mengonversi file EPUB ke pdf document. Default pdf Page size - A4 300dpi 2480 X 3508. |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | Membuat opsi muat dengan ukuran Page yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | Mendapatkan atau mengatur Css khusus yang diterapkan saat membuka dokumen Epub. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau mengatur bendera untuk menonaktifkan semua pembatasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan melakukan operasi dengan font yang dilarang oleh lisensi font tersebut, misalnya memungkinkan menyematkan font ke dalam PDF document meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | Mendapatkan referensi pada objek yang mewakili informasi margin. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | Mendapatkan atau mengatur ukuran Page output untuk impor. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. Continue adalah tindakan default dan operasi Load berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Load harus berhenti. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | Mewakili mode penggunaan area margin - mendefinisikan perlakuan instruksi (jika ada) CSS dokumen yang diimpor terkait penggunaan margin. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | PERHATIAN! Fitur ini telah diimplementasikan tetapi belum dipublikasikan ke API publik karena masalah penghalang di lapisan OSHARED yang terdeteksi pada dokumen contoh. Mewakili mode penggunaan ukuran Page selama konversi. Format (seperti HTML, EPUB dll), biasanya memiliki desain mengambang, sehingga memungkinkan menyesuaikan ukuran Page yang diperlukan. Namun terkadang konten memiliki posisi horizontal atau ukuran yang ditentukan yang tidak memungkinkan menempatkan konten ke dalam ukuran Page yang diperlukan. Dalam kasus tersebut kita dapat menentukan apa yang harus dilakukan (misalnya ketika ukuran konten tidak cocok dengan ukuran Page awal yang diperlukan dari dokumen PDF document). |

## Contoh

Contoh berikut menunjukkan cara mengonversi file EPUB ke file PDF

```csharp
[C#]
	// Jalur ke direktori dokumen.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Jalur ke file EPUB Anda.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// Jalur ke file PDF output.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// Inisialisasi EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// Simpan file PDF
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

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


