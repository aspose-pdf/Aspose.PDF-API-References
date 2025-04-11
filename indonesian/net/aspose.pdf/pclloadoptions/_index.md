---
title: Class PclLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.PclLoadOptions. Mewakili opsi untuk memuat mengimpor file PCL ke dalam dokumen pdf
type: docs
weight: 8300
url: /id/net/aspose.pdf/pclloadoptions/
---
## Kelas PclLoadOptions

Mewakili opsi untuk memuat (mengimpor) file PCL ke dalam dokumen pdf.

```csharp
public sealed class PclLoadOptions : LoadOptions, IPipelineOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PclLoadOptions](pclloadoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BatchSize](../../aspose.pdf/pclloadoptions/batchsize/) { get; set; } | Mendefinisikan ukuran batch jika konversi batch berlaku untuk pasangan format sumber dan tujuan. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau mengatur flag untuk menonaktifkan batasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan untuk melakukan operasi dengan font yang dilarang oleh lisensi font ini, misalnya memungkinkan untuk menyematkan font ke dalam dokumen PDF meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan baik Lanjutkan atau Hentikan. Lanjutkan adalah tindakan default dan operasi Muat berlanjut, namun pengguna juga dapat mengembalikan Hentikan di mana kasus operasi Muat harus dihentikan. |

## Field

| Nama | Deskripsi |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/pclloadoptions/conversionengine/) | Mendefinisikan mesin konversi yang akan digunakan untuk konversi |
| [Exceptions](../../aspose.pdf/pclloadoptions/exceptions/) | Daftar kesalahan konversi. |
| [SupressErrors](../../aspose.pdf/pclloadoptions/supresserrors/) | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah kesalahan konversi PCL harus disembunyikan. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PCL ke file PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your PCL File.
	string pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf");

	// Initialize PclLoadOptions	
	PclLoadOptions pclLoadOptions = new PclLoadOptions();
		
	using (Document pdfDocument = new Document(pclFile, pclLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PCL File.
    Dim pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf")
 
    ' Initialize PclLoadOptions
    Dim pclLoadOptions As PclLoadOptions = New PclLoadOptions()
 
    Using pdfDocument As Document = New Document(pclFile, pclLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Lihat Juga

* kelas [LoadOptions](../loadoptions/)
* antarmuka [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)