---
title: "Kelas PdfSaveOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.PdfSaveOptions. Opsi penyimpanan untuk mengekspor ke format Pdf"
type: docs
weight: 8570
url: /id/net/aspose.pdf/pdfsaveoptions/
---
## PdfSaveOptions class

Opsi penyimpanan untuk mengekspor ke format Pdf

```csharp
public class PdfSaveOptions : SaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah glif font akan di-cache saat menyiapkan halaman aps. Meningkatkan kinerja konversi PDF ke format lain tetapi meningkatkan konsumsi memori. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [DefaultFontName](../../aspose.pdf/pdfsaveoptions/defaultfontname/) { get; set; } | Nama font yang digunakan secara default untuk font yang tidak ada di komputer. Ketika dokumen PDF yang disimpan ke PDF berisi font yang tidak tersedia di dokumen itu sendiri maupun di perangkat, API menggantikan font tersebut dengan font default (jika font dengan [`DefaultFontName`](./defaultfontname/) ditemukan di perangkat). |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format penyimpanan data. |
| [TempPath](../../aspose.pdf/pdfsaveoptions/temppath/) { get; set; } | Jalur untuk file sementara. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan Continue atau Abort. Continue adalah tindakan default dan operasi Save berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Save harus berhenti. |

## Contoh

Contoh berikut menunjukkan cara mengatur nama font default saat Menyimpan PDF

```csharp
[C#]
	// Jalur ke direktori dokumen.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Muat dokumen PDF yang ada dengan font yang hilang
	string documentName = dataDir + "input.pdf";
	string fontName = "Arial";
	using (System.IO.FileStream fs = new System.IO.FileStream(documentName, System.IO.FileMode.Open))
	using (Document document = new Document(fs))
	{
		PdfSaveOptions pdfSaveOptions = new PdfSaveOptions();

		// Tentukan Nama Font Default
		pdfSaveOptions.DefaultFontName = fontName;
		document.Save(dataDir + "output_out.pdf", pdfSaveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' Load an existing PDF document with missing font
    Dim documentName = dataDir & "input.pdf"
    Dim fontName = "Arial"
 
    Using fs As FileStream = New FileStream(documentName, FileMode.Open)
 
        Using document As Document = New Document(fs)
            Dim pdfSaveOptions As PdfSaveOptions = New PdfSaveOptions()

            ' Specify Default Font Name
            pdfSaveOptions.DefaultFontName = fontName
            document.Save(dataDir & "output_out.pdf", pdfSaveOptions)
        End Using
    End Using
```

### Lihat Juga

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


