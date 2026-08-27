---
title: "Kelas XpsSaveOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.XpsSaveOptions. Opsi penyimpanan untuk mengekspor ke format Xps"
type: docs
weight: 11710
url: /id/net/aspose.pdf/xpssaveoptions/
---
## XpsSaveOptions class

Opsi penyimpanan untuk mengekspor ke format Xps

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
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah glif font akan di-cache saat menyiapkan halaman aps. Meningkatkan kinerja konversi PDF ke format lain tetapi meningkatkan konsumsi memori. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [DefaultFont](../../aspose.pdf/xpssaveoptions/defaultfont/) { get; set; } | Mendapatkan/mengatur nama font default. Digunakan jika nama font yang disematkan tidak ditemukan di sistem. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Atribut ini mengaktifkan fungsionalitas untuk mengekstrak gambar atau teks dari dokumen PDF dengan sublayer OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format penyimpanan data. |
| [SaveTransparentTexts](../../aspose.pdf/xpssaveoptions/savetransparenttexts/) { get; set; } | Menunjukkan apakah akan mempertahankan teks transparan (hasil OCR). |
| [UseEmbeddedTrueTypeFonts](../../aspose.pdf/xpssaveoptions/useembeddedtruetypefonts/) { get; set; } | Mendapatkan/mengatur flag untuk menggunakan font TrueType yang disematkan. Menghindari penggunaan font TrueType yang disematkan dapat mengurangi waktu konversi. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan Continue atau Abort. Continue adalah tindakan default dan operasi Save berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Save harus berhenti. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Proses halaman dengan beberapa thread. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Terkadang PDF berisi gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang berulang yang ditempatkan berdekatan. Dalam kasus seperti itu, renderer format target (mis. MsWord untuk format DOCS) kadang menghasilkan batas yang terlihat antara bagian-bagian gambar latar belakang, karena teknik penyamaran tepi gambar (anti-aliasing) mereka berbeda dari Acrobat Reader. Jika tampak bahwa dokumen yang diekspor mengandung batas terlihat antara bagian-bagian gambar latar belakang yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan efek yang tidak diinginkan. PERHATIAN! Optimasi kualitas ini biasanya secara signifikan memperlambat konversi, jadi, harap gunakan opsi ini hanya ketika benar‑benar diperlukan. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PDF ke file XPS

```csharp
[C#]
	// Jalur ke direktori dokumen.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Jalur ke File PDF Anda
	var pdfFile = Path.Combine(dataDir, "PDF-to-XPS.pdf");

	// Jalur ke File XPS Anda
	var xpsFile= Path.Combine(dataDir, "PDF-to-XPS.xps");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Inisialisasi XpsSaveOptions	
		XpsSaveOptions saveOptions = new XpsSaveOptions();
		
		// Simpan file XPS
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

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


