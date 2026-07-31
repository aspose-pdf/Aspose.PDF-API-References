---
title: "Kelas XmlSaveOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.XmlSaveOptions. Opsi penyimpanan untuk ekspor ke format Xml"
type: docs
weight: 11590
url: /id/net/aspose.pdf/xmlsaveoptions/
---
## XmlSaveOptions class

Opsi penyimpanan untuk mengekspor ke format Xml.

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
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah glif font akan di-cache saat menyiapkan halaman aps. Meningkatkan kinerja konversi PDF ke format lain tetapi meningkatkan konsumsi memori. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format penyimpanan data. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan Continue atau Abort. Continue adalah tindakan default dan operasi Save berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Save harus berhenti. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PDF ke file XML

```csharp
[C#]
	// Jalur ke direktori dokumen.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Jalur ke File PDF Anda.
	var pdfFile = Path.Combine(dataDir, "PDF-to-XML.pdf");

	// Jalur ke File XML output.
	var xmlFile= Path.Combine(dataDir, "PDF-to-XML.xml");
		
	using (Document pdfDocument = new Document(pdfFile)){
		// Inisialisasi XmlSaveOptions	
		XmlSaveOptions saveOptions = new XmlSaveOptions();
		
		// Simpan file XML
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

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


