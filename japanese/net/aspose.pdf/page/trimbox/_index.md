---
title: Page.TrimBox
second_title: Aspose.PDF for .NET API Reference
description: ページプロパティ。ページのトリムボックスを取得または設定します
type: docs
weight: 290
url: /ja/net/aspose.pdf/page/trimbox/
---
## Page.TrimBox プロパティ

ページのトリムボックスを取得または設定します。

```csharp
public Rectangle TrimBox { get; set; }
```

## 例

例は、ページのトリムボックスを取得する方法を示しています：

```csharp
Document document = new Document("sample.pdf");
Rectangle trimBox = document.Pages[1].TrimBox;
```

### 関連項目

* クラス [Rectangle](../../rectangle/)
* クラス [Page](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)