---
title: Class XpsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.XpsLoadOptions. Mewakili opsi untuk memuat/mengimpor file xps ke dalam dokumen pdf
type: docs
weight: 11510
url: /id/net/aspose.pdf/xpsloadoptions/
---
## Kelas XpsLoadOptions

Mewakili opsi untuk memuat/mengimpor file xps ke dalam dokumen pdf.

```csharp
public sealed class XpsLoadOptions : LoadOptions, IPipelineOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [XpsLoadOptions](xpsloadoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BatchSize](../../aspose.pdf/xpsloadoptions/batchsize/) { get; set; } | Mendefinisikan ukuran batch jika konversi batch berlaku untuk pasangan format sumber dan tujuan. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau mengatur flag untuk menonaktifkan batasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan untuk melakukan operasi dengan font yang dilarang oleh lisensi font ini, misalnya memungkinkan untuk menyematkan font ke dalam dokumen PDF meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan baik Lanjutkan atau Hentikan. Lanjutkan adalah tindakan default dan operasi Muat berlanjut, namun pengguna juga dapat mengembalikan Hentikan di mana kasus operasi Muat harus dihentikan. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file XPS ke file PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your XPS File.
	string xpsFile = Path.Combine(dataDir, "XPS-to-PDF.xps");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "XPS-to-PDF.pdf");

	// Initialize XpsLoadOptions	
	XpsLoadOptions xpsLoadOptions = new XpsLoadOptions();
		
	using (Document pdfDocument = new Document(xpsFile, xpsLoadOptions)){
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XPS File.
    Dim xpsFile = Path.Combine(dataDir, "XPS-to-PDF.xps")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XPS-to-PDF.pdf")
 
    ' Initialize XpsLoadOptions
    Dim xpsLoadOptions As XpsLoadOptions = New XpsLoadOptions()
 
    Using pdfDocument As Document = New Document(xpsFile, xpsLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Lihat Juga

* kelas [LoadOptions](../loadoptions/)
* antarmuka [IPipelineOptions](../ipipelineoptions/)
* ruang nama [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)