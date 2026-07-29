---
title: "PdfViewer.PrintDocuments"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfViewer 方法。使用默认打印机和页面设置打印多个 PDF 文档。"
type: docs
weight: 370
url: /zh/net/aspose.pdf.facades/pdfviewer/printdocuments/
---
## PrintDocuments(params Document[]) {#printdocuments}

使用默认打印机和页面设置打印多个 PDF 文档。

```csharp
public static void PrintDocuments(params Document[] documents)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| documents | Document[] | 一个由 [`Document`](../../../aspose.pdf/document/) 对象组成的数组，表示要打印的 PDF 文档。 |

## 备注

此方法允许在单个打印作业中打印多个 PDF 文档。

## 示例

```csharp
[C#]
using (Aspose.Pdf.Document document1 = new Aspose.Pdf.Document(dataDir + "PrintDocument.pdf"),
                           document2 = new Aspose.Pdf.Document(dataDir + "Print-PageRange.pdf"),
                           document3 = new Aspose.Pdf.Document(dataDir + "35925_1_3.xps", new Aspose.Pdf.XpsLoadOptions()))
{
    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(document1, document2, document3);
}

[VisualBasic]
Using document1 As New Aspose.Pdf.Document(dataDir & "PrintDocument.pdf"),
      document2 As New Aspose.Pdf.Document(dataDir & "Print-PageRange.pdf"),
      document3 As New Aspose.Pdf.Document(dataDir & "35925_1_3.xps", New Aspose.Pdf.XpsLoadOptions())
     Aspose.Pdf.Facades.PdfViewer.PrintDocuments(document1, document2, document3)
End Using
```

### 另请参见

* class [Document](../../../aspose.pdf/document/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(params string[]) {#printdocuments_8}

使用默认打印机和页面设置打印多个 PDF 文档。

```csharp
public static void PrintDocuments(params string[] filePaths)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePaths | String[] | 一个文件路径数组，表示要打印的 PDF 文档。 |

## 备注

此方法允许在单个打印作业中打印多个 PDF 文档。请确保提供的文件路径有效且可访问。

## 示例

```csharp
[C#]
var path1 = dataDir + "PrintDocument.pdf";
var path2 = dataDir + "Print-PageRange.pdf";
var path3 = dataDir + "35925_1_3.xps";

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(path1, path2, path3);

[VisualBasic]
Dim path1 As String = dataDir & "PrintDocument.pdf"
Dim path2 As String = dataDir & "Print-PageRange.pdf"
Dim path3 As String = dataDir & "35925_1_3.xps"

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(path1, path2, path3)
```

### 另请参见

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(params Stream[]) {#printdocuments_7}

使用默认打印机和页面设置，从提供的流中打印多个 PDF 文档。

```csharp
public static void PrintDocuments(params Stream[] documentStreams)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| documentStreams | Stream[] | 一个包含待打印的 PDF Document 的流数组。 |

## 备注

此方法允许在一次操作中打印多个 PDF Document。请确保提供的流在打印过程中是有效且可访问的。

## 示例

```csharp
[C#]
using (Stream stream1 = File.OpenRead(dataDir + "PrintDocument.pdf"),
              stream2 = File.OpenRead(dataDir + "Print-PageRange.pdf"),
              stream3 = File.OpenRead(dataDir + "35925_1_3.xps"))
{
    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(stream1, stream2, stream3);
}

[VisualBasic]
Using stream1 As Stream = File.OpenRead(dataDir & "PrintDocument.pdf"),
      stream2 As Stream = File.OpenRead(dataDir & "Print-PageRange.pdf"),
      stream3 As Stream = File.OpenRead(dataDir & "35925_1_3.xps")
    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(stream1, stream2, stream3)
End Using
```

### 另请参见

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, params Document[]) {#printdocuments_1}

使用指定的打印机设置打印多个 PDF 文档。

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, params Document[] documents)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| printerSettings | PrinterSettings | 指定用于打印的打印机设置的 [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/) 对象。 |
| documents | Document[] | 一个由 [`Document`](../../../aspose.pdf/document/) 对象组成的数组，表示要打印的 PDF 文档。 |

## 备注

此方法允许使用自定义打印机设置打印多个 PDF Document。

## 示例

```csharp
[C#]
using (Aspose.Pdf.Document document1 = new Aspose.Pdf.Document(dataDir + "PrintDocument.pdf"),
                           document2 = new Aspose.Pdf.Document(dataDir + "Print-PageRange.pdf"),
                           document3 = new Aspose.Pdf.Document(dataDir + "35925_1_3.xps", new Aspose.Pdf.XpsLoadOptions()))
{
    var printDocument = new PrintDocument();
    Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, document1, document2, document3);
}

[VisualBasic]
Using document1 As New Aspose.Pdf.Document(dataDir & "PrintDocument.pdf"),
      document2 As New Aspose.Pdf.Document(dataDir & "Print-PageRange.pdf"),
      document3 As New Aspose.Pdf.Document(dataDir & "35925_1_3.xps", New Aspose.Pdf.XpsLoadOptions())
     Dim printDocument As New PrintDocument()
     Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
     printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

     Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, document1, document2, document3)
End Using
```

### 另请参见

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [Document](../../../aspose.pdf/document/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, params string[]) {#printdocuments_6}

使用指定的打印机设置打印多个 PDF 文档。

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, params string[] filePaths)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| printerSettings | PrinterSettings | 包含打印机配置详细信息的 [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/) 对象。 |
| filePaths | String[] | 一个文件路径数组，表示要打印的 PDF 文档。 |

## 备注

此方法允许在单个打印作业中打印多个 PDF 文档。请确保提供的文件路径有效且可访问。

## 示例

```csharp
[C#]
var path1 = dataDir + "PrintDocument.pdf";
var path2 = dataDir + "Print-PageRange.pdf";
var path3 = dataDir + "35925_1_3.xps";

var printDocument = new PrintDocument();
Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, path1, path2, path3);

[VisualBasic]
Dim path1 As String = dataDir & "PrintDocument.pdf"
Dim path2 As String = dataDir & "Print-PageRange.pdf"
Dim path3 As String = dataDir & "35925_1_3.xps"

Dim printDocument As New PrintDocument()
Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, path1, path2, path3)
```

### 另请参见

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, params Stream[]) {#printdocuments_5}

使用指定的打印机设置，从提供的流中打印多个 PDF 文档。

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, params Stream[] documentStreams)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| printerSettings | PrinterSettings | 打印过程中将应用的打印机设置。 |
| documentStreams | Stream[] | 一个包含待打印的 PDF Document 的流数组。 |

## 备注

此方法允许在一次操作中打印多个 PDF Document。请确保提供的流在打印过程中是有效且可访问的。

## 示例

```csharp
[C#]
using (Stream stream1 = File.OpenRead(dataDir + "PrintDocument.pdf"),
              stream2 = File.OpenRead(dataDir + "Print-PageRange.pdf"),
              stream3 = File.OpenRead(dataDir + "35925_1_3.xps"))
{
    var printDocument = new PrintDocument();
    Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, stream1, stream2, stream3);
}

[VisualBasic]
Using stream1 As Stream = File.OpenRead(dataDir & "PrintDocument.pdf"),
      stream2 As Stream = File.OpenRead(dataDir & "Print-PageRange.pdf"),
      stream3 As Stream = File.OpenRead(dataDir & "35925_1_3.xps")
    Dim printDocument As New PrintDocument()
    Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, stream1, stream2, stream3)
