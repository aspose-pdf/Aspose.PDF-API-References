---
title: Document.Optimize
second_title: Aspose.PDF for .NET API Reference
description: 文档方法。线性化文档，以便尽可能快速地打开第一页，尽可能快速地显示下一页或通过链接跟随到下一页，随着数据通过慢通道传输时逐步显示页面，首先显示最有用的数据，允许用户交互，例如在整个页面接收和显示之前执行跟随链接的操作。调用此方法实际上并不会保存文档。相反，文档只是准备好具有优化结构，然后调用保存以获取优化文档。
type: docs
weight: 750
url: /zh/net/aspose.pdf/document/optimize/
---
## Document.Optimize 方法

线性化文档，以便 - 尽可能快速地打开第一页； - 尽可能快速地显示下一页或通过链接跟随到下一页； - 当页面的数据通过慢通道传输时逐步显示页面（首先显示最有用的数据）； - 允许用户交互，例如在整个页面接收和显示之前执行跟随链接的操作。调用此方法实际上并不会保存文档。相反，文档只是准备好具有优化结构，然后调用保存以获取优化文档。

```csharp
public void Optimize()
```

### 示例

以下示例演示如何为网络优化 PDF 文档。

```csharp
[C#]
	// The path to your PDF File.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Open document
	using (Document pdfDocument = new Document(pdfFilePath))
	{

	// Optimize for web
	pdfDocument.Optimize();

	// Save output document
	pdfDocument.Save(pdfFilePath);
	}
```

```csharp
[VB.NET]

    ' The path to your PDF File.
    Dim pdfFilePath As String = "YOUR_PDF_FILE_PATH"
	
    ' Open document
    Using pdfDocument As Document = New Document(pdfFilePath)

        ' Optimize for web
        pdfDocument.Optimize()

        ' Save output document
        pdfDocument.Save(pdfFilePath)
    End Using
```

### 另请参阅

* 类 [Document](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)