---
title: Class Table
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Table クラス。ページに追加できるテーブルを表します
type: docs
weight: 10280
url: /ja/net/aspose.pdf/table/
---
## テーブル クラス

ページに追加できるテーブルを表します。

```csharp
public sealed class Table : BaseParagraph
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Table](table/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment/) { get; set; } | テーブルの配置を取得または設定します。 |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor/) { get; set; } | テーブルの背景色を取得または設定します。 |
| [Border](../../aspose.pdf/table/border/) { get; set; } | ボーダーを取得または設定します。 |
| [BreakText](../../aspose.pdf/table/breaktext/) { get; set; } | テーブルの改行テキストを取得または設定します。 |
| [Broken](../../aspose.pdf/table/broken/) { get; set; } | テーブルの垂直ブロークンを取得または設定します。 |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment/) { get; set; } | テーブルの列調整を取得または設定します。 |
| [ColumnWidths](../../aspose.pdf/table/columnwidths/) { get; set; } | テーブルの列幅を取得します。 |
| [CornerStyle](../../aspose.pdf/table/cornerstyle/) { get; set; } | ボーダーコーナーのスタイルを取得または設定します。 |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder/) { get; set; } | デフォルトのセルボーダーを取得します。 |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding/) { get; set; } | デフォルトのセルパディングを取得または設定します。 |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate/) { get; set; } | デフォルトのセルテキスト状態を取得または設定します。 |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth/) { get; set; } | デフォルトの列幅を取得または設定します。 |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 段落の水平配置を取得または設定します。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントハイパーリンクを取得または設定します（PDFジェネレーター用）。 |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded/) { get; set; } | 列幅にボーダーが含まれているかどうかを取得または設定します。 |
| [IsBroken](../../aspose.pdf/table/isbroken/) { get; set; } | テーブルが壊れているかどうかを取得または設定します - 次のページに切り捨てられます。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列にあるかどうかを示すブール値を取得または設定します。デフォルトは false です（PDF生成用）。 |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインであるかどうかを取得または設定します。デフォルトは false です（PDF生成用）。 |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されることを強制するブール値を取得または設定します。デフォルトは false です（PDF生成用）。 |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示すブール値を取得または設定します。デフォルトは false です（PDF生成用）。 |
| [Left](../../aspose.pdf/table/left/) { get; set; } | テーブルの左座標を取得または設定します。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側のマージンを取得または設定します（PDF生成用）。 |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount/) { get; set; } | テーブルの最大列数を取得または設定します。 |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount/) { get; set; } | 複数ページに繰り返される最初の行数を取得します。 |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle/) { get; set; } | 繰り返される行のスタイルを取得します。 |
| [Rows](../../aspose.pdf/table/rows/) { get; } | テーブルの行を取得します。 |
| [Top](../../aspose.pdf/table/top/) { get; set; } | テーブルの上座標を取得または設定します。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直配置を取得または設定します。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z-オーダーを示す int 値を取得または設定します。大きな ZIndex を持つグラフは、小さな ZIndex を持つグラフの上に配置されます。ZIndex は負の値を持つことができます。負の ZIndex を持つグラフは、ページ内のテキストの後ろに配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone/)() | テーブルをクローンします。 |
| [GetHeight](../../aspose.pdf/table/getheight/)(Page) | 高さを取得します。 |
| [GetWidth](../../aspose.pdf/table/getwidth/)() | 幅を取得します。 |
| [ImportArray](../../aspose.pdf/table/importarray/)(object[], int, int, bool) | 一次元配列のデータをテーブルにインポートします。インポートは各配列のアイテムごとに1つのセルを使用し、パラメータで定義された行と列から開始します。インポート中に、必要な行がまだ存在しないことが検出された場合（つまり、ターゲットテーブルがすべてのデータを吸収するには小さすぎる場合）、必要な行が作成されます。 |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_1)(DataTable, bool, int, int) | System.Data.DataTable から Aspose.Pdf.Table にデータをインポートします。 |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable)(DataTable, bool, int, byte, int, int, bool) | DataTable オブジェクトをテーブルにインポートします。 |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | DataTable オブジェクトをインポートしますが、全体のエンティティとしてではありません。指定された行と列のみがインポートされます。 |
| [ImportDataView](../../aspose.pdf/table/importdataview/)(DataView, bool, int, int, int, int) | DataView オブジェクトのデータをテーブルにインポートします。 |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate/)(int, TextState) | 高さを設定します。 |

### 参照

* クラス [BaseParagraph](../baseparagraph/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)