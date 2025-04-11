---
title: Enum ComparisonMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.ComparisonMode 列挙型。比較モードの列挙
type: docs
weight: 3140
url: /ja/net/aspose.pdf.comparison/comparisonmode/
---
## ComparisonMode 列挙型

比較モードの列挙型。

```csharp
public enum ComparisonMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Normal | `0` | 通常モード。テキストフラグメント内のスペースのみが考慮されます（ドキュメントの生成方法に依存します）。 |
| IgnoreSpaces | `1` | すべてのスペースが無視されます。変更は単語のみに求められます。 |
| ParseSpaces | `2` | モードは通常に似ていますが、距離に基づいてテキストフラグメント間の視覚的な間隔を考慮しようとします。フラグメント間のスペースの数を認識することは正確でない場合があります。これは、ドキュメントの生成方法に大きく依存するためです。異なるジェネレーターによって作成されたドキュメントの場合、テキストフラグメント間のスペースを比較する際に不正確さが生じる可能性があります。 |

### 参照

* 名前空間 [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* アセンブリ [Aspose.PDF](../../)