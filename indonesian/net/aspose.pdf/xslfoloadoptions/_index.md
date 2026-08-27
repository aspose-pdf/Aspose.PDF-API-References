---
title: "Kelas XslFoLoadOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.XslFoLoadOptions. Mewakili opsi untuk memuat/mengimpor file XSLFO ke dalam dokumen pdf"
type: docs
weight: 11720
url: /id/net/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions class

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
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | Jalur dasar/url dari mana jalur relatif ke sumber eksternal (jika ada) yang direferensikan dalam file SVG yang dimuat dicari. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau mengatur bendera untuk menonaktifkan semua pembatasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan melakukan operasi dengan font yang dilarang oleh lisensi font tersebut, misalnya memungkinkan menyematkan font ke dalam PDF document meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. Continue adalah tindakan default dan operasi Load berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Load harus berhenti. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Mendapatkan data xsl untuk mengonversi xml menjadi pdf document. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | XsltArgumentList untuk menyisipkan nilai ke dalam parameter xls yang ada  File XLS memiliki parameter 'animal' tanpa nilai: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); sekarang konverter mengasumsikan bahwa ada parameter 'animal' dengan nilai 'cat' dalam file XLS. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | Dokumen XSLFO sumber dapat berisi kesalahan format. Enum ini mengenumerasikan strategi yang mungkin untuk menangani kesalahan tersebut. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file XSL-FO ke file PDF

```csharp
[C#]
// Jalur ke direktori dokumen.
string dataDir = @"YOUR_DATA_DIRECTORY";

// Jalur ke File XSL-FO Anda.
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// Jalur ke file PDF output.
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// Inisialisasi XslFoLoadOptions	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // Simpan file PDF
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

* class [XmlLoadOptions](../xmlloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