End Using
```

### 另请参见

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, PageSettings, params Document[]) {#printdocuments_2}

使用指定的打印机和页面设置打印多个 PDF 文档。

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, PageSettings pageSettings, 
    params Document[] documents)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| printerSettings | PrinterSettings | 指定用于打印的打印机设置的 [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/) 对象。 |
| pageSettings | PageSettings | 指定用于打印的 Page 设置的 [`PageSettings`](../../../aspose.pdf.printing/pagesettings/) 对象。 |
| documents | Document[] | 一个由 [`Document`](../../../aspose.pdf/document/) 对象组成的数组，表示要打印的 PDF 文档。 |

## 备注

此方法允许使用自定义打印机和 Page 设置打印多个 PDF Document。

## 示例

```csharp
[C#]
using (Aspose.Pdf.Document document1 = new Aspose.Pdf.Document(dataDir + "PrintDocument.pdf"),
                           document2 = new Aspose.Pdf.Document(dataDir + "Print-PageRange.pdf"),
                           document3 = new Aspose.Pdf.Document(dataDir + "35925_1_3.xps", new Aspose.Pdf.XpsLoadOptions()))
{
    var printDocument = new PrintDocument();
    Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

    Aspose.Pdf.Printing.PageSettings pageSettings = new Aspose.Pdf.Printing.PageSettings();
    pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4;
    pageSettings.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, document1, document2, document3);
}

