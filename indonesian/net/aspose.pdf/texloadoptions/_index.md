---
title: "Kelas TeXLoadOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.TeXLoadOptions. Mewakili opsi untuk memuat/mengimpor file TeX ke dalam dokumen PDF"
type: docs
weight: 10550
url: /id/net/aspose.pdf/texloadoptions/
---
## TeXLoadOptions class

Mewakili opsi untuk memuat/mengimpor file TeX ke dalam dokumen PDF.

```csharp
public class TeXLoadOptions : LoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TeXLoadOptions](texloadoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | Mendapatkan/mengatur nilai tertentu untuk primitif tanggal/waktu seperti tahun, bulan, hari, dan waktu. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau mengatur bendera untuk menonaktifkan semua pembatasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan melakukan operasi dengan font yang dilarang oleh lisensi font tersebut, misalnya memungkinkan menyematkan font ke dalam PDF document meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | Mendapatkan/mengatur direktori input TeX. |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | Mendapatkan/mengatur nama pekerjaan. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | Mendapatkan/mengatur flag yang membatalkan ligatur di semua font. |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | Mendapatkan/mengatur direktori output TeX. |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | Mendapatkan/mengatur flag yang memungkinkan merasterkan rumus matematika. |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | Mendapatkan/mengatur flag yang menunjukkan apakah perlu menjalankan pekerjaan TeX dua kali dalam kasus, misalnya, terdapat referensi dalam file TeX masukan. Secara umum, perilaku ini berguna ketika mesin mengumpulkan beberapa data selama proses penataan dan menyimpannya dalam file tambahan pada run pertama. Dan pada run kedua, mesin entah bagaimana menggunakan data tersebut. |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | Mendapatkan/mengatur direktori input yang dibutuhkan TeX. Input yang diperlukan adalah file-file yang dimasukkan ke dalam file .tex utama, misalnya, paket-paket yang tidak memiliki dukungan bawaan. |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | Mendapatkan/mengatur flag yang menunjukkan apakah menampilkan output terminal di konsol. |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | Mendapatkan/mengatur flag yang menunjukkan apakah melakukan subset font dalam file output atau tidak. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. Continue adalah tindakan default dan operasi Load berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Load harus berhenti. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | Mendapatkan hasil untuk pemuatan dan kompilasi TeX - apakah semuanya berjalan lancar atau ada komentar/galat. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file TeX ke file PDF

```csharp
[C#]
	// Jalur ke direktori dokumen.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Jalur ke File TeX Anda.
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// Jalur ke file PDF output.
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// Inisialisasi TeXLoadOptions	
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// Simpan file PDF
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your TeX File.
    Dim texFile = Path.Combine(dataDir, "TeX-to-PDF.tex")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf")
 
    ' Initialize TeXLoadOptions
    Dim texLoadOptions As TeXLoadOptions = New TeXLoadOptions()
 
    Using pdfDocument As Document = New Document(texFile, texLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Lihat Juga

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


