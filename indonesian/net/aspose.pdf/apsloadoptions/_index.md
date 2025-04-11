---
title: Class ApsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.ApsLoadOptions. Kelas ini menjelaskan opsi pemuatan aps
type: docs
weight: 2750
url: /id/net/aspose.pdf/apsloadoptions/
---
## Kelas ApsLoadOptions

Kelas ini menjelaskan opsi pemuatan aps.

```csharp
public class ApsLoadOptions : LoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ApsLoadOptions](apsloadoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau menetapkan flag untuk menonaktifkan batasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan untuk melakukan operasi dengan font yang dilarang oleh lisensi font ini, misalnya memungkinkan untuk menyematkan font ke dalam dokumen PDF meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan baik Lanjutkan atau Hentikan. Lanjutkan adalah tindakan default dan operasi Pemuatan berlanjut, namun pengguna juga dapat mengembalikan Hentikan di mana kasus operasi Pemuatan harus dihentikan. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file APS ke file PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your APS File.
	string apsFile = Path.Combine(dataDir, "APS-to-PDF.aps");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "APS-to-PDF.pdf");

	// Initialize ApsLoadOptions  	
	ApsLoadOptions apsLoadOptions = new ApsLoadOptions();

	// Initialize Document wiht ApsLoadOptions     
	using (Document pdfDocument = new Document(apsFile, apsLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your APS File.
    Dim apsFile = Path.Combine(dataDir, "APS-to-PDF.aps")
	
    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "APS-to-PDF.pdf")
 
    ' Initialize ApsLoadOptions    
    Dim apsLoadOptions As ApsLoadOptions = New ApsLoadOptions()
 
	' Initialize Document wiht ApsLoadOptions
    Using pdfDocument As Document = New Document(apsFile, apsLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Lihat Juga

* kelas [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)