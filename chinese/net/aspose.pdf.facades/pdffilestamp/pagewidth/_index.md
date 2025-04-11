---
title: PdfFileStamp.PageWidth
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp 属性。获取输入文件中第一页的宽度
type: docs
weight: 80
url: /zh/net/aspose.pdf.facades/pdffilestamp/pagewidth/
---
## PdfFileStamp.PageWidth 属性

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

### 另见

* 类 [PdfFileStamp](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)