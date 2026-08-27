---
title: "Page.MediaBox"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Page プロパティ。ページの MediaBox を取得または設定します"
type: docs
weight: 180
url: /ja/net/aspose.pdf/page/mediabox/
---
## Page.MediaBox property

ページのメディアボックスを取得または設定します。

```csharp
public Rectangle MediaBox { get; set; }
```

## 例

例として、ページの MediaBox を取得する方法を示します：

```csharp
Document document = new Document("sample.pdf");
Rectangle mediaBox = document.Pages[1].MediaBox;
```

### 関連項目

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


