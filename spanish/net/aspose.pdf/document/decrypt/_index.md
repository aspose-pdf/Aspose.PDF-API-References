---
title: Document.Decrypt
second_title: Aspose.PDF for .NET API Reference
description: Método del documento. Desencripta el documento. Luego llama a Guardar para obtener la versión desencriptada del documento
type: docs
weight: 600
url: /es/net/aspose.pdf/document/decrypt/
---
## Método Document.Decrypt

Desencripta el documento. Luego llama a Guardar para obtener la versión desencriptada del documento.

```csharp
public void Decrypt()
```

### Ejemplos

El siguiente código de muestra muestra cómo desencriptar un archivo PDF.

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

### Ver También

* clase [Document](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)