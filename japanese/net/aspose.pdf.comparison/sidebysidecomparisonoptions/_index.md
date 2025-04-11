---
title: Class SideBySideComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.SideBySideComparisonOptions クラス。サイドバイサイド出力でドキュメントを比較するためのオプションクラスを表します。
type: docs
weight: 3290
url: /ja/net/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## SideBySideComparisonOptions クラス

サイドバイサイド出力でドキュメントを比較するためのオプションクラスを表します。

```csharp
public class SideBySideComparisonOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SideBySideComparisonOptions](sidebysidecomparisonoptions/)() | デフォルトコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AdditionalChangeMarks](../../aspose.pdf.comparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | 追加の変更マーカーが表示されるかどうかを決定するプロパティを取得および設定します。設定すると、現在のページにはないが別のページに存在する変更マークが表示されます。変更が単語の間にある場合、マークは空白文字に対して正確に位置付けられない場合があります。デフォルト値は `false` です。 |
| [ComparisonArea1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | 比較エリアを取得および設定します。比較メソッドの最初のページまたはドキュメントに使用されます。このオプションは、[`ExcludeTables`](./excludetables/)、[`ExcludeAreas1`](./excludeareas1/) および [`ExcludeAreas2`](./excludeareas2/) オプションと一緒に設定することはできません。 |
| [ComparisonArea2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | 比較エリアを取得および設定します。比較メソッドの2番目のページまたはドキュメントに使用されます。このオプションは、[`ExcludeTables`](./excludetables/)、[`ExcludeAreas1`](./excludeareas1/) および [`ExcludeAreas2`](./excludeareas2/) オプションと一緒に設定することはできません。 |
| [ComparisonMode](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | 比較モードを取得および設定します。デフォルト値は !:SideBySideComparison.ComparisonMode.IgnoreSpaces です。 |
| [ExcludeAreas1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | 除外エリアを取得および設定します。比較メソッドの最初のページまたはドキュメントに使用されます。このオプションは、[`ExcludeTables`](./excludetables/) と一緒に設定できます。このオプションは、[`ComparisonArea1`](./comparisonarea1/) オプションと一緒に設定することはできません。 |
| [ExcludeAreas2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | 除外エリアを取得および設定します。比較メソッドの2番目のページまたはドキュメントに使用されます。このオプションは、[`ExcludeTables`](./excludetables/) と一緒に設定できます。このオプションは、[`ComparisonArea2`](./comparisonarea2/) オプションと一緒に設定することはできません。 |
| [ExcludeTables](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | テーブルが比較から除外されるかどうかを決定するオプションを取得および設定します。このオプションは、[`ComparisonArea1`](./comparisonarea1/) および [`ComparisonArea2`](./comparisonarea2/) と一緒に設定することはできません。デフォルト値は `false` です。 |

### 参照

* 名前空間 [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* アセンブリ [Aspose.PDF](../../)