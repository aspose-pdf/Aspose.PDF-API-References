---
title: "Kelas DocSaveOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.DocSaveOptions. Opsi penyimpanan untuk ekspor ke format Doc"
type: docs
weight: 3870
url: /id/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class

Opsi penyimpanan untuk ekspor ke format Doc

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
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend/) { get; set; } | Gunakan paragraf atau jeda baris |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | Mendefinisikan ukuran batch jika konversi batch berlaku untuk pasangan format sumber dan tujuan. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah glif font akan di-cache saat menyiapkan halaman aps. Meningkatkan kinerja konversi PDF ke format lain tetapi meningkatkan konsumsi memori. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | Mendapatkan atau mengatur konversi untuk font Type3. Pada font Type 3, glif harus didefinisikan oleh aliran operator grafis. Ini berarti bahwa dalam output DOC/DOCX kita melihat gambar alih-alih teks. Atur flag ini ke true untuk mengonversi font Type3 ke TTF dan mendapatkan teks dalam file yang dihasilkan. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Atribut ini mengaktifkan fungsionalitas untuk mengekstrak gambar atau teks dari dokumen PDF dengan sublayer OCR. |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | Format output |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | Resolusi X gambar yang dikonversi. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | Resolusi Y gambar yang dikonversi. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | Parameter ini digunakan untuk mengelompokkan baris teks menjadi paragraf. Menentukan seberapa jauh dua baris teks relatif dapat dipisahkan. Ditentukan dalam ratusan persen dari tinggi baris teks. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | Mendefinisikan jalur (nama file atau nama direktori) untuk menyimpan data sementara saat mengonversi dalam mode penyimpanan memori. |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | Mode pengenalan. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | Aktifkan pengenalan bullet |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | Dalam Pdf, kata dapat direpresentasikan secara internal dengan operator yang mencetak kata dengan mencetak masing-masing huruf atau suku katanya secara terpisah. Jadi, untuk mendeteksi kata terkadang kita perlu mendeteksi kelompok karakter independen yang sebenarnya merupakan kata. Pengaturan ini menentukan lebar ruang antara elemen teks (huruf, suku kata) yang harus diperlakukan sebagai jarak antar kata selama pengenalan kata dalam PDF sumber. (keberadaan ruang kosong setidaknya dengan lebar ini antara huruf berarti elemen teks tersebut termasuk dalam kata yang berbeda). Nilainya dinormalkan terhadap ukuran font – 1,0 berarti 100% dari ukuran font kata yang dimaksud. PERHATIAN! Ini hanya digunakan dalam kasus ketika PDF sumber berisi font khusus yang jarang digunakan sehingga nilai optimal tidak dapat dihitung dari font. Jadi, dalam sebagian besar kasus parameter ini tidak mengubah apa pun dalam dokumen hasil. |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | Mendapatkan atau mengatur prosedur untuk menyimpan ulang font. Jika diatur ke true, kami memuat ulang font pada setiap halaman untuk menghindari pengaruh properti font sebelumnya dan memuat font yang baru dibuat dari awal. Atur opsi ini ke false jika Anda ingin meningkatkan kinerja. Nilai default adalah true; |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format penyimpanan data. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan Continue atau Abort. Continue adalah tindakan default dan operasi Save berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Save harus berhenti. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | Handler ini dapat digunakan untuk menangani peristiwa kemajuan konversi, misalnya dapat digunakan untuk menampilkan bilah kemajuan atau pesan tentang jumlah halaman yang sedang diproses, contoh kode handler yang menampilkan kemajuan di konsol adalah: |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Proses halaman dengan beberapa thread. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Terkadang PDF berisi gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang berulang yang ditempatkan berdekatan. Dalam kasus seperti itu, renderer format target (mis. MsWord untuk format DOCS) kadang menghasilkan batas yang terlihat antara bagian-bagian gambar latar belakang, karena teknik penyamaran tepi gambar (anti-aliasing) mereka berbeda dari Acrobat Reader. Jika tampak bahwa dokumen yang diekspor mengandung batas terlihat antara bagian-bagian gambar latar belakang yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan efek yang tidak diinginkan. PERHATIAN! Optimasi kualitas ini biasanya secara signifikan memperlambat konversi, jadi, harap gunakan opsi ini hanya ketika benar‑benar diperlukan. |

### Contoh

Contoh berikut menunjukkan cara mengonversi file PDF ke file DOC atau DOCX

```csharp
[C#]
	// Jalur ke direktori dokumen.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Jalur ke File PDF Anda.
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// Jalur ke file DOC atau DOCX output.
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// Atur mode pengenalan menjadi Flow
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// Atur kedekatan Horizontal menjadi 2.5
			RelativeHorizontalProximity = 2.5f,
			// Aktifkan nilai untuk mengenali bullet selama proses konversi
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

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


