---
title: Class DocSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.DocSaveOptions. Opsi simpan untuk ekspor ke format Doc
type: docs
weight: 3750
url: /id/net/aspose.pdf/docsaveoptions/
---
## Kelas DocSaveOptions

Opsi simpan untuk ekspor ke format Doc

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend/) { get; set; } | Gunakan paragraf atau pemisah baris |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | Mendefinisikan ukuran batch jika konversi batch berlaku untuk pasangan format sumber dan tujuan. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah glyph font akan disimpan sementara menyiapkan halaman aps. Meningkatkan kinerja konversi pdf ke format lain tetapi meningkatkan konsumsi memori. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | Mendapatkan atau mengatur konversi untuk font Type3. Dalam font Type 3, glyph harus didefinisikan oleh aliran operator grafis. Ini berarti bahwa dalam output DOC/DOCX kita melihat gambar alih-alih teks. Atur bendera ini ke true untuk mengonversi font Type3 ke TTF dan mendapatkan teks dalam file yang dihasilkan. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Atribut ini mengaktifkan fungsionalitas untuk mengekstrak gambar atau teks untuk dokumen PDF dengan sublayer OCR. |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | Format output |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | Resolusi X gambar yang dikonversi. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | Resolusi Y gambar yang dikonversi. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | Parameter ini digunakan untuk mengelompokkan baris teks menjadi paragraf. Menentukan seberapa jauh dua baris teks relatif dapat dipisahkan. Ditentukan dalam ratusan persen dari tinggi baris teks. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | Mendefinisikan jalur (nama file atau nama direktori) untuk menyimpan data sementara saat mengonversi dalam mode simpan memori. |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | Mode pengenalan. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | Aktifkan pengenalan peluru |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | Dalam Pdf, kata-kata dapat diwakili secara internal dengan operator yang mencetak kata-kata dengan mencetak huruf atau suku kata mereka secara independen. Jadi, untuk mendeteksi kata-kata kadang-kadang kita perlu mendeteksi kelompok karakter independen yang sebenarnya adalah kata-kata. Pengaturan ini mendefinisikan lebar ruang antara elemen teks (huruf, suku kata) yang harus diperlakukan sebagai jarak antara kata-kata selama pengenalan kata dalam PDF sumber. (keberadaan ruang kosong setidaknya dengan lebar ini antara huruf berarti bahwa elemen tekstual termasuk dalam kata yang berbeda). Ini dinormalkan ke ukuran font - 1.0 berarti 100% dari ukuran font kata yang diharapkan. PERHATIAN! Ini hanya digunakan dalam kasus ketika PDF sumber mengandung font yang jarang digunakan yang optimal nilainya tidak dapat dihitung dari font. Jadi, dalam sebagian besar kasus parameter ini tidak mengubah apa pun dalam dokumen hasil. |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | Mendapatkan atau mengatur prosedur untuk menyimpan ulang font. Jika diatur ke true, kami memuat ulang font di setiap halaman untuk menghindari pengaruh properti font sebelumnya dan memuat font yang baru dibuat dari awal. Atur opsi ini ke false jika Anda ingin meningkatkan kinerja. Nilai default adalah true; |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format penyimpanan data. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Melanjutkan atau Membatalkan. Melanjutkan adalah tindakan default dan operasi Simpan dilanjutkan, namun pengguna juga dapat mengembalikan Membatalkan di mana kasus operasi Simpan harus dihentikan. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | Handler ini dapat digunakan untuk menangani peristiwa kemajuan konversi, misalnya, dapat digunakan untuk menampilkan bilah kemajuan atau pesan tentang jumlah halaman yang sedang diproses, contoh kode handler yang menunjukkan kemajuan di konsol adalah: |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Proses halaman dalam beberapa utas. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Terkadang PDF mengandung gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang yang sama yang ditumpuk satu di samping yang lain. Dalam kasus seperti itu, perender format target (misalnya MsWord untuk format DOCS) kadang-kadang menghasilkan batas yang terlihat antara bagian gambar latar belakang, karena teknik mereka dalam menghaluskan tepi gambar (anti-aliasing) berbeda dari Acrobat Reader. Jika terlihat bahwa dokumen yang diekspor mengandung batas yang terlihat antara bagian gambar latar belakang yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan efek yang tidak diinginkan itu. PERHATIAN! Optimasi kualitas ini biasanya secara signifikan memperlambat konversi, jadi, silakan gunakan opsi ini hanya ketika benar-benar diperlukan. |

### Contoh

Contoh berikut menunjukkan cara mengonversi file PDF ke file DOC atau DOCX

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// The path to output DOC or DOCX File.
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// Set the recognition mode as Flow
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// Set the Horizontal proximity as 2.5
			RelativeHorizontalProximity = 2.5f,
			// Enable the value to recognize bullets during conversion process
			RecognizeBullets = true
		};
		pdfDocument.Save(docFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf")
    
	' The path to output DOC or DOCX File.
    Dim docFile = Path.Combine(dataDir, "PDF-to-DOC.doc")
 
    Using pdfDocument As Document = New Document(pdfFile)
        Dim saveOptions As DocSaveOptions = New DocSaveOptions With {
          .Format = DocSaveOptions.DocFormat.Doc,
            ' Set the recognition mode as Flow
            .Mode = DocSaveOptions.RecognitionMode.Flow,
            ' Set the Horizontal proximity as 2.5
            .RelativeHorizontalProximity = 2.5,
            ' Enable the value to recognize bullets during conversion process
            .RecognizeBullets = True
        }
        pdfDocument.Save(docFile, saveOptions)
    End Using
```

### Lihat Juga

* kelas [UnifiedSaveOptions](../unifiedsaveoptions/)
* antarmuka [IPipelineOptions](../ipipelineoptions/)
* ruang nama [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)