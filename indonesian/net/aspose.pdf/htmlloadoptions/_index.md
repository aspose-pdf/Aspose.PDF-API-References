---
title: "Class HtmlLoadOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.HtmlLoadOptions class. Mewakili opsi untuk memuat/mengimpor file html ke dalam dokumen pdf"
type: docs
weight: 5660
url: /id/net/aspose.pdf/htmlloadoptions/
---
## HtmlLoadOptions class

Mewakili opsi untuk memuat/mengimpor file html ke dalam dokumen pdf.

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | Membuat opsi pemuatan untuk mengonversi html menjadi dokumen pdf dengan jalur dasar kosong. |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | Membuat opsi pemuatan untuk mengonversi html menjadi dokumen pdf dengan jalur dasar yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | Jalur/URL dasar untuk file html. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau mengatur bendera untuk menonaktifkan semua pembatasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan melakukan operasi dengan font yang dilarang oleh lisensi font tersebut, misalnya memungkinkan menyematkan font ke dalam PDF document meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | Mendapatkan atau mengatur tipe media yang mungkin digunakan selama rendering. |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | Mendapatkan atau mengatur atribut yang menentukan enkoding yang digunakan untuk dokumen ini pada saat parsing. Jika atribut ini null, enkoding akan ditentukan dari atribut set karakter dokumen. |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | Mendapatkan atau mengatur penyematan font ke dokumen hasil |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | Mendapatkan atau mengatur flag yang menentukan bahwa aturan @page yang didefinisikan dalam css akan menimpa nilai yang didefinisikan dalam PageInfo. |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | Mendapatkan atau mengatur rendering seluruh dokumen ke satu halaman |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | Mendapatkan atau mengatur info halaman dokumen |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | Mendapatkan atau mengatur opsi tata letak. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. Continue adalah tindakan default dan operasi Load berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Load harus berhenti. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | Terkadang diperlukan untuk menghindari penggunaan pemuat internal sumber daya eksternal (seperti gambar atau CSS) dan menyediakan metode khusus yang akan mengambil sumber daya yang diminta dari suatu tempat. Misalnya, selama penggunaan Aspose.PDF di cloud akses langsung ke file yang direferensikan tidak memungkinkan: dalam kasus seperti itu kode khusus yang dimasukkan ke dalam metode khusus harus digunakan, dan delegasi yang merujuk ke metode tersebut harus ditetapkan ke atribut ini. |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | Jika pemuatan data eksternal yang direferensikan dalam HTML memerlukan kredensial, Anda dapat menaruhnya ke parameter ini - mereka akan digunakan selama pemuatan sumber daya eksternal |

## Contoh

Contoh berikut menunjukkan cara mengonversi file HTML ke file PDF

```csharp
[C#]
	// Jalur ke direktori dokumen.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Jalur ke File HTML Anda.
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// Jalur ke file PDF output.
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// Inisialisasi HtmlLoadOptions	
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// Simpan file PDF
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your HTML File.
    Dim htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf")
 
    ' Initialize HtmlLoadOptions    
    Dim htmlLoadOptions As HtmlLoadOptions = New HtmlLoadOptions()
 
    Using pdfDocument As Document = New Document(htmlFile, htmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Lihat Juga

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


