---
title: "Document.Decrypt"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Document. Mendekripsi dokumen. Panggil kemudian Save untuk memperoleh versi dokumen yang didekripsi"
type: docs
weight: 620
url: /id/net/aspose.pdf/document/decrypt/
---
## Document.Decrypt method

Mendekripsi document. Panggil kemudian Save untuk memperoleh versi document yang telah didekripsi.

```csharp
public void Decrypt()
```

### Contoh

Kode contoh berikut menunjukkan cara mendekripsi file PDF.

```csharp
[C#]
	// Jalur ke File PDF Anda.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Buka dokumen
	using (Document document = new Document(pdfFilePath, "YOUR_PASSWORD"))
	{
		// Dekripsi PDF
		document.Decrypt();

		// Simpan PDF yang diperbarui
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

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


