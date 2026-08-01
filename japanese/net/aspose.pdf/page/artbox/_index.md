---
title: "Page.ArtBox"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Page プロパティ。ページのアートボックスを取得または設定します。"
type: docs
weight: 30
url: /ja/net/aspose.pdf/page/artbox/
---
## Page.ArtBox property

ページのアートボックスを取得または設定します。

```csharp
public Rectangle ArtBox { get; set; }
```

## 例

例では、ページのアートボックスを取得する方法を示しています。

```csharp
Document document = new Document("sample.pdf");
Rectangle artBox = document.Pages[1].ArtBox;
```

### 関連項目

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


