---
title: "Document.TaggedContent"
second_title: "Aspose.PDF for .NET API 参考"
description: "Document 属性。获取对 TaggedPdf 内容的访问"
type: docs
weight: 540
url: /zh/net/aspose.pdf/document/taggedcontent/
---
## Document.TaggedContent property

获取对 TaggedPdf 内容的访问。

```csharp
public ITaggedContent TaggedContent { get; }
```

## 示例

示例演示如何使用标记内容来创建带有标题、段落和图像的新文档。

```csharp
// 创建新文档
Document document = new Document();

// 获取标记内容
ITaggedContent taggedContent = document.TaggedContent;

// 设置文档的语言
taggedContent.SetLanguage("en-US");

// 设置 PDF 文档的标题
taggedContent.SetTitle("Example document");

// 创建并添加节
SectElement sect = taggedContent.CreateSectElement();
taggedContent.RootElement.AppendChild(sect);

// 创建标题
HeaderElement h1 = taggedContent.CreateHeaderElement(1);
h1.SetText("The Header");
sect.AppendChild(h1);

// 创建段落
ParagraphElement p = taggedContent.CreateParagraphElement();
p.SetTag("Paragraph");
p.SetText("The text of paragraph.");
sect.AppendChild(p);

// 创建插图
IllustrationElement figure1 = taggedContent.CreateFigureElement();
sect.AppendChild(figure1);
figure1.AlternativeText = "Figure 1";
figure1.Title = "Image 1";
figure1.SetTag("Fig");
figure1.SetImage("path/of/image.jpg");

// 保存文档
document.Save("example.pdf");
```

### 另请参见

* interface [ITaggedContent](../../../aspose.pdf.tagged/itaggedcontent/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


