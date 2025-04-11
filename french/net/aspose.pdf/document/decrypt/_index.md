---
title: Document.Decrypt
second_title: Aspose.PDF for .NET API Reference
description: Méthode Document. Décrypte le document. Appelez ensuite Save pour obtenir la version décryptée du document
type: docs
weight: 600
url: /fr/net/aspose.pdf/document/decrypt/
---
## Méthode Document.Decrypt

Décrypte le document. Appelez ensuite Save pour obtenir la version décryptée du document.

```csharp
public void Decrypt()
```

### Exemples

Le code d'exemple suivant montre comment décrypter un fichier PDF.

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

### Voir aussi

* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)