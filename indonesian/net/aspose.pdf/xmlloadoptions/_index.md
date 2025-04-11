---
title: Class XmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.XmlLoadOptions. Mewakili opsi untuk memuat/mengimpor file XML ke dalam dokumen pdf
type: docs
weight: 11390
url: /id/net/aspose.pdf/xmlloadoptions/
---
## Kelas XmlLoadOptions

Mewakili opsi untuk memuat/mengimpor file XML ke dalam dokumen pdf.

```csharp
public class XmlLoadOptions : LoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions/#constructor)() | Membuat objek `XmlLoadOptions` tanpa data xsl. |
| [XmlLoadOptions](xmlloadoptions/#constructor_1)(Stream) | Membuat objek `XmlLoadOptions` dengan data xsl. |
| [XmlLoadOptions](xmlloadoptions/#constructor_2)(string) | Membuat objek `XmlLoadOptions` dengan data xsl. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau mengatur flag untuk menonaktifkan batasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan untuk melakukan operasi dengan font yang dilarang oleh lisensi font ini, misalnya memungkinkan untuk menyematkan font ke dalam dokumen PDF meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Melanjutkan atau Menghentikan. Melanjutkan adalah tindakan default dan operasi Muat berlanjut, namun pengguna juga dapat mengembalikan Menghentikan di mana operasi Muat harus dihentikan. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Mendapatkan data xsl untuk mengonversi xml menjadi dokumen pdf. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file XML menjadi file PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your XML File.
	string xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf");

	// Initialize XmlLoadOptions	
	XmlLoadOptions xmlLoadOptions = new XmlLoadOptions();
		
	using (Document pdfDocument = new Document(xmlFile, xmlLoadOptions))
	{
	 
		// Save XML file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XML File.
    Dim xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf")
 
    ' Initialize XmlLoadOptions
    Dim xmlLoadOptions As XmlLoadOptions = New XmlLoadOptions()
 
    Using pdfDocument As Document = New Document(xmlFile, xmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Lihat Juga

* kelas [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)