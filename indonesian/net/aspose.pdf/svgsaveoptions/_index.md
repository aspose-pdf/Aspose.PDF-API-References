---
title: "Kelas SvgSaveOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.SvgSaveOptions. Opsi penyimpanan untuk ekspor ke format SVG"
type: docs
weight: 10410
url: /id/net/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions class

Opsi penyimpanan untuk mengekspor ke format SVG

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
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah glif font akan di-cache saat menyiapkan halaman aps. Meningkatkan kinerja konversi PDF ke format lain tetapi meningkatkan konsumsi memori. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Atribut ini mengaktifkan fungsionalitas untuk mengekstrak gambar atau teks dari dokumen PDF dengan sublayer OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format penyimpanan data. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan Continue atau Abort. Continue adalah tindakan default dan operasi Save berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Save harus berhenti. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | Menentukan apakah output akan dibuat sebagai satu arsip zip. Silakan lihat komentar pada opsi 'TreatTargetFileNameAsDirectory' untuk melihat aturan penamaan file svg halaman untuk dokumen sumber multihalaman, yang juga diterapkan pada kumpulan file output yang di-zip. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi untuk penanganan khusus file gambar eksternal yang direferensikan (seperti BMP atau JPEG yang disematkan) yang disematkan ke dalam SVG yang disimpan. Strategi tersebut harus memproses sumber daya dan mengembalikan string yang mewakili URI yang diinginkan dari sumber daya yang disimpan dalam SVG yang dihasilkan. Jika pemrosesan untuk file ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter itu sendiri, bukan dalam kode khusus, silakan atur dalam kode khusus flag 'CustomProcessingCancelled' pada variabel parameter 'imageSavingInfo'. Ini memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter sendiri seolah-olah tidak ada kode khusus eksternal. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Proses halaman dengan beberapa thread. |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | Menentukan apakah akan mengubah skala dokumen output dari poin tipografi ke piksel. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | Opsi ini menentukan apakah akan dibuat direktori target (jika belum ada) dengan nama yang sama dengan file output yang diminta, alih-alih file output itu sendiri. Dengan cara ini, direktori akan berisi semua gambar SVG output dari halaman (seperti dijelaskan di bawah). Jika tidak, file output halaman selain yang pertama akan dibuat tepat di direktori yang diminta sebagai file output utama, tetapi akan memiliki akhiran nama file _[2...n], yang ditentukan oleh nomor halaman, misalnya jika Anda menentukan file output \"C:\\AsposeTests\\output.svg\" dan output akan berisi beberapa file SVG halaman, maka file halaman juga akan dibuat di direktori \"C:\\AsposeTests\\\" dan memiliki nama 'output.svg', 'output_2.svg', 'output_3.svg', dll. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Terkadang PDF berisi gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang berulang yang ditempatkan berdekatan. Dalam kasus seperti itu, renderer format target (mis. MsWord untuk format DOCS) kadang menghasilkan batas yang terlihat antara bagian-bagian gambar latar belakang, karena teknik penyamaran tepi gambar (anti-aliasing) mereka berbeda dari Acrobat Reader. Jika tampak bahwa dokumen yang diekspor mengandung batas terlihat antara bagian-bagian gambar latar belakang yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan efek yang tidak diinginkan. PERHATIAN! Optimasi kualitas ini biasanya secara signifikan memperlambat konversi, jadi, harap gunakan opsi ini hanya ketika benar‑benar diperlukan. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PDF ke file SVG

```csharp
[C#]
	// Jalur ke direktori dokumen.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Jalur ke File PDF Anda.
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// Jalur ke file SVG output.
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Inisialisasi SvgSaveOptions\t
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// Simpan file SVG
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

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