[VisualBasic]
Using document1 As New Aspose.Pdf.Document(dataDir & "PrintDocument.pdf"),
      document2 As New Aspose.Pdf.Document(dataDir & "Print-PageRange.pdf"),
      document3 As New Aspose.Pdf.Document(dataDir & "35925_1_3.xps", New Aspose.Pdf.XpsLoadOptions())
     Dim printDocument As New PrintDocument()
     Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
     printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

     Dim pageSettings As New Aspose.Pdf.Printing.PageSettings()
     pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4
     pageSettings.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)

     Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, document1, document2, document3)
End Using
```

### 另请参见

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [Document](../../../aspose.pdf/document/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, PageSettings, params string[]) {#printdocuments_4}

使用指定的打印机和页面设置打印多个 PDF 文档。

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, PageSettings pageSettings, 
    params string[] filePaths)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| printerSettings | PrinterSettings | 包含打印机配置详细信息的 [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/) 对象。 |
| pageSettings | PageSettings | 指定 Page 布局和设置的 [`PageSettings`](../../../aspose.pdf.printing/pagesettings/) 对象。 |
| filePaths | String[] | 一个文件路径数组，表示要打印的 PDF 文档。 |

## 备注

此方法允许在单个打印作业中打印多个 PDF 文档。请确保提供的文件路径有效且可访问。

## 示例

```csharp
[C#]
var path1 = dataDir + "PrintDocument.pdf";
var path2 = dataDir + "Print-PageRange.pdf";
var path3 = dataDir + "35925_1_3.xps";

var printDocument = new PrintDocument();
Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

Aspose.Pdf.Printing.PageSettings pageSettings = new Aspose.Pdf.Printing.PageSettings();
pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4;
pageSettings.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, path1, path2, path3);

[VisualBasic]
Dim path1 As String = dataDir & "PrintDocument.pdf"
Dim path2 As String = dataDir & "Print-PageRange.pdf"
Dim path3 As String = dataDir & "35925_1_3.xps"

Dim printDocument As New PrintDocument()
Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

Dim pageSettings As New Aspose.Pdf.Printing.PageSettings()
pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4
pageSettings.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, path1, path2, path3)
```

### 另请参见

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, PageSettings, params Stream[]) {#printdocuments_3}

使用指定的打印机和页面设置，从提供的流中打印多个 PDF 文档。

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, PageSettings pageSettings, 
    params Stream[] documentStreams)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| printerSettings | PrinterSettings | 打印过程中将应用的打印机设置。 |
| pageSettings | PageSettings | 打印过程中将应用于每个 Document 的 Page 设置。 |
| documentStreams | Stream[] | 一个包含待打印的 PDF Document 的流数组。 |

## 备注

此方法允许在一次操作中打印多个 PDF Document。请确保提供的流在打印过程中是有效且可访问的。

## 示例

```csharp
[C#]
using (Stream stream1 = File.OpenRead(dataDir + "PrintDocument.pdf"),
              stream2 = File.OpenRead(dataDir + "Print-PageRange.pdf"),
              stream3 = File.OpenRead(dataDir + "35925_1_3.xps"))
{
    var printDocument = new PrintDocument();
    Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

    Aspose.Pdf.Printing.PageSettings pageSettings = new Aspose.Pdf.Printing.PageSettings();
    pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4;
    pageSettings.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, stream1, stream2, stream3);
}

[VisualBasic]
Using stream1 As Stream = File.OpenRead(dataDir & "PrintDocument.pdf"),
      stream2 As Stream = File.OpenRead(dataDir & "Print-PageRange.pdf"),
      stream3 As Stream = File.OpenRead(dataDir & "35925_1_3.xps")
    Dim printDocument As New PrintDocument()
    Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

    Dim pageSettings As New Aspose.Pdf.Printing.PageSettings()
    pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4
    pageSettings.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, stream1, stream2, stream3)
End Using
```

### 另请参见

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


