---
title: Document.Decrypt
second_title: Aspose.PDF for .NET API Reference
description: Método do documento. Descriptografa o documento. Chame então Save para obter a versão descriptografada do documento
type: docs
weight: 600
url: /pt/net/aspose.pdf/document/decrypt/
---
## Método Document.Decrypt

Descriptografa o documento. Chame então Save para obter a versão descriptografada do documento.

```csharp
public void Decrypt()
```

### Exemplos

O seguinte código de exemplo mostra como descriptografar um arquivo PDF.

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

### Veja Também

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)