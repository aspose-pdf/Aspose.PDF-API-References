---
title: "Page.CropBox"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Page プロパティ。ページのクロップボックスを取得または設定します"
type: docs
weight: 100
url: /ja/net/aspose.pdf/page/cropbox/
---
## Page.CropBox property

ページのクロップボックスを取得または設定します。

```csharp
public Rectangle CropBox { get; set; }
```

## 例

例ではページのクロップボックスの取得方法を示しています：

```csharp
Document document = new Document("sample.pdf");
Rectangle cropBox = document.Pages[1].CropBox;
```

### 関連項目

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


