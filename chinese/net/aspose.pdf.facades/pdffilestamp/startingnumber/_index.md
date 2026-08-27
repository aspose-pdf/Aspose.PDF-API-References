---
title: "PdfFileStamp.StartingNumber"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileStamp 属性。获取或设置输入文件中第一页的起始编号。后续页面将从该值开始编号。例如，如果 StartingNumber 设置为 100，文档页面将显示编号 100 101 102"
type: docs
weight: 100
url: /zh/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## PdfFileStamp.StartingNumber property

获取或设置输入文件中第一页的起始编号。后续页面将从该值开始编号。例如，如果 StartingNumber 设置为 100，文档页面的编号将为 100、101、102……

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

### 另请参见

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


