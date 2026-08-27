---
title: "PdfViewer.PrintDocumentWithSetup"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfViewer 方法。使用设置对话框打印 Pdf Document。通过对话框选择打印机。"
type: docs
weight: 340
url: /zh/net/aspose.pdf.facades/pdfviewer/printdocumentwithsetup/
---
## PdfViewer.PrintDocumentWithSetup method

使用设置对话框打印 Pdf document。通过对话框选择打印机。

```csharp
public void PrintDocumentWithSetup()
```

## 示例

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.BindPdf(@"d:\test.pdf");
iewer.AutoResize = true;         //print the file with adjusted size
iewer.AutoRotate = true;         //print the file with adjusted rotation
iewer.PrintPageDialog = false;   //do not produce the page number dialog when printing
iewer.PrintDocumentWithSetup();
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.BindPdf(@"d:\test.pdf")
iewer.AutoResize = True          'print the file with adjusted size
iewer.AutoRotate = True          'print the file with adjusted rotation
iewer.PrintPageDialog = False    'do not produce the page number dialog when printing
iewer.PrintDocumentWithSetup()
iewer.Close()
```

### 另请参见

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


