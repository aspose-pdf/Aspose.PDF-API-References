---
title: "PdfExtractor.GetAttachNames"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfExtractor 方法。返回 PDF 文件中附件的列表。注意，必须先调用 ExtractAttachments 才能使用此方法。"
type: docs
weight: 160
url: /zh/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## PdfExtractor.GetAttachNames method

返回 PDF 文件中的附件列表。注意：在使用此方法之前必须先调用 ExtractAttachments。

```csharp
public IList<string> GetAttachNames()
```

### 返回值

附件列表

## 示例

示例演示如何从 PDF 文件中提取附件名称。

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### 另请参见

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


