---
title: "Kelas ApsLoadOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.ApsLoadOptions. Kelas menjelaskan opsi pemuatan aps"
type: docs
weight: 2850
url: /id/net/aspose.pdf/apsloadoptions/
---
## ApsLoadOptions class

Kelas menggambarkan opsi pemuatan aps.

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
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau mengatur bendera untuk menonaktifkan semua pembatasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan melakukan operasi dengan font yang dilarang oleh lisensi font tersebut, misalnya memungkinkan menyematkan font ke dalam PDF document meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. Continue adalah tindakan default dan operasi Load berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Load harus berhenti. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file APS ke file PDF

```csharp
[C#]
	// Jalur ke direktori dokumen.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Jalur ke file APS Anda.
	string apsFile = Path.Combine(dataDir, "APS-to-PDF.aps");

	// Jalur ke file PDF output.
	string pdfFile = Path.Combine(dataDir, "APS-to-PDF.pdf");

	// Inisialisasi ApsLoadOptions 	
	ApsLoadOptions apsLoadOptions = new ApsLoadOptions();

	// Inisialisasi Document dengan ApsLoadOptions     
	using (Document pdfDocument = new Document(apsFile, apsLoadOptions))
	{
	 
		// Simpan file PDF
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

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


