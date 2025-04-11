---
title: Class ComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.ComparisonOptions クラス。PDF ドキュメント比較オプションクラスを表します
type: docs
weight: 3150
url: /ja/net/aspose.pdf.comparison/comparisonoptions/
---
## ComparisonOptions クラス

PDF ドキュメント比較オプションクラスを表します。

```csharp
public class ComparisonOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ComparisonOptions](comparisonoptions/)() | デフォルトコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [EditOperationsOrder](../../aspose.pdf.comparison/comparisonoptions/editoperationsorder/) { get; set; } | 編集操作の順序を取得および設定します。 |
| [ExcludeAreas1](../../aspose.pdf.comparison/comparisonoptions/excludeareas1/) { get; set; } | 除外エリアを取得および設定します。比較メソッドの最初のページまたはドキュメントに使用されます。このオプションは [`ExcludeTables`](./excludetables/) と一緒に設定できます。このオプションは [`ExtractionArea`](./extractionarea/) オプションと一緒に設定することはできません。 |
| [ExcludeAreas2](../../aspose.pdf.comparison/comparisonoptions/excludeareas2/) { get; set; } | 除外エリアを取得および設定します。比較メソッドの2 番目のページまたはドキュメントに使用されます。このオプションは [`ExcludeTables`](./excludetables/) と一緒に設定できます。このオプションは [`ExtractionArea`](./extractionarea/) オプションと一緒に設定することはできません。 |
| [ExcludeTables](../../aspose.pdf.comparison/comparisonoptions/excludetables/) { get; set; } | 比較からテーブルを除外するかどうかを決定するオプションを取得および設定します。このオプションは [`ExtractionArea`](./extractionarea/) オプションと一緒に設定することはできません。デフォルト値は `false` です。 |
| [ExtractionArea](../../aspose.pdf.comparison/comparisonoptions/extractionarea/) { get; set; } | ページのテキストが比較される矩形領域を取得および設定します。このオプションは [`ExcludeTables`](./excludetables/)、[`ExcludeAreas1`](./excludeareas1/) および [`ExcludeAreas2`](./excludeareas2/) オプションと一緒に設定することはできません。 |

### 参照

* 名前空間 [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* アセンブリ [Aspose.PDF](../../)