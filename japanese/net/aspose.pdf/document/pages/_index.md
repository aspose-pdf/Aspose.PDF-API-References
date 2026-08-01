---
title: "Document.Pages"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Document property. ドキュメントページのコレクションを取得または設定します。コレクション内のページ番号は 1 から始まりますのでご注意ください"
type: docs
weight: 490
url: /ja/net/aspose.pdf/document/pages/
---
## Document.Pages property

document のページコレクションを取得または設定します。コレクション内の pages は 1 から番号付けされていることに注意してください。

```csharp
public PageCollection Pages { get; }
```

## 例

以下の例はドキュメントページの操作方法を示しています。ページ数の取得方法と、ドキュメントの開始ページの矩形を取得する方法です。

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### 関連項目

* class [PageCollection](../../pagecollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


