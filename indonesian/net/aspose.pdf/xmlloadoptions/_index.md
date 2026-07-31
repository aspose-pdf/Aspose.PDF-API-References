---
title: "Kelas XmlLoadOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.XmlLoadOptions. Menyatakan opsi untuk memuat/mengimpor file XML ke dalam pdf document"
type: docs
weight: 11580
url: /id/net/aspose.pdf/xmlloadoptions/
---
## XmlLoadOptions class

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
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau mengatur bendera untuk menonaktifkan semua pembatasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan melakukan operasi dengan font yang dilarang oleh lisensi font tersebut, misalnya memungkinkan menyematkan font ke dalam PDF document meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. Continue adalah tindakan default dan operasi Load berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Load harus berhenti. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Mendapatkan data xsl untuk mengonversi xml menjadi pdf document. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file XML ke file PDF

```csharp
[C#]
	// Jalur ke direktori dokumen.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Jalur ke File XML Anda.
	string xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml");

	// Jalur ke file PDF output.
	string pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf");

	// Inisialisasi XmlLoadOptions	
	XmlLoadOptions xmlLoadOptions = new XmlLoadOptions();
		
	using (Document pdfDocument = new Document(xmlFile, xmlLoadOptions))
	{
	 
		// Simpan file XML
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

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


