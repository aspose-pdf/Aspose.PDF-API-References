---
title: PrintLargePdf
second_title: Aspose.PDF for .NET API 参考
description: 打开并打印一个大的 Pdf 文件如果您的 Pdf 文件有数百页或更多或它的大小是 超过 3 MB建议使用此方法以获得更好的性能
type: docs
weight: 320
url: /zh/net/aspose.pdf.facades/pdfviewer/printlargepdf/
---
## PrintLargePdf(string) {#printlargepdf_3}

打开并打印一个大的 Pdf 文件。如果您的 Pdf 文件有数百页或更多或它的大小是 超过 3 MB，建议使用此方法以获得更好的性能。

```csharp
public void PrintLargePdf(string filePath)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | Pdf 文件的路径。 |

### 评论

该方法集成了文件的打开和打印，您无需 显式调用OpenPdfFile()。

### 例子

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;     //打印调整大小的文件
iewer.AutoRotate = true;     //打印调整旋转的文件
iewer.PrintPageDialog=false;//打印时不产生页码对话框
iewer.PrintLargePdf(@"d:\test.pdf");

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true      '打印调整大小的文件
iewer.AutoRotate = true      '使用调整后的旋转打印文件
iewer.PrintPageDialog=false;//打印时不产生页码对话框
iewer.PrintLargePdf(@"d:\test.pdf")
iewer.ClosePdfFile();
```

### 也可以看看

* class [PdfViewer](../../pdfviewer)
* 命名空间 [Aspose.Pdf.Facades](../../pdfviewer)
* 部件 [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

打开并打印一个大的 Pdf 流。如果您的 Pdf 文件有数百页或更多或它的大小是 超过 3 MB，建议使用此方法以获得更好的性能。

```csharp
public void PrintLargePdf(Stream inputStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 要打开和打印的 pdf 流.. |

### 评论

该方法集成了文件的打开和打印，您无需 显式调用OpenPdfFile()。

### 例子

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;        //打印调整大小的文件
iewer.AutoRotate = true;        //打印调整旋转的文件
iewer.PrintPageDialog=false;//打印时不产生页码对话框
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")));
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true         '打印调整大小的文件
iewer.AutoRotate = true         '使用调整后的旋转打印文件
iewer.PrintPageDialog=false;//打印时不产生页码对话框
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")))
iewer.ClosePdfFile()
```

### 也可以看看

* class [PdfViewer](../../pdfviewer)
* 命名空间 [Aspose.Pdf.Facades](../../pdfviewer)
* 部件 [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PrinterSettings) {#printlargepdf_5}

打开并打印具有指定打印机设置的大型 Pdf 文件。如果您的 Pdf 文件有数百 页或更多或它的大小超过 3 MB，建议使用此方法以获得更好的性能。

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | Pdf 文件的路径。 |
| printerSettings | PrinterSettings | 打印机设置。 |

### 评论

该方法集成了文件的打开和打印，您无需 显式调用OpenPdfFile()。

### 例子

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //打印调整大小的文件
iewer.AutoRotate = true;       //打印调整旋转的文件
iewer.PrintPageDialog=false;//打印时不产生页码对话框
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(@"d:\test.pdf",ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        '打印调整大小的文件
iewer.AutoRotate = true        '使用调整后的旋转打印文件
iewer.PrintPageDialog=false;//打印时不产生页码对话框
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(@"d:\test.pdf",ps)
iewer.ClosePdfFile()
```

### 也可以看看

* class [PdfViewer](../../pdfviewer)
* 命名空间 [Aspose.Pdf.Facades](../../pdfviewer)
* 部件 [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

打开并打印具有指定打印机设置的大型 Pdf 流。如果您的 Pdf 文件有数百 页或更多或它的大小超过 3 MB，建议使用此方法以获得更好的性能。

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 要打开和打印的 pdf 流.. |
| printerSettings | PrinterSettings | 打印机设置。 |

### 评论

该方法集成了文件的打开和打印，您无需 显式调用OpenPdfFile()。

### 例子

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //打印调整大小的文件
iewer.AutoRotate = true;       //打印调整旋转的文件
iewer.PrintPageDialog=false;//打印时不产生页码对话框
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        '打印调整大小的文件
iewer.AutoRotate = true        '使用调整后的旋转打印文件
iewer.PrintPageDialog=false;//打印时不产生页码对话框
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps)
iewer.ClosePdfFile()
```

### 也可以看看

* class [PdfViewer](../../pdfviewer)
* 命名空间 [Aspose.Pdf.Facades](../../pdfviewer)
* 部件 [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PageSettings, PrinterSettings) {#printlargepdf_4}

打开并打印具有指定页面设置和打印机设置的大型 Pdf 文件。如果您的 Pdf 文件有数百页或更多或它的大小超过 3 MB，建议使用此方法 获得更好的性能。

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | Pdf 文件的路径。 |
| pageSettings | PageSettings | 页面设置。 |
| printerSettings | PrinterSettings | 打印机设置。 |

### 评论

该方法集成了文件的打开和打印，您无需 显式调用OpenPdfFile()。

### 例子

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //打印调整大小的文件
iewer.AutoRotate = true;       //打印调整旋转的文件
iewer.PrintPageDialog=false;//打印时不产生页码对话框
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
ageSettings pgs = new PageSettings();
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169);
gs.Margins = new Margins(0, 0, 0, 0);
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true       '打印调整大小的文件
iewer.AutoRotate = true       '使用调整后的旋转打印文件
iewer.PrintPageDialog=false;//打印时不产生页码对话框
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps)
iewer.ClosePdfFile()
```

### 也可以看看

* class [PdfViewer](../../pdfviewer)
* 命名空间 [Aspose.Pdf.Facades](../../pdfviewer)
* 部件 [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PageSettings, PrinterSettings) {#printlargepdf_1}

打开并打印具有指定页面设置和打印机设置的大型 Pdf 流。如果您的 Pdf 文件有数百页或更多或它的大小超过 3 MB，建议使用此方法 获得更好的性能。

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 要打开和打印的 pdf 流。 |
| pageSettings | PageSettings | 页面设置。 |
| printerSettings | PrinterSettings | 打印机设置。 |

### 评论

该方法集成了文件的打开和打印，您无需 显式调用OpenPdfFile()。

### 例子

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //打印调整大小的文件
iewer.AutoRotate = true;       //打印调整旋转的文件
iewer.PrintPageDialog=false;//打印时不产生页码对话框
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
ageSettings pgs = new PageSettings();
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169);
gs.Margins = new Margins(0, 0, 0, 0);
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true       '打印调整大小的文件
iewer.AutoRotate = true       '使用调整后的旋转打印文件
iewer.PrintPageDialog=false;//打印时不产生页码对话框
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps)
iewer.ClosePdfFile()
```

### 也可以看看

* class [PdfViewer](../../pdfviewer)
* 命名空间 [Aspose.Pdf.Facades](../../pdfviewer)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
