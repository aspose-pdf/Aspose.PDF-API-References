---
title: "PdfExtractor.ExtractTextMode"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfExtractor 属性。设置提取文本结果的模式。"
type: docs
weight: 40
url: /zh/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## PdfExtractor.ExtractTextMode property

设置文本提取结果的模式。

```csharp
public int ExtractTextMode { get; set; }
```

### Property Value

0 表示纯文本模式，1 表示原始顺序模式。默认值为 0。

## 示例

示例演示在文本提取场景中使用 `ExtractTextMode` 属性。

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### 另请参见

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


