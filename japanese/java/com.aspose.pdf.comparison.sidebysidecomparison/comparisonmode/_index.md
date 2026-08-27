---
title: "ComparisonMode"
linktitle: "ComparisonMode"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "比較モード列挙です。"
type: docs
weight: 10
url: /ja/java/com.aspose.pdf.comparison.sidebysidecomparison/comparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.Enum, com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode

```
public final class ComparisonMode extends com.aspose.ms.System.Enum
```

比較モード列挙です。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [IgnoreSpaces](#IgnoreSpaces) | すべてのスペースは無視されます。変更は単語単位でのみ検索されます。 |
| [Normal](#Normal) | 通常モード。テキストフラグメント内のスペースのみが考慮されます（ドキュメントの生成方法に依存します）。 |
| [ParseSpaces](#ParseSpaces) | このモードは通常と似ていますが、距離に基づいてテキストフラグメント間の視覚的な間隔を考慮しようとします。フラグメント間のスペース数の認識は、ドキュメントの生成方法に大きく依存するため正確でない場合があります。異なるジェネレータで作成されたドキュメントの場合、テキストフラグメント間のスペース比較に不正確さが生じる可能性があります。このオプションは、論理的ではあるものの、複雑に構造化されたドキュメントに適用した際に期待される比較結果と異なる結果を生むことがあります。 |

### IgnoreSpaces {#IgnoreSpaces}
```
public static final int IgnoreSpaces
```

すべてのスペースは無視されます。変更は単語単位でのみ検索されます。

### Normal {#Normal}
```
public static final int Normal
```

通常モード。テキストフラグメント内のスペースのみが考慮されます（ドキュメントの生成方法に依存します）。

### ParseSpaces {#ParseSpaces}
```
public static final int ParseSpaces
```

このモードは通常と似ていますが、距離に基づいてテキストフラグメント間の視覚的な間隔を考慮しようとします。フラグメント間のスペース数の認識は、ドキュメントの生成方法に大きく依存するため正確でない場合があります。異なるジェネレータで作成されたドキュメントの場合、テキストフラグメント間のスペース比較に不正確さが生じる可能性があります。このオプションは、論理的ではあるものの、複雑に構造化されたドキュメントに適用した際に期待される比較結果と異なる結果を生むことがあります。
