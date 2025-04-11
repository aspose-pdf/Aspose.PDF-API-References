---
title: Class SvgSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.SvgSaveOptions. Opsi penyimpanan untuk ekspor ke format SVG
type: docs
weight: 10230
url: /id/net/aspose.pdf/svgsaveoptions/
---
## Kelas SvgSaveOptions

Opsi penyimpanan untuk ekspor ke format SVG

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Mendapatkan atau menetapkan nilai boolean yang menunjukkan apakah glyph font akan disimpan saat menyiapkan halaman aps. Meningkatkan kinerja konversi pdf ke format lain tetapi meningkatkan konsumsi memori. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Mendapatkan atau menetapkan nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Atribut ini mengaktifkan fungsionalitas untuk mengekstrak gambar atau teks untuk dokumen PDF dengan sublayer OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format penyimpanan data. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah akan Melanjutkan atau Membatalkan. Melanjutkan adalah tindakan default dan operasi Simpan dilanjutkan, namun pengguna juga dapat mengembalikan Membatalkan, dalam hal ini operasi Simpan harus dihentikan. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | Menentukan apakah output akan dibuat sebagai satu arsip zip. Silakan merujuk komentar pada opsi 'TreatTargetFileNameAsDirectory' untuk melihat aturan penamaan file svg dari halaman untuk dokumen sumber multipage, yang juga diterapkan pada set file output yang terkompresi. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi untuk penanganan khusus dari file gambar eksternal yang dirujuk yang dibuat (seperti BMP atau JPEG yang disematkan) yang disematkan ke dalam SVG yang disimpan. Strategi itu harus memproses sumber daya dan mengembalikan string yang mewakili URI yang diinginkan dari sumber daya yang disimpan dalam SVG yang dihasilkan. Jika pemrosesan untuk file ini atau itu harus dilakukan oleh kode konverter itu sendiri, bukan dalam kode khusus, silakan atur dalam kode khusus bendera 'CustomProcessingCancelled' dari variabel parameter 'imageSavingInfo'. Ini memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk pemrosesan sumber daya itu harus dilakukan di dalam konverter seolah-olah tidak ada kode khusus eksternal. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Memproses halaman dalam beberapa utas. |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | Menentukan apakah akan menskalakan dokumen output dari poin tipografi ke piksel. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | Opsi ini menentukan apakah direktori target akan dibuat (jika belum ada) dengan nama yang sama seperti file output yang diminta alih-alih file output yang diminta itu sendiri. Jika ya, direktori tersebut akan berisi semua gambar SVG output dari halaman (seperti yang dijelaskan di bawah). Jika tidak, file output dari halaman selain yang pertama akan dibuat tepat di direktori yang diminta sebagai file output utama, tetapi akan mengandung dalam nama file akhiran _[2...n], yang ditentukan oleh nomor halaman, misalnya jika Anda mendefinisikan file output "C:\AsposeTests\output.svg" dan output akan berisi beberapa file svg dari halaman, maka file halaman akan dibuat juga di direktori "C:\AsposeTests\" dan memiliki nama 'output.svg', 'output_2.svg', 'output_3.svg' dll. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Terkadang PDF mengandung gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang yang sama yang ditumpuk satu di samping yang lain. Dalam kasus seperti itu, perender format target (misalnya MsWord untuk format DOCS) terkadang menghasilkan batas yang terlihat antara bagian gambar latar belakang, karena teknik penghalusan tepi gambar (anti-aliasing) mereka berbeda dari Acrobat Reader. Jika terlihat bahwa dokumen yang diekspor mengandung batas yang terlihat antara bagian gambar latar belakang yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan efek yang tidak diinginkan itu. PERHATIAN! Optimasi kualitas ini biasanya secara signifikan memperlambat konversi, jadi, silakan gunakan opsi ini hanya ketika benar-benar diperlukan. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PDF ke file SVG

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// The path to output SVG File.
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize SvgSaveOptions	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// Save SVG file
		pdfDocument.Save(svgFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf")

    ' The path to output SVG File.
    Dim svgFile = Path.Combine(dataDir, "PDF-to-SVG.svg")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize SvgSaveOptions
        Dim saveOptions As SvgSaveOptions = New SvgSaveOptions()
 
        ' Save SVG file
        pdfDocument.Save(svgFile, saveOptions)
    End Using
```

### Lihat Juga

* kelas [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)