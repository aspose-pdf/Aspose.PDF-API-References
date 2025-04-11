---
title: PdfExtractor.ExtractTextMode
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor 属性。设置提取文本结果的模式
type: docs
weight: 40
url: /zh/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## PdfExtractor.ExtractTextMode 属性

设置提取文本结果的模式。

```csharp
public int ExtractTextMode { get; set; }
```

### 属性值

0 是纯文本模式，1 是原始排序模式。默认值为 0。

## 示例

该示例演示了 `ExtractTextMode` 属性在文本提取场景中的使用。

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### 另请参阅

* 类 [PdfExtractor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)