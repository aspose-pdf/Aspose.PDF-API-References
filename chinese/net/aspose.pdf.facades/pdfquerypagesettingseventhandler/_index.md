---
title: Delegate PdfQueryPageSettingsEventHandler
second_title: Aspose.PDF for .NET API Reference
description: 表示处理 PdfViewer 的 PdfQueryPageSettings 事件的方法
type: docs
weight: 4620
url: /zh/net/aspose.pdf.facades/pdfquerypagesettingseventhandler/
---
## PdfQueryPageSettingsEventHandler 委托

表示处理 [`PdfQueryPageSettings`](../pdfviewer/pdfquerypagesettings/) 事件的方法，该事件属于 [`PdfViewer`](../pdfviewer/)。

```csharp
public delegate void PdfQueryPageSettingsEventHandler(object sender, 
    PdfQueryPageSettingsEventArgs queryPageSettingsEventArgs, PdfPrintPageInfo currentPageInfo);
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sender | Object | 事件的源。 |
| queryPageSettingsEventArgs | PdfQueryPageSettingsEventArgs | 包含事件数据的 [`PdfQueryPageSettingsEventArgs`](../../aspose.pdf.printing/pdfquerypagesettingseventargs/)。 |
| currentPageInfo | PdfPrintPageInfo | 当前打印的页面信息。 |

### 另见

* 类 [PdfQueryPageSettingsEventArgs](../../aspose.pdf.printing/pdfquerypagesettingseventargs/)
* 类 [PdfPrintPageInfo](../pdfprintpageinfo/)
* 命名空间 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../)