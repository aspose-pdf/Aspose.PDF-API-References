---
title: "Page.Duration"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Page プロパティ。ページ表示時間を取得または設定します。これはプレゼンテーション中にページが表示される秒数です。期間が未定義の場合は 1 を返します"
type: docs
weight: 110
url: /ja/net/aspose.pdf/page/duration/
---
## Page.Duration property

ページの表示時間を取得または設定します。これはプレゼンテーション中にページが表示される秒数です。期間が定義されていない場合は -1 を返します。

```csharp
public double Duration { get; set; }
```

## 例

例ではページの表示時間の取得方法を示しています

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### 関連項目

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


