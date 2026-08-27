---
title: "Document.Decrypt"
second_title: "Aspose.PDF for .NET API 参考"
description: "Document 方法。解密文档。调用后再 Save 以获取文档的解密版本"
type: docs
weight: 620
url: /zh/net/aspose.pdf/document/decrypt/
---
## Document.Decrypt method

解密文档。调用 Save 以获取文档的解密版本。

```csharp
public void Decrypt()
```

### 示例

以下示例代码展示了如何解密 PDF 文件。

```csharp
[C#]
	// PDF 文件的路径。
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// 打开文档
	using (Document document = new Document(pdfFilePath, "YOUR_PASSWORD"))
	{
		// 解密 PDF
		document.Decrypt();

		// 保存已更新的 PDF
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

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


