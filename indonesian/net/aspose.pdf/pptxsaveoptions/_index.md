---
title: "Kelas PptxSaveOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.PptxSaveOptions class. Opsi penyimpanan untuk ekspor ke format SVG"
type: docs
weight: 9630
url: /id/net/aspose.pdf/pptxsaveoptions/
---
## PptxSaveOptions class

Opsi penyimpanan untuk mengekspor ke format SVG

```csharp
public class PptxSaveOptions : UnifiedSaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PptxSaveOptions](pptxsaveoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah glif font akan di-cache saat menyiapkan halaman aps. Meningkatkan kinerja konversi PDF ke format lain tetapi meningkatkan konsumsi memori. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [CustomProgressHandler](../../aspose.pdf/pptxsaveoptions/customprogresshandler/) { get; set; } | Handler ini dapat digunakan untuk menangani peristiwa kemajuan konversi, misalnya dapat digunakan untuk menampilkan bilah kemajuan atau pesan tentang jumlah halaman yang sedang diproses, contoh kode handler yang menampilkan kemajuan di konsol adalah: |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Atribut ini mengaktifkan fungsionalitas untuk mengekstrak gambar atau teks dari dokumen PDF dengan sublayer OCR. |
| [ImageResolution](../../aspose.pdf/pptxsaveoptions/imageresolution/) { get; set; } | Mendapatkan atau mengatur resolusi gambar (dpi). Default adalah 192 dpi. |
| [OptimizeTextBoxes](../../aspose.pdf/pptxsaveoptions/optimizetextboxes/) { get; set; } | Mengaktifkan/menonaktifkan pengenalan kolom teks |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format penyimpanan data. |
| [SeparateImages](../../aspose.pdf/pptxsaveoptions/separateimages/) { get; set; } | Jika disetel ke true maka gambar dipisahkan dari semua grafik lainnya |
| [SlidesAsImages](../../aspose.pdf/pptxsaveoptions/slidesasimages/) { get; set; } | Jika disetel ke true maka semua konten dikenali sebagai gambar (satu per halaman) |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan Continue atau Abort. Continue adalah tindakan default dan operasi Save berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Save harus berhenti. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Proses halaman dengan beberapa thread. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Terkadang PDF berisi gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang berulang yang ditempatkan berdekatan. Dalam kasus seperti itu, renderer format target (mis. MsWord untuk format DOCS) kadang menghasilkan batas yang terlihat antara bagian-bagian gambar latar belakang, karena teknik penyamaran tepi gambar (anti-aliasing) mereka berbeda dari Acrobat Reader. Jika tampak bahwa dokumen yang diekspor mengandung batas terlihat antara bagian-bagian gambar latar belakang yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan efek yang tidak diinginkan. PERHATIAN! Optimasi kualitas ini biasanya secara signifikan memperlambat konversi, jadi, harap gunakan opsi ini hanya ketika benar‑benar diperlukan. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PDF ke file PPT atau PPTX

```csharp
[C#]
	// Jalur ke direktori dokumen.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Jalur ke File PDF Anda.
	var pdfFile = Path.Combine(dataDir, "PDF-to-PPTX.pdf");

	// Jalur ke file PPT atau PPTX Anda.
	var pptxFile = Path.Combine(dataDir, "PDF-to-PPTX.pptx");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Inisialisasi PptxSaveOptions	
		PptxSaveOptions saveOptions = new PptxSaveOptions();
		
		// Simpan file PPT atau PPTX
		pdfDocument.Save(pptxFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-PPTX.pdf")
    ' The path to your PPT or PPTX File.
    Dim pptxFile = Path.Combine(dataDir, "PDF-to-PPTX.pptx")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize PptxSaveOptions    
        Dim saveOptions As PptxSaveOptions = New PptxSaveOptions()
 
        ' Save PPT or PPTX file
        pdfDocument.Save(pptxFile, saveOptions)
    End Using
```

### Lihat Juga

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


