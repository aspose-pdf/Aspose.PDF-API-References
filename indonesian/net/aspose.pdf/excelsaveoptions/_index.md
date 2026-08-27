---
title: "Kelas ExcelSaveOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.ExcelSaveOptions. Opsi penyimpanan untuk ekspor ke format Excel."
type: docs
weight: 4200
url: /id/net/aspose.pdf/excelsaveoptions/
---
## ExcelSaveOptions class

Opsi penyimpanan untuk ekspor ke format Excel.

```csharp
public class ExcelSaveOptions : UnifiedSaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ExcelSaveOptions](excelsaveoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah glif font akan di-cache saat menyiapkan halaman aps. Meningkatkan kinerja konversi PDF ke format lain tetapi meningkatkan konsumsi memori. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Atribut ini mengaktifkan fungsionalitas untuk mengekstrak gambar atau teks dari dokumen PDF dengan sublayer OCR. |
| [Format](../../aspose.pdf/excelsaveoptions/format/) { get; set; } | Format output |
| [InsertBlankColumnAtFirst](../../aspose.pdf/excelsaveoptions/insertblankcolumnatfirst/) { get; set; } | Atur true jika Anda memerlukan penyisipan kolom kosong sebagai kolom pertama lembar kerja. Nilai default adalah false; artinya kolom kosong tidak akan disisipkan. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf/excelsaveoptions/minimizethenumberofworksheets/) { get; set; } | Atur true jika Anda perlu meminimalkan jumlah lembar kerja dalam buku kerja yang dihasilkan. Nilai default adalah false; artinya setiap halaman PDF disimpan sebagai lembar kerja terpisah. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format penyimpanan data. |
| [UniformWorksheets](../../aspose.pdf/excelsaveoptions/uniformworksheets/) { get; set; } | Setel true untuk menggunakan pembagian kolom seragam di seluruh Document. Nilai default adalah false; artinya pembagian kolom akan independen untuk setiap halaman. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan Continue atau Abort. Continue adalah tindakan default dan operasi Save berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Save harus berhenti. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Proses halaman dengan beberapa thread. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Terkadang PDF berisi gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang berulang yang ditempatkan berdekatan. Dalam kasus seperti itu, renderer format target (mis. MsWord untuk format DOCS) kadang menghasilkan batas yang terlihat antara bagian-bagian gambar latar belakang, karena teknik penyamaran tepi gambar (anti-aliasing) mereka berbeda dari Acrobat Reader. Jika tampak bahwa dokumen yang diekspor mengandung batas terlihat antara bagian-bagian gambar latar belakang yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan efek yang tidak diinginkan. PERHATIAN! Optimasi kualitas ini biasanya secara signifikan memperlambat konversi, jadi, harap gunakan opsi ini hanya ketika benar‑benar diperlukan. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PDF ke file XLS atau XLSX.

```csharp
[C#]
	// Jalur ke direktori dokumen.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Jalur ke File PDF Anda.
	var pdfFile = Path.Combine(dataDir, "PDF-to-xlsx.pdf");

	// Jalur ke file xls atau xlsx output.
	var excelFile= Path.Combine(dataDir, "PDF-to-xlsx.xlsx");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Inisialisasi ExcelSaveOptions\t
		ExcelSaveOptions saveOptions = new ExcelSaveOptions();
		
		// Simpan file xls atau xlsx
		pdfDocument.Save(excelFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
    
	' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-xlsx.pdf")
    
	' The path to output xls or xlsx File.
    Dim excelFile = Path.Combine(dataDir, "PDF-to-xlsx.xlsx")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize ExcelSaveOptions  
        Dim saveOptions As ExcelSaveOptions = New ExcelSaveOptions()
 
        ' Save xls or xlsx file
        pdfDocument.Save(excelFile, saveOptions)
    End Using
```

### Lihat Juga

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


