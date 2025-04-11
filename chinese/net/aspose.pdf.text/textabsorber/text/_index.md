---
title: TextAbsorber.Text
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber 属性。获取 TextAbsorber 在 PDF 文档或页面上提取的文本
type: docs
weight: 50
url: /zh/net/aspose.pdf.text/textabsorber/text/
---
## TextAbsorber.Text 属性

获取 [`TextAbsorber`](../) 在 PDF 文档或页面上提取的文本。

```csharp
public virtual string Text { get; }
```

## 示例

该示例演示如何从 PDF 文档的所有页面提取文本。

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### 另请参阅

* 类 [TextAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)