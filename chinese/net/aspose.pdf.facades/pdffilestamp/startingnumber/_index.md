---
title: PdfFileStamp.StartingNumber
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp 属性。获取或设置输入文件中第一页的起始编号。后续页面将从此值开始编号。例如，如果 StartingNumber 设置为 100，文档页面将编号为 100、101、102。
type: docs
weight: 100
url: /zh/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## PdfFileStamp.StartingNumber 属性

获取或设置输入文件中第一页的起始编号。后续页面将从此值开始编号。例如，如果 StartingNumber 设置为 100，文档页面将编号为 100、101、102...

```csharp
public int StartingNumber { get; set; }
```

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.StartingNumber = 100;
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### 另请参阅

* 类 [PdfFileStamp](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)