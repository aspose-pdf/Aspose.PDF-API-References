---
title: Class XslFoLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.XslFoLoadOptions. Mewakili opsi untuk memuat/mengimpor file XSLFO ke dalam dokumen pdf
type: docs
weight: 11530
url: /id/net/aspose.pdf/xslfoloadoptions/
---
## Kelas XslFoLoadOptions

Mewakili opsi untuk memuat/mengimpor file XSL-FO ke dalam dokumen pdf.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | Membuat objek `XslFoLoadOptions` tanpa data xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | Membuat objek `XslFoLoadOptions` dengan data xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | Membuat objek `XslFoLoadOptions` dengan data xsl. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | Jalur/url dasar dari mana jalur relatif ke sumber daya eksternal (jika ada) yang dirujuk dalam file SVG yang dimuat dicari. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau mengatur bendera untuk menonaktifkan batasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan untuk melakukan operasi dengan font yang dilarang oleh lisensi font ini, misalnya memungkinkan untuk menyematkan font ke dalam dokumen PDF meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan baik Lanjutkan atau Hentikan. Lanjutkan adalah tindakan default dan operasi Muat berlanjut, namun pengguna juga dapat mengembalikan Hentikan di mana kasus operasi Muat harus dihentikan. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Mendapatkan data xsl untuk mengonversi xml menjadi dokumen pdf. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | XsltArgumentList untuk menyisipkan nilai ke dalam parameter xls yang ada. File XLS memiliki parameter 'animal' tanpa nilai: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); sekarang konverter menganggap bahwa ada parameter 'animal' dengan nilai 'cat' dalam file XLS. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | Dokumen XSLFO sumber dapat mengandung kesalahan format. Enum ini mencantumkan strategi yang mungkin untuk menangani kesalahan tersebut. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file XSL-FO ke file PDF

```csharp
[C#]
// The path to the documents directory.
string dataDir = @"YOUR_DATA_DIRECTORY";

// The path to your XSL-FO File.
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// The path to output PDF File.
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// Initialize XslFoLoadOptions	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // Save PDF file
    pdfDocument.Save(pdfFile);
}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XSL-FO File.
    Dim xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf")
 
    ' Initialize XslFoLoadOptions  
    Dim xslFoLoadOptions As XslFoLoadOptions = New XslFoLoadOptions()
 
    Using pdfDocument As Document = New Document(xslFoFile, xslFoLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Lihat Juga

* kelas [XmlLoadOptions](../xmlloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)