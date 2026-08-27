---
title: "列挙体 ComparisonMode"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Comparison.ComparisonMode 列挙体。比較モードの列挙です。"
type: docs
weight: 3250
url: /ja/net/aspose.pdf.comparison/comparisonmode/
---
## ComparisonMode enumeration

比較モード列挙体です。

```csharp
public enum ComparisonMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Normal | `0` | 通常モード。テキストフラグメント内のスペースのみが考慮されます（ドキュメントの生成方法に依存します）。 |
| IgnoreSpaces | `1` | すべてのスペースは無視されます。変更は単語単位でのみ検出されます。 |
| ParseSpaces | `2` | このモードは通常モードに似ていますが、距離に基づいてテキストフラグメント間の視覚的な間隔を考慮しようとします。フラグメント間のスペース数の認識は、ドキュメントの生成方法に大きく依存するため正確でない場合があります。異なるジェネレータで作成されたドキュメントの場合、テキストフラグメント間のスペース比較に不正確さが生じる可能性があります。 |

### 関連項目

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


