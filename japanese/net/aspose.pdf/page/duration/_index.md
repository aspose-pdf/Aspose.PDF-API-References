---
title: Page.Duration
second_title: Aspose.PDF for .NET API Reference
description: ページプロパティ。設定されたページ表示時間を取得します。これは、プレゼンテーション中にページが表示される時間（秒）です。期間が定義されていない場合は1を返します。
type: docs
weight: 110
url: /ja/net/aspose.pdf/page/duration/
---
## Page.Duration プロパティ

設定されたページ表示時間を取得します。これは、プレゼンテーション中にページが表示される時間（秒）です。期間が定義されていない場合は-1を返します。

```csharp
public double Duration { get; set; }
```

## 例

例は、ページの期間を取得する方法を示しています。

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### 関連項目

* クラス [Page](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)