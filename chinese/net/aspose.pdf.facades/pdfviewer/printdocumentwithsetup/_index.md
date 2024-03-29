---
title: PrintDocumentWithSetup
second_title: Aspose.PDF for .NET API 参考
description: 打印带有设置对话框的 Pdf 文档使用对话框选择打印机
type: docs
weight: 310
url: /zh/net/aspose.pdf.facades/pdfviewer/printdocumentwithsetup/
---
## PdfViewer.PrintDocumentWithSetup method

打印带有设置对话框的 Pdf 文档。使用对话框选择打印机。

```csharp
public void PrintDocumentWithSetup()
```

### 例子

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.OpenPdfFile(@"d:\test.pdf");
iewer.AutoResize = true;         //打印调整大小的文件
iewer.AutoRotate = true;         //打印调整旋转的文件
iewer.PrintPageDialog=false;//打印时不产生页码对话框
iewer.PrintDocumentWithSetup();
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer()
iewer.OpenPdfFile(@"d:\test.pdf")   
iewer.AutoResize = true          '打印调整大小的文件
iewer.AutoRotate = true          '使用调整后的旋转打印文件
iewer.PrintPageDialog=false;//打印时不产生页码对话框
iewer.PrintDocumentWithSetup()
iewer.ClosePdfFile()
```

### 也可以看看

* class [PdfViewer](../../pdfviewer)
* 命名空间 [Aspose.Pdf.Facades](../../pdfviewer)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
