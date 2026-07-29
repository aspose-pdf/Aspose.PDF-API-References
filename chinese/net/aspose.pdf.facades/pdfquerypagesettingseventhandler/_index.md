---
title: "委托 PdfQueryPageSettingsEventHandler"
second_title: "Aspose.PDF for .NET API 参考"
description: "表示处理 PdfViewer 的 PdfQueryPageSettings 事件的方法"
type: docs
weight: 4740
url: /zh/net/aspose.pdf.facades/pdfquerypagesettingseventhandler/
---
## PdfQueryPageSettingsEventHandler delegate

表示处理 [`PdfQueryPageSettings`](../pdfviewer/pdfquerypagesettings/) 事件的 [`PdfViewer`](../pdfviewer/) 方法。

```csharp
public delegate void PdfQueryPageSettingsEventHandler(object sender, 
    PdfQueryPageSettingsEventArgs queryPageSettingsEventArgs, PdfPrintPageInfo currentPageInfo);
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 发送者 | 对象 | 事件的来源。 |
| queryPageSettingsEventArgs | PdfQueryPageSettingsEventArgs | 一个包含事件数据的[`PdfQueryPageSettingsEventArgs`](../../aspose.pdf.printing/pdfquerypagesettingseventargs/)。 |
| currentPageInfo | PdfPrintPageInfo | 当前打印的 Page 信息。 |

### 另请参见

* class [PdfQueryPageSettingsEventArgs](../../aspose.pdf.printing/pdfquerypagesettingseventargs/)
* class [PdfPrintPageInfo](../pdfprintpageinfo/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


