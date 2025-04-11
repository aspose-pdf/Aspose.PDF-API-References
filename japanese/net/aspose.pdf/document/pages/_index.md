---
title: Document.Pages
second_title: Aspose.PDF for .NET API Reference
description: ドキュメントプロパティ。ドキュメントページのコレクションを取得または設定します。コレクション内のページは1から番号が付けられていることに注意してください。
type: docs
weight: 470
url: /ja/net/aspose.pdf/document/pages/
---
## Document.Pages プロパティ

ドキュメントページのコレクションを取得または設定します。コレクション内のページは1から番号が付けられていることに注意してください。

```csharp
public PageCollection Pages { get; }
```

## 例

以下の例は、ドキュメントページを操作する方法を示しています：ページ数を取得する方法と、ドキュメントの最初のページの矩形を取得する方法。

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### 参照

* class [PageCollection](../../pagecollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)