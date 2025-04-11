---
title: Document.Decrypt
second_title: Aspose.PDF for .NET API Reference
description: Метод документа. Расшифровывает документ. Затем вызовите Save, чтобы получить расшифрованную версию документа
type: docs
weight: 600
url: /ru/net/aspose.pdf/document/decrypt/
---
## Метод Document.Decrypt

Расшифровывает документ. Затем вызовите Save, чтобы получить расшифрованную версию документа.

```csharp
public void Decrypt()
```

### Примеры

Следующий пример кода показывает, как расшифровать PDF файл.

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

### См. также

* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)