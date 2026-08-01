---
title: "OutputIntents.Item"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OutputIntents プロパティ。指定されたインデックスの出力インテントを取得します"
type: docs
weight: 30
url: /ja/net/aspose.pdf/outputintents/item/
---
## OutputIntents indexer

指定された *index* の出力インテントを取得します。

```csharp
public OutputIntent this[int index] { get; }
```

| パラメーター | 説明 |
| --- | --- |
| インデックス | 取得する出力インテントのゼロベースインデックスです。 |

### 戻り値

指定された *index* の出力インテントです。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *index* が 0 未満、または *index* が [`Count`](../count/) と等しいかそれ以上です。 |
| InvalidOperationException | コレクションを含むドキュメントには、OutputIntents にアクセスするカタログがありません。 |

### 関連項目

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


