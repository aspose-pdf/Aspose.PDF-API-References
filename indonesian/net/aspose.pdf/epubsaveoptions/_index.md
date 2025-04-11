---
title: Class EpubSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.EpubSaveOptions. Opsi simpan untuk ekspor ke format EPUB
type: docs
weight: 4060
url: /id/net/aspose.pdf/epubsaveoptions/
---
## Kelas EpubSaveOptions

Opsi simpan untuk ekspor ke format EPUB

```csharp
public class EpubSaveOptions : UnifiedSaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [EpubSaveOptions](epubsaveoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah glyph font akan disimpan sementara saat menyiapkan halaman aps. Meningkatkan kinerja konversi pdf ke format lain tetapi meningkatkan konsumsi memori. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Atribut ini mengaktifkan fungsionalitas untuk mengekstrak gambar atau teks untuk dokumen PDF dengan sublayer OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format data simpan. |
| [Title](../../aspose.pdf/epubsaveoptions/title/) { get; set; } | Mendapatkan atau mengatur judul dokumen EPUB. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah akan Melanjutkan atau Menghentikan. Melanjutkan adalah tindakan default dan operasi Simpan berlanjut, namun pengguna juga dapat mengembalikan Menghentikan di mana operasi Simpan harus dihentikan. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [ContentRecognitionMode](../../aspose.pdf/epubsaveoptions/contentrecognitionmode/) | Ketika file PDF (yang biasanya memiliki tata letak tetap) sedang dikonversi, mesin konversi mencoba melakukan pengelompokan dan analisis multi-level untuk memulihkan niat asli penulis dokumen dan menghasilkan hasil dalam tata letak aliran. Properti ini menyetel konversi untuk metode pengenalan konten yang diinginkan ini atau itu. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Memproses halaman dalam beberapa utas. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Terkadang PDF mengandung gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang yang sama yang diletakkan berdekatan satu sama lain. Dalam kasus seperti itu, perender format target (misalnya MsWord untuk format DOCS) terkadang menghasilkan batas yang terlihat antara bagian gambar latar belakang, karena teknik mereka dalam penghalusan tepi gambar (anti-aliasing) berbeda dari Acrobat Reader. Jika terlihat bahwa dokumen yang diekspor mengandung batas yang terlihat antara bagian gambar latar belakang yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan efek yang tidak diinginkan itu. PERHATIAN! Optimasi kualitas ini biasanya secara signifikan memperlambat konversi, jadi, silakan gunakan opsi ini hanya ketika benar-benar diperlukan. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PDF ke file EPUB

```csharp
	[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-EPUB.pdf");

	// The path to output EPUB File.
	var epubFile = Path.Combine(dataDir, "PDF-to-EPUB.epub");
		
	using (Document pdfDocument = new Document(pdfFile))
	{

		// Initialize EpubSaveOptions 	
		EpubSaveOptions saveOptions = new EpubSaveOptions();
		
		// Save EPUB file
		pdfDocument.Save(epubFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-EPUB.pdf")

    ' The path to output EPUB File.
    Dim epubFile = Path.Combine(dataDir, "PDF-to-EPUB.epub")
 
    Using pdfDocument As Document = New Document(pdfFile)

        ' Initialize EpubSaveOptions    
        Dim saveOptions As EpubSaveOptions = New EpubSaveOptions()
 
        ' Save EPUB file
        pdfDocument.Save(epubFile, saveOptions)
    End Using
```

### Lihat Juga

* kelas [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)