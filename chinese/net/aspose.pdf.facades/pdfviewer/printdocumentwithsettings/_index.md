---
title: PrintDocumentWithSettings
second_title: Aspose.PDF for .NET API 参考
description: 打印带有设置的 Pdf 文档如果文档大小与页面大小不兼容pdf.kit 将扩展它以适应页面大小
type: docs
weight: 300
url: /zh/net/aspose.pdf.facades/pdfviewer/printdocumentwithsettings/
---
## PrintDocumentWithSettings(PageSettings, PrinterSettings) {#printdocumentwithsettings}

打印带有设置的 Pdf 文档。如果文档大小与页面大小不兼容，pdf.kit 将扩展它以适应页面大小。

```csharp
public void PrintDocumentWithSettings(PageSettings pageSettings, PrinterSettings printerSettings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageSettings | PageSettings | 打印文档的页面设置。 |
| printerSettings | PrinterSettings | 打印文档的打印机设置。 |

### 例子

printerSettings 对象用于打印文档。 pageSettings.PrinterSettings 对象被忽略。

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.OpenPdfFile(@"d:\test.pdf");
iewer.AutoResize = true;         //打印调整大小的文件
iewer.AutoRotate = true;         //打印调整旋转的文件
iewer.PrintPageDialog=false;//打印时不产生页码对话框
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
ageSettings pgs = new PageSettings();
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169);
gs.Margins = new Margins(0, 0, 0, 0);
iewer.PrintDocumentWithSettings(pgs, ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer()
iewer.OpenPdfFile(@"d:\test.pdf")
iewer.AutoResize = true;           '打印调整大小的文件
iewer.AutoRotate = true;           '使用调整后的旋转打印文件
iewer.PrintPageDialog=false;//打印时不产生页码对话框
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintDocumentWithSettings(pgs, ps)
iewer.ClosePdfFile()
```

### 也可以看看

* class [PdfViewer](../../pdfviewer)
* 命名空间 [Aspose.Pdf.Facades](../../pdfviewer)
* 部件 [Aspose.PDF](../../../)

---

## PrintDocumentWithSettings(PrinterSettings) {#printdocumentwithsettings_1}

使用打印机设置打印 Pdf 文档。输出页面大小将适合文档首页大小。

```csharp
public void PrintDocumentWithSettings(PrinterSettings printerSettings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| printerSettings | PrinterSettings | 打印文档的打印机设置。 |

### 例子

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.OpenPdfFile(@"d:\test.pdf");
iewer.AutoResize = true;         //打印调整大小的文件
iewer.AutoRotate = true;         //打印调整旋转的文件
iewer.PrintPageDialog=false;//打印时不产生页码对话框
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintDocumentWithSettings(ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer()
iewer.OpenPdfFile(@"d:\test.pdf")
iewer.AutoResize = true;        '打印调整大小的文件
iewer.AutoRotate = true;        '使用调整后的旋转打印文件
iewer.PrintPageDialog=false;//打印时不产生页码对话框
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintDocumentWithSettings(ps);
iewer.ClosePdfFile()
```

### 也可以看看

* class [PdfViewer](../../pdfviewer)
* 命名空间 [Aspose.Pdf.Facades](../../pdfviewer)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
