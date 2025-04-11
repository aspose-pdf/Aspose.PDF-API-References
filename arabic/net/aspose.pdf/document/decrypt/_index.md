---
title: Document.Decrypt
second_title: Aspose.PDF for .NET API Reference
description: طريقة الوثيقة. تقوم بفك تشفير الوثيقة. اتصل بعد ذلك بـ Save للحصول على النسخة المفككة من الوثيقة
type: docs
weight: 600
url: /ar/net/aspose.pdf/document/decrypt/
---
## Document.Decrypt method

تقوم بفك تشفير الوثيقة. اتصل بعد ذلك بـ Save للحصول على النسخة المفككة من الوثيقة.

```csharp
public void Decrypt()
```

### Examples

يعرض الكود النموذجي التالي كيفية فك تشفير ملف PDF.

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