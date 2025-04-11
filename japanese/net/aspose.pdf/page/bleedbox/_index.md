---
title: Page.BleedBox
second_title: Aspose.PDF for .NET API Reference
description: ページプロパティ。ページのブリードボックスを取得または設定します
type: docs
weight: 70
url: /ja/net/aspose.pdf/page/bleedbox/
---
## Page.BleedBox プロパティ

ページのブリードボックスを取得または設定します。

```csharp
public Rectangle BleedBox { get; set; }
```

## 例

例は、ページのブリードボックスを取得する方法を示しています:

```csharp
Document document = new Document("sample.pdf");
Rectangle bleedBox = document.Pages[1].BleedBox;
```

### 参照

* クラス [Rectangle](../../rectangle/)
* クラス [Page](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)