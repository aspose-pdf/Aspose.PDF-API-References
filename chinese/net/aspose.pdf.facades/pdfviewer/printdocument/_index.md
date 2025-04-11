---
title: PdfViewer.PrintDocument
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer 方法。使用默认打印机打印 Pdf 文档
type: docs
weight: 320
url: /zh/net/aspose.pdf.facades/pdfviewer/printdocument/
---
## PdfViewer.PrintDocument 方法

使用默认打印机打印 Pdf 文档。

```csharp
public void PrintDocument()
```

## 示例

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.OpenPdfFile(@"d:\test.pdf");
iewer.AutoResize = true;         //print the file with adjusted size
iewer.AutoRotate = true;         //print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
iewer.PrintDocument(ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer()
iewer.OpenPdfFile(@"d:\test.pdf")
iewer.AutoResize = true;         'print the file with adjusted size
iewer.AutoRotate = true;         'print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
iewer.PrintDocument(ps);
iewer.ClosePdfFile()
```

### 另请参阅

* 类 [PdfViewer](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)