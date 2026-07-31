---
title: "Kelas TxtLoadOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.TxtLoadOptions. Opsi pemuatan untuk konversi TXT ke PDF"
type: docs
weight: 11320
url: /id/net/aspose.pdf/txtloadoptions/
---
## TxtLoadOptions class

Opsi pemuatan untuk konversi TXT ke PDF.

```csharp
public class TxtLoadOptions : LoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TxtLoadOptions](txtloadoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau mengatur bendera untuk menonaktifkan semua pembatasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan melakukan operasi dengan font yang dilarang oleh lisensi font tersebut, misalnya memungkinkan menyematkan font ke dalam PDF document meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. Continue adalah tindakan default dan operasi Load berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Load harus berhenti. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file TXT ke file PDF

```csharp
[C#]
	// Jalur ke direktori dokumen.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Jalur ke file TXT Anda.
	string txtFile = Path.Combine(dataDir, "TXT-to-PDF.txt");

	// Jalur ke file PDF output.
	string pdfFile = Path.Combine(dataDir, "TXT-to-PDF.pdf");

	// Inisialisasi TxtLoadOptions	
	TxtLoadOptions txtLoadOptions = new TxtLoadOptions();
		
	using (Document pdfDocument = new Document(txtFile, txtLoadOptions))
	{
	 
		// Simpan file PDF
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]
    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your TXT File.
    Dim txtFile = Path.Combine(dataDir, "TXT-to-PDF.txt")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "TXT-to-PDF.pdf")
 
    ' Initialize TxtLoadOptions
    Dim txtLoadOptions As TxtLoadOptions = New TxtLoadOptions()
 
    Using pdfDocument As Document = New Document(txtFile, txtLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Lihat Juga

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


