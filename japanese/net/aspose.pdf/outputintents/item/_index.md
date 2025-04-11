---
title: OutputIntents.Item
second_title: Aspose.PDF for .NET API Reference
description: OutputIntents プロパティ。指定されたインデックスの出力インテントを取得します
type: docs
weight: 30
url: /ja/net/aspose.pdf/outputintents/item/
---
## OutputIntents インデクサ

指定された *index* の出力インテントを取得します。

```csharp
public OutputIntent this[int index] { get; }
```

| パラメーター | 説明 |
| --- | --- |
| index | 取得する出力インテントのゼロベースのインデックス。 |

### 戻り値

指定された *index* の出力インテント。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *index* が 0 未満であるか、*index* が [`Count`](../count/) と等しいかそれ以上です。 |
| InvalidOperationException | コレクションを含むドキュメントに OutputIntents にアクセスするためのカタログがありません。 |

### 参照

* クラス [OutputIntent](../../outputintent/)
* クラス [OutputIntents](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)