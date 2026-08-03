---
title: "Document.Decrypt"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Document-metod. Dekrypterar dokumentet. Anropa sedan Save för att få den dekrypterade versionen av dokumentet"
type: docs
weight: 620
url: /sv/net/aspose.pdf/document/decrypt/
---
## Document.Decrypt method

Dekrypterar document. Anropa sedan Save för att få den dekrypterade versionen av document.

```csharp
public void Decrypt()
```

### Exempel

Följande exempelprogram visar hur man dekrypterar en PDF-fil.

```csharp
[C#]
	// Sökvägen till din PDF‑fil.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Öppna dokument
	using (Document document = new Document(pdfFilePath, "YOUR_PASSWORD"))
	{
		// Dekryptera PDF
		document.Decrypt();

		// Spara uppdaterad PDF
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

### Se även

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


