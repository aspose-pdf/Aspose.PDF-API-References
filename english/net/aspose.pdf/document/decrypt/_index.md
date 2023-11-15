---
title: Document.Decrypt
second_title: Aspose.PDF for .NET API Reference
description: Document method. Decrypts the document. Call then Save to obtain decrypted version of the document
type: docs
weight: 580
url: /net/aspose.pdf/document/decrypt/
---
## Document.Decrypt method

Decrypts the document. Call then Save to obtain decrypted version of the document.

```csharp
public void Decrypt()
```

### Examples

The following sample code shows how to decrypt a PDF file.

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

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


