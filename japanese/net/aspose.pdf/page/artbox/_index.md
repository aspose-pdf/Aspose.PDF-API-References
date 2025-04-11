---
title: Page.ArtBox
second_title: Aspose.PDF for .NET API Reference
description: ページプロパティ。ページのアートボックスを取得または設定します
type: docs
weight: 30
url: /ja/net/aspose.pdf/page/artbox/
---
## Page.ArtBox プロパティ

ページのアートボックスを取得または設定します。

```csharp
public Rectangle ArtBox { get; set; }
```

## 例

例は、ページのアートボックスを取得する方法を示しています。

```csharp
Document document = new Document("sample.pdf");
Rectangle artBox = document.Pages[1].ArtBox;
```

### 関連項目

* クラス [Rectangle](../../rectangle/)
* クラス [Page](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)