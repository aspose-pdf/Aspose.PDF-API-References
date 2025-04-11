---
title: Document.Decrypt
second_title: Aspose.PDF for .NET API Reference
description: Dokumentmetod. Avkrypterar dokumentet. Anropa sedan Spara för att få den avkrypterade versionen av dokumentet
type: docs
weight: 600
url: /sv/net/aspose.pdf/document/decrypt/
---
## Document.Decrypt metod

Avkrypterar dokumentet. Anropa sedan Spara för att få den avkrypterade versionen av dokumentet.

```csharp
public void Decrypt()
```

### Exempel

Följande exempel visar hur man avkrypterar en PDF-fil.

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

### Se Även

* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)