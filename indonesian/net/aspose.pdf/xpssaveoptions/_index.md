---
title: Class XpsSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.XpsSaveOptions. Opsi penyimpanan untuk ekspor ke format Xps
type: docs
weight: 11520
url: /id/net/aspose.pdf/xpssaveoptions/
---
## Kelas XpsSaveOptions

Opsi penyimpanan untuk ekspor ke format Xps

```csharp
public class XpsSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BatchSize](../../aspose.pdf/xpssaveoptions/batchsize/) { get; set; } | Mendefinisikan ukuran batch jika konversi batch berlaku untuk pasangan format sumber dan tujuan. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah glyph font akan di-cache saat menyiapkan halaman aps. Meningkatkan kinerja konversi pdf ke format lain tetapi meningkatkan konsumsi memori. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Atribut ini mengaktifkan fungsionalitas untuk mengekstrak gambar atau teks untuk dokumen PDF dengan sublayer OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format penyimpanan data. |
| [SaveTransparentTexts](../../aspose.pdf/xpssaveoptions/savetransparenttexts/) { get; set; } | Menunjukkan apakah akan mempertahankan teks transparan (OCR'ed). |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah akan Melanjutkan atau Membatalkan. Melanjutkan adalah tindakan default dan operasi Simpan berlanjut, namun pengguna juga dapat mengembalikan Membatalkan di mana operasi Simpan harus dihentikan. |

## Field

| Nama | Deskripsi |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Memproses halaman dalam beberapa thread. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Terkadang PDF mengandung gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang yang sama yang diletakkan berdekatan satu sama lain. Dalam kasus seperti itu, renderer format target (misalnya MsWord untuk format DOCS) kadang-kadang menghasilkan batas yang terlihat antara bagian gambar latar belakang, karena teknik mereka dalam penghalusan tepi gambar (anti-aliasing) berbeda dari Acrobat Reader. Jika terlihat bahwa dokumen yang diekspor mengandung batas yang terlihat antara bagian gambar latar belakang yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan efek yang tidak diinginkan itu. PERHATIAN! Optimasi kualitas ini biasanya secara signifikan memperlambat konversi, jadi, silakan gunakan opsi ini hanya ketika benar-benar diperlukan. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PDF ke file XPS

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File
	var pdfFile = Path.Combine(dataDir, "PDF-to-XPS.pdf");

	// The path to your XPS File
	var xpsFile= Path.Combine(dataDir, "PDF-to-XPS.xps");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize XpsSaveOptions	
		XpsSaveOptions saveOptions = new XpsSaveOptions();
		
		// Save XPS file
		pdfDocument.Save(xpsFile, saveOptions);
	}
```

```csharp
[VB.NET]
 
    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-XPS.pdf")

    ' The path to your XPS File
    Dim xpsFile = Path.Combine(dataDir, "PDF-to-XPS.xps")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize XpsSaveOptions
        Dim saveOptions As XpsSaveOptions = New XpsSaveOptions()
 
        ' Save XPS file
        pdfDocument.Save(xpsFile, saveOptions)
    End Using
```

### Lihat Juga

* kelas [UnifiedSaveOptions](../unifiedsaveoptions/)
* antarmuka [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)