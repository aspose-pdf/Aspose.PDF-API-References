---
title: Document.TaggedContent
second_title: Aspose.PDF for .NET API Reference
description: 文档属性。获取对 TaggedPdf 内容的访问
type: docs
weight: 520
url: /zh/net/aspose.pdf/document/taggedcontent/
---
## Document.TaggedContent 属性

获取对 TaggedPdf 内容的访问。

```csharp
public ITaggedContent TaggedContent { get; }
```

## 示例

该示例演示如何使用标记内容创建带有标题、段落和图像的新文档。

```csharp
// Create new document
Document document = new Document();

// Get the tagged content
ITaggedContent taggedContent = document.TaggedContent;

// Set language for document
taggedContent.SetLanguage("en-US");

// Set title for PDF document
taggedContent.SetTitle("Example document");

// Creating and adding Section
SectElement sect = taggedContent.CreateSectElement();
taggedContent.RootElement.AppendChild(sect);

// Create Header
HeaderElement h1 = taggedContent.CreateHeaderElement(1);
h1.SetText("The Header");
sect.AppendChild(h1);

// Create paragraph
ParagraphElement p = taggedContent.CreateParagraphElement();
p.SetTag("Paragraph");
p.SetText("The text of paragraph.");
sect.AppendChild(p);

// Create illustration
IllustrationElement figure1 = taggedContent.CreateFigureElement();
sect.AppendChild(figure1);
figure1.AlternativeText = "Figure 1";
figure1.Title = "Image 1";
figure1.SetTag("Fig");
figure1.SetImage("path/of/image.jpg");

// Save document
document.Save("example.pdf");
```

### 另请参阅

* 接口 [ITaggedContent](../../../aspose.pdf.tagged/itaggedcontent/)
* 类 [Document](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)