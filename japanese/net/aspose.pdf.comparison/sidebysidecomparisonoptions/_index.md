---
title: "クラス SideBySideComparisonOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Comparison.SideBySideComparisonOptions クラス。ドキュメントをサイドバイサイド出力で比較するためのオプション クラスを表します。"
type: docs
weight: 3400
url: /ja/net/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## SideBySideComparisonOptions class

ドキュメントを並列出力で比較するためのオプションクラスを表します。

```csharp
public class SideBySideComparisonOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SideBySideComparisonOptions](sidebysidecomparisonoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AdditionalChangeMarks](../../aspose.pdf.comparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | 追加の変更マーカーを表示するかどうかを決定するプロパティを取得および設定します。設定すると、現在のページにはないが別のページに存在する変更マークを表示します。変更が単語間にある場合、マークは空白文字に対して正確に配置されない可能性があります。デフォルト値は `false` です。 |
| [ComparisonArea1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | 比較領域を取得および設定します。比較メソッドで最初のページまたはドキュメントに使用されます。このオプションは [`ExcludeTables`](./excludetables/)、[`ExcludeAreas1`](./excludeareas1/) および [`ExcludeAreas2`](./excludeareas2/) オプションと同時に設定できません。 |
| [ComparisonArea2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | 比較領域を取得および設定します。比較メソッドで2番目のページまたはドキュメントに使用されます。このオプションは [`ExcludeTables`](./excludetables/)、[`ExcludeAreas1`](./excludeareas1/) および [`ExcludeAreas2`](./excludeareas2/) オプションと同時に設定できません。 |
| [ComparisonMode](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | 比較モードを取得および設定します。デフォルト値は !:SideBySideComparison.ComparisonMode.IgnoreSpaces です。 |
| [ExcludeAreas1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | 除外領域を取得および設定します。比較メソッドで最初のページまたはドキュメントに使用されます。このオプションは [`ExcludeTables`](./excludetables/) と一緒に設定できますが、[`ComparisonArea1`](./comparisonarea1/) オプションとは同時に設定できません。 |
| [ExcludeAreas2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | 除外領域を取得および設定します。比較メソッドで2番目のページまたはドキュメントに使用されます。このオプションは [`ExcludeTables`](./excludetables/) と一緒に設定できますが、[`ComparisonArea2`](./comparisonarea2/) オプションとは同時に設定できません。 |
| [ExcludeTables](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | テーブルを比較から除外するかどうかを決定するオプションを取得および設定します。このオプションは [`ComparisonArea1`](./comparisonarea1/) および [`ComparisonArea2`](./comparisonarea2/) と同時に設定できません。デフォルト値は `false` です。 |

### 関連項目

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


