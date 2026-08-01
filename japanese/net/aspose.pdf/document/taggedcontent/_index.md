---
title: "Document.TaggedContent"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Document プロパティ。TaggedPdf コンテンツへのアクセスを取得します。"
type: docs
weight: 540
url: /ja/net/aspose.pdf/document/taggedcontent/
---
## Document.TaggedContent property

TaggedPdf コンテンツへのアクセスを取得します。

```csharp
public ITaggedContent TaggedContent { get; }
```

## 例

この例では、ヘッダー、段落、画像を含む新しいドキュメントを作成するためにタグ付けされたコンテンツを使用する方法を示しています。

```csharp
// 新しいドキュメントを作成する
Document document = new Document();

// タグ付けされたコンテンツを取得する
ITaggedContent taggedContent = document.TaggedContent;

// ドキュメントの言語を設定する
taggedContent.SetLanguage("en-US");

// PDF ドキュメントのタイトルを設定する
taggedContent.SetTitle("Example document");

// セクションを作成して追加する
SectElement sect = taggedContent.CreateSectElement();
taggedContent.RootElement.AppendChild(sect);

// ヘッダーを作成する
HeaderElement h1 = taggedContent.CreateHeaderElement(1);
h1.SetText("The Header");
sect.AppendChild(h1);

// 段落を作成する
ParagraphElement p = taggedContent.CreateParagraphElement();
p.SetTag("Paragraph");
p.SetText("The text of paragraph.");
sect.AppendChild(p);

// イラストを作成する
IllustrationElement figure1 = taggedContent.CreateFigureElement();
sect.AppendChild(figure1);
figure1.AlternativeText = "Figure 1";
figure1.Title = "Image 1";
figure1.SetTag("Fig");
figure1.SetImage("path/of/image.jpg");

// 保存 document
document.Save("example.pdf");
```

### 関連項目

* interface [ITaggedContent](../../../aspose.pdf.tagged/itaggedcontent/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


