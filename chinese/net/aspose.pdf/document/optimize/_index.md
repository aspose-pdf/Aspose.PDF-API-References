---
title: "Document.Optimize"
second_title: "Aspose.PDF for .NET API 参考"
description: "Document 方法。线性化文档，以便  尽快打开首页  尽快显示下一页或通过链接跳转到下一页  当页面数据通过慢速通道传输时，逐步增量显示页面  优先显示最有用的数据  允许用户交互，例如在整个页面尚未接收并显示之前就可以点击链接。调用此方法并不会真正保存文档。相反，文档仅被准备为优化后的结构，需要随后调用 Save 才能得到优化后的文档。"
type: docs
weight: 770
url: /zh/net/aspose.pdf/document/optimize/
---
## Document.Optimize method

线性化文档，以实现以下目标：- 尽快打开首页；- 尽快显示下一页或通过链接跳转到下一页；- 当页面数据通过慢速通道分段传输时，逐步显示页面（优先显示最有用的数据）；- 允许用户交互（如点击链接）在整个页面接收并显示之前就可以进行。调用此方法并不会实际保存文档。相反，文档仅被准备为优化结构，随后调用 Save 以获取优化后的文档。

```csharp
public void Optimize()
```

### 示例

以下示例展示了如何为 Web 优化 PDF 文档。

```csharp
[C#]
	// PDF 文件的路径。
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// 打开文档
	using (Document pdfDocument = new Document(pdfFilePath))
	{

	// 为 Web 优化
	pdfDocument.Optimize();

	// 保存输出文档
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

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


