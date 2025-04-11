---
title: Class StartEndPageEventArgs
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Printing.StartEndPageEventArgs 类。提供 PdfViewer 类的 StartPage 和 EndPage 事件的数据
type: docs
weight: 9710
url: /zh/net/aspose.pdf.printing/startendpageeventargs/
---
## StartEndPageEventArgs 类

提供 [`StartPage`](../../aspose.pdf.facades/pdfviewer/startpage/) 和 [`EndPage`](../../aspose.pdf.facades/pdfviewer/endpage/) 事件的数据，属于 [`PdfViewer`](../../aspose.pdf.facades/pdfviewer/) 类。

```csharp
public sealed class StartEndPageEventArgs : EventArgs
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [StartEndPageEventArgs](startendpageeventargs/)(int, int, int, int) | 初始化 `StartEndPageEventArgs` 类的新实例。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| readonly [CurrentCopy](../../aspose.pdf.printing/startendpageeventargs/currentcopy/) | 获取当前正在打印的副本编号。 |
| readonly [CurrentPage](../../aspose.pdf.printing/startendpageeventargs/currentpage/) | 获取当前正在打印的页面编号。 |
| readonly [TotalCopies](../../aspose.pdf.printing/startendpageeventargs/totalcopies/) | 获取要打印的副本总数。 |
| readonly [TotalPages](../../aspose.pdf.printing/startendpageeventargs/totalpages/) | 获取要打印的页面总数。 |

### 另请参阅

* 命名空间 [Aspose.Pdf.Printing](../../aspose.pdf.printing/)
* 程序集 [Aspose.PDF](../../)