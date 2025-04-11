---
title: Page.CropBox
second_title: Aspose.PDF for .NET API Reference
description: ページプロパティ。ページのクロップボックスを取得または設定します
type: docs
weight: 100
url: /ja/net/aspose.pdf/page/cropbox/
---
## Page.CropBoxプロパティ

ページのクロップボックスを取得または設定します。

```csharp
public Rectangle CropBox { get; set; }
```

## 例

例は、ページのクロップボックスを取得する方法を示しています。

```csharp
Document document = new Document("sample.pdf");
Rectangle cropBox = document.Pages[1].CropBox;
```

### 関連項目

* クラス [Rectangle](../../rectangle/)
* クラス [Page](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)