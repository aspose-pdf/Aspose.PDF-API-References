---
title: Document.Decrypt
second_title: Aspose.PDF for .NET API Reference
description: Dokumentmethode. Entschlüsselt das Dokument. Rufen Sie dann Speichern auf, um die entschlüsselte Version des Dokuments zu erhalten.
type: docs
weight: 600
url: /de/net/aspose.pdf/document/decrypt/
---
## Document.Decrypt-Methode

Entschlüsselt das Dokument. Rufen Sie dann Speichern auf, um die entschlüsselte Version des Dokuments zu erhalten.

```csharp
public void Decrypt()
```

### Beispiele

Der folgende Beispielcode zeigt, wie man eine PDF-Datei entschlüsselt.

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

### Siehe auch

* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)