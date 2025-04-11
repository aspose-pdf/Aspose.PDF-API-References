---
title: PdfExtractor.GetAttachNames
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor 方法。返回 PDF 文件中的附件列表。注意：必须在使用此方法之前调用 ExtractAttachments
type: docs
weight: 160
url: /zh/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## PdfExtractor.GetAttachNames 方法

返回 PDF 文件中的附件列表。注意：必须在使用此方法之前调用 ExtractAttachments。

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

### 另请参阅

* 类 [PdfExtractor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)