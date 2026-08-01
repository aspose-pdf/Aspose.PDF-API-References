---
title: "クラス ComparisonOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Comparison.ComparisonOptions クラス。PDF ドキュメントの比較オプションクラスを表します。"
type: docs
weight: 3260
url: /ja/net/aspose.pdf.comparison/comparisonoptions/
---
## ComparisonOptions class

PDF ドキュメント比較オプション クラスを表します。

```csharp
public class ComparisonOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ComparisonOptions](comparisonoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [EditOperationsOrder](../../aspose.pdf.comparison/comparisonoptions/editoperationsorder/) { get; set; } | 編集操作の順序を取得および設定します。 |
| [ExcludeAreas1](../../aspose.pdf.comparison/comparisonoptions/excludeareas1/) { get; set; } | 除外領域を取得および設定します。比較メソッドで最初のページまたはドキュメントに使用されます。このオプションは [`ExcludeTables`](./excludetables/) と共に設定できます。このオプションは [`ExtractionArea`](./extractionarea/) オプションと共に設定できません。 |
| [ExcludeAreas2](../../aspose.pdf.comparison/comparisonoptions/excludeareas2/) { get; set; } | 除外領域を取得および設定します。比較メソッドで2番目のページまたはドキュメントに使用されます。このオプションは [`ExcludeTables`](./excludetables/) と共に設定できます。このオプションは [`ExtractionArea`](./extractionarea/) オプションと共に設定できません。 |
| [ExcludeTables](../../aspose.pdf.comparison/comparisonoptions/excludetables/) { get; set; } | 比較からテーブルを除外するかどうかを決定するオプションを取得および設定します。このオプションは [`ExtractionArea`](./extractionarea/) オプションと同時に設定できません。デフォルト値は `false` です。 |
| [ExtractionArea](../../aspose.pdf.comparison/comparisonoptions/extractionarea/) { get; set; } | ページのテキストが比較される矩形領域を取得および設定します。このオプションは [`ExcludeTables`](./excludetables/)、[`ExcludeAreas1`](./excludeareas1/) および [`ExcludeAreas2`](./excludeareas2/) オプションと同時に設定できません。 |

### 関連項目

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


