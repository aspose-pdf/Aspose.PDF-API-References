---
title: PdfFileStamp.PageHeight
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp 属性。获取源文件中第一页的高度
type: docs
weight: 60
url: /zh/net/aspose.pdf.facades/pdffilestamp/pageheight/
---
## PdfFileStamp.PageHeight 属性

获取源文件中第一页的高度。

```csharp
public float PageHeight { get; }
```

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Console.WriteLine("Height = " + fileStamp.PageHeight);
fileStamp.Close();
```

### 另请参阅

* 类 [PdfFileStamp](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)