---
title: "Page.TrimBox"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Page プロパティ。ページのトリムボックスを取得または設定します。"
type: docs
weight: 290
url: /ja/net/aspose.pdf/page/trimbox/
---
## Page.TrimBox property

ページのトリムボックスを取得または設定します。

```csharp
public Rectangle TrimBox { get; set; }
```

## 例

例ではページのトリムボックスの取得方法を示しています：

```csharp
Document document = new Document("sample.pdf");
Rectangle trimBox = document.Pages[1].TrimBox;
```

### 関連項目

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


