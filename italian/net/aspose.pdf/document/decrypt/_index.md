---
title: Document.Decrypt
second_title: Aspose.PDF for .NET API Reference
description: Metodo del documento. Decifra il documento. Chiamata, salva per ottenere la versione decifrata del documento.
type: docs
weight: 600
url: /it/net/aspose.pdf/document/decrypt/
---
## Metodo Document.Decrypt

Decripta il documento. Chiamare poi Salva per ottenere la versione decrittografata del documento.

```csharp
public void Decrypt()
```

### Esempi

Il seguente codice di esempio mostra come decriptare un file PDF.

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

### Vedi Anche

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)