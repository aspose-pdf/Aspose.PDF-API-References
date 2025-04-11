---
title: TextAbsorber.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber 属性。获取或设置文本提取选项
type: docs
weight: 30
url: /zh/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## TextAbsorber.ExtractionOptions 属性

获取或设置文本提取选项。

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## 备注

允许在提取过程中定义文本格式模式 [`TextExtractionOptions`](../../textextractionoptions/)。默认模式是 Pure

## 示例

该示例演示如何设置 Pure 文本格式模式并执行文本提取。

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber();

// set pure text formatting mode
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;
```

### 另请参阅

* 类 [TextExtractionOptions](../../textextractionoptions/)
* 类 [TextAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)