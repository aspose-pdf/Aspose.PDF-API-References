---
title: Class HtmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.HtmlLoadOptions. Mewakili opsi untuk memuat/mengimpor file html ke dalam dokumen pdf
type: docs
weight: 5530
url: /id/net/aspose.pdf/htmlloadoptions/
---
## Kelas HtmlLoadOptions

Mewakili opsi untuk memuat/mengimpor file html ke dalam dokumen pdf.

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | Membuat opsi muat untuk mengonversi html menjadi dokumen pdf dengan jalur dasar kosong. |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | Membuat opsi muat untuk mengonversi html menjadi dokumen pdf dengan jalur dasar yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | Jalur/url dasar untuk file html. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau menetapkan flag untuk menonaktifkan batasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan untuk melakukan operasi dengan font yang dilarang oleh lisensi font ini, misalnya memungkinkan untuk menyematkan font ke dalam dokumen PDF meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | Mendapatkan atau menetapkan jenis media yang mungkin digunakan selama rendering. |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | Mendapatkan atau menetapkan atribut yang menentukan pengkodean yang digunakan untuk dokumen ini pada saat parsing. Jika atribut ini null, pengkodean akan ditentukan dari atribut set karakter dokumen. |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | Mendapatkan atau menetapkan penyematan font ke dokumen hasil |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | Mendapatkan atau menetapkan flag yang menentukan bahwa aturan @page yang didefinisikan dalam css akan menggantikan nilai yang ditentukan dalam PageInfo. |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | Mendapatkan atau menetapkan rendering semua dokumen ke satu halaman |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | Mendapatkan atau menetapkan informasi halaman dokumen |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | Mendapatkan atau menetapkan opsi tata letak. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan baik Lanjutkan atau Hentikan. Lanjutkan adalah tindakan default dan operasi Muat berlanjut, namun pengguna juga dapat mengembalikan Hentikan di mana kasus operasi Muat harus dihentikan. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | Terkadang perlu untuk menghindari penggunaan pemuat internal sumber daya eksternal (seperti gambar atau CSS) dan menyediakan metode kustom yang akan mendapatkan sumber daya yang diminta dari suatu tempat. Misalnya, selama penggunaan Aspose.PDF di cloud, akses langsung ke file yang dirujuk tidak mungkin: dalam kasus seperti itu, beberapa kode kustom yang dimasukkan ke dalam metode khusus harus digunakan, dan delegasi yang merujuk metode tersebut harus ditugaskan ke atribut ini. |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | Jika pemuatan data eksternal yang dirujuk dalam HTML memerlukan kredensial, Anda dapat menempatkannya ke dalam parameter ini - mereka akan digunakan selama pemuatan sumber daya eksternal |

## Contoh

Contoh berikut menunjukkan cara mengonversi file HTML ke file PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your HTML File.
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// Initialize HtmlLoadOptions	
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// Save PDF file
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

* kelas [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)