---
title: "Document.Decrypt"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Document. Decripta il documento. Chiama poi Save per ottenere la versione decrittata del documento"
type: docs
weight: 620
url: /it/net/aspose.pdf/document/decrypt/
---
## Document.Decrypt method

Decripta il documento. Chiama poi Save per ottenere la versione decrittata del documento.

```csharp
public void Decrypt()
```

### Esempi

Il seguente codice di esempio mostra come decrittare un file PDF.

```csharp
[C#]
	// Il percorso al tuo file PDF.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Apri documento
	using (Document document = new Document(pdfFilePath, "YOUR_PASSWORD"))
	{
		// Decrittare PDF
		document.Decrypt();

		// Salva PDF aggiornato
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

### Vedi anche

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


