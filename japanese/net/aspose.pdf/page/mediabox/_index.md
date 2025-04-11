---
title: Page.MediaBox
second_title: Aspose.PDF for .NET API Reference
description: ページプロパティ。ページのメディアボックスを取得または設定します。
type: docs
weight: 180
url: /ja/net/aspose.pdf/page/mediabox/
---
## Page.MediaBox プロパティ

ページのメディアボックスを取得または設定します。

```csharp
public Rectangle MediaBox { get; set; }
```

## 例

例は、ページのメディアボックスを取得する方法を示しています。

```csharp
Document document = new Document("sample.pdf");
Rectangle mediaBox = document.Pages[1].MediaBox;
```

### 参照

* クラス [Rectangle](../../rectangle/)
* クラス [Page](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)