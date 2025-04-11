---
title: Document.Decrypt
second_title: Aspose.PDF for .NET API Reference
description: Metode dokumen. Mendekripsi dokumen. Panggil kemudian Simpan untuk mendapatkan versi dokumen yang terdekripsi
type: docs
weight: 600
url: /id/net/aspose.pdf/document/decrypt/
---
## Metode Document.Decrypt

Mendekripsi dokumen. Panggil kemudian Simpan untuk mendapatkan versi dokumen yang terdekripsi.

```csharp
public void Decrypt()
```

### Contoh

Kode sampel berikut menunjukkan cara mendekripsi file PDF.

```csharp
[C#]
	// The path to your PDF File.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Open document
	using (Document document = new Document(pdfFilePath, "YOUR_PASSWORD"))
	{
		// Decrypt PDF
		document.Decrypt();

		// Save updated PDF
		document.Save(pdfFilePath);
	}
```

```csharp
[VB.NET]

    ' The path to your PDF File.
    Dim pdfFilePath As String = "YOUR_PDF_FILE_PATH"

    ' Open document
    Using document As Document = New Document(pdfFilePath, "YOUR_PASSWORD")

        ' Decrypt PDF
        document.Decrypt()

        ' Save updated PDF
        document.Save(pdfFilePath)
    End Using
```

### Lihat Juga

* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)