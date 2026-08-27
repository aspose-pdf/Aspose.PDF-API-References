---
title: "Kelas EpubSaveOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.EpubSaveOptions. Opsi penyimpanan untuk ekspor ke format EPUB"
type: docs
weight: 4180
url: /id/net/aspose.pdf/epubsaveoptions/
---
## EpubSaveOptions class

Opsi penyimpanan untuk ekspor ke format EPUB.

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
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah glif font akan di-cache saat menyiapkan halaman aps. Meningkatkan kinerja konversi PDF ke format lain tetapi meningkatkan konsumsi memori. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Atribut ini mengaktifkan fungsionalitas untuk mengekstrak gambar atau teks dari dokumen PDF dengan sublayer OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format penyimpanan data. |
| [Title](../../aspose.pdf/epubsaveoptions/title/) { get; set; } | Mengambil atau mengatur judul dokumen EPUB. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan Continue atau Abort. Continue adalah tindakan default dan operasi Save berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Save harus berhenti. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [ContentRecognitionMode](../../aspose.pdf/epubsaveoptions/contentrecognitionmode/) | Ketika file PDF (yang biasanya memiliki tata letak tetap) sedang dikonversi, mesin konversi berusaha melakukan pengelompokan dan analisis multi‑tingkat untuk mengembalikan maksud penulis dokumen asli dan menghasilkan hasil dalam tata letak aliran. Properti ini menyesuaikan konversi tersebut untuk metode pengenalan konten yang diinginkan. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Proses halaman dengan beberapa thread. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Terkadang PDF berisi gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang berulang yang ditempatkan berdekatan. Dalam kasus seperti itu, renderer format target (mis. MsWord untuk format DOCS) kadang menghasilkan batas yang terlihat antara bagian-bagian gambar latar belakang, karena teknik penyamaran tepi gambar (anti-aliasing) mereka berbeda dari Acrobat Reader. Jika tampak bahwa dokumen yang diekspor mengandung batas terlihat antara bagian-bagian gambar latar belakang yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan efek yang tidak diinginkan. PERHATIAN! Optimasi kualitas ini biasanya secara signifikan memperlambat konversi, jadi, harap gunakan opsi ini hanya ketika benar‑benar diperlukan. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PDF ke file EPUB

```csharp
	[C#]
	// Jalur ke direktori dokumen.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Jalur ke File PDF Anda.
	var pdfFile = Path.Combine(dataDir, "PDF-to-EPUB.pdf");

	// Jalur ke file EPUB output.
	var epubFile = Path.Combine(dataDir, "PDF-to-EPUB.epub");
		
	using (Document pdfDocument = new Document(pdfFile))
	{

		// Inisialisasi EpubSaveOptions \t
		EpubSaveOptions saveOptions = new EpubSaveOptions();
		
		// Simpan file EPUB
		pdfDocument.Save(epubFile, saveOptions);
	}
````

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

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


