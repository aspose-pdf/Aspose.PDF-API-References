---
title: Document.TaggedContent
second_title: Aspose.PDF for .NET API Reference
description: ドキュメントプロパティ。TaggedPdf コンテンツへのアクセスを取得します
type: docs
weight: 520
url: /ja/net/aspose.pdf/document/taggedcontent/
---
## Document.TaggedContent プロパティ

TaggedPdf コンテンツへのアクセスを取得します。

```csharp
public ITaggedContent TaggedContent { get; }
```

## 例

この例では、ヘッダー、段落、画像を含む新しいドキュメントを作成するためのタグ付きコンテンツの使用方法を示します。

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

### 関連項目

* インターフェース [ITaggedContent](../../../aspose.pdf.tagged/itaggedcontent/)
* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)