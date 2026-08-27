---
title: "PdfFileStamp.PageWidth"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileStamp 属性。获取输入文件中第一页的宽度。"
type: docs
weight: 80
url: /zh/net/aspose.pdf.facades/pdffilestamp/pagewidth/
---
## PdfFileStamp.PageWidth property

获取输入文件中第一页的宽度。

```csharp
public float PageWidth { get; }
```

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Console.WriteLine("Width = " + fileStamp.PageWidth);
fileStamp.Close();
```

### 另请参见

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


