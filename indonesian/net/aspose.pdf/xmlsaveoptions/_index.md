---
title: Class XmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.XmlSaveOptions. Opsi penyimpanan untuk ekspor ke format Xml
type: docs
weight: 11400
url: /id/net/aspose.pdf/xmlsaveoptions/
---
## Kelas XmlSaveOptions

Opsi penyimpanan untuk ekspor ke format Xml

```csharp
public class XmlSaveOptions : SaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [XmlSaveOptions](xmlsaveoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Mendapatkan atau menetapkan nilai boolean yang menunjukkan apakah glyph font akan disimpan sementara saat menyiapkan halaman aps. Meningkatkan kinerja konversi pdf ke format lain tetapi meningkatkan konsumsi memori. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Mendapatkan atau menetapkan nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format penyimpanan data. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah akan Melanjutkan atau Membatalkan. Melanjutkan adalah tindakan default dan operasi Simpan berlanjut, namun pengguna juga dapat mengembalikan Membatalkan di mana kasus operasi Simpan harus dihentikan. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PDF ke file XML

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-XML.pdf");

	// The path to output XML File.
	var xmlFile= Path.Combine(dataDir, "PDF-to-XML.xml");
		
	using (Document pdfDocument = new Document(pdfFile)){
		// Initialize XmlSaveOptions	
		XmlSaveOptions saveOptions = new XmlSaveOptions();
		
		// Save XML file
		pdfDocument.Save(xmlFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-XML.pdf")

    ' The path to output XML File.
    Dim xmlFile = Path.Combine(dataDir, "PDF-to-XML.xml")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize XmlSaveOptions
        Dim saveOptions As XmlSaveOptions = New XmlSaveOptions()
 
        ' Save XML file
        pdfDocument.Save(xmlFile, saveOptions)
    End Using
```

### Lihat Juga

* kelas [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)