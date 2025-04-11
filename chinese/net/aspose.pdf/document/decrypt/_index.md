---
title: Document.Decrypt
second_title: Aspose.PDF for .NET API Reference
description: Document 方法。解密文档。然后调用 Save 以获取文档的解密版本
type: docs
weight: 600
url: /zh/net/aspose.pdf/document/decrypt/
---
## Document.Decrypt 方法

解密文档。然后调用 Save 以获取文档的解密版本。

```csharp
public void Decrypt()
```

### 示例

以下示例代码演示如何解密 PDF 文件。

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

### 另请参阅

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)