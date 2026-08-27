---
title: "クラス Table"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Table クラス。page に追加できるテーブルを表します。"
type: docs
weight: 10460
url: /ja/net/aspose.pdf/table/
---
## Table class

ページに追加できるテーブルを表します。

```csharp
public sealed class Table : BaseParagraph
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Table](table/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment/) { get; set; } | テーブルの配置を取得または設定します。 |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor/) { get; set; } | テーブルの背景色を取得または設定します |
| [Border](../../aspose.pdf/table/border/) { get; set; } | 境界線を取得または設定します。 |
| [BreakText](../../aspose.pdf/table/breaktext/) { get; set; } | テーブルの改行テキストを取得または設定します |
| [Broken](../../aspose.pdf/table/broken/) { get; set; } | テーブルの垂直分割を取得または設定します; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment/) { get; set; } | テーブルの列調整を取得または設定します。 |
| [ColumnWidths](../../aspose.pdf/table/columnwidths/) { get; set; } | テーブルの列幅を取得します。 |
| [CornerStyle](../../aspose.pdf/table/cornerstyle/) { get; set; } | 罫線の角のスタイルを取得または設定します |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder/) { get; set; } | デフォルトのセル境界線を取得します; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding/) { get; set; } | デフォルトのセル余白を取得または設定します。 |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate/) { get; set; } | デフォルトのセルテキスト状態を取得または設定します。 |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth/) { get; set; } | デフォルトのセル境界線を取得します; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 段落の水平揃えを取得または設定します。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントハイパーリンクを取得または設定します（PDF ジェネレータ用）。 |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded/) { get; set; } | 列幅に含まれる罫線を取得または設定します。 |
| [IsBroken](../../aspose.pdf/table/isbroken/) { get; set; } | テーブルが分割されるかどうかを取得または設定します - 次のページで切り捨てられます。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインかどうかを取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されるように強制する bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [Left](../../aspose.pdf/table/left/) { get; set; } | テーブルの左座標を取得または設定します。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側余白を取得または設定します（pdf 生成用） |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount/) { get; set; } | テーブルの最大列数を取得または設定します |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount/) { get; set; } | 複数ページにわたって繰り返される最初の行数を取得します |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle/) { get; set; } | 繰り返し行のスタイルを取得します |
| [Rows](../../aspose.pdf/table/rows/) { get; } | テーブルの行を取得します。 |
| [Top](../../aspose.pdf/table/top/) { get; set; } | テーブルの上座標を取得または設定します。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直配置を取得または設定します |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z 順序を示す整数値を取得または設定します。ZIndex が大きいグラフは ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフはページ内のテキストの背後に配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone/)() | テーブルをクローンします。 |
| [GetHeight](../../aspose.pdf/table/getheight/)(Page) | 高さを取得します。 |
| [GetWidth](../../aspose.pdf/table/getwidth/)() | 幅を取得します。 |
| [ImportArray](../../aspose.pdf/table/importarray/)(object[], int, int, bool) | データの一次元配列をテーブルにインポートします。インポートは配列の各項目につき 1 つのセルに対応し、パラメータで定義された行と列から開始します。インポート中に、必要な行がまだ存在しないことが検出された場合（つまり、対象テーブルがすべてのデータを収めるには小さすぎる場合）、必要な行が作成されます。 |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_1)(DataTable, bool, int, int) | System.Data.DataTable からデータを Aspose.Pdf.Table にインポートします |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable)(DataTable, bool, int, byte, int, int, bool) | DataTable オブジェクトをテーブルにインポートします。 |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | DataTable オブジェクトをインポートしますが、全体としてではなく、指定された行と列のみがインポートされます。 |
| [ImportDataView](../../aspose.pdf/table/importdataview/)(DataView, bool, int, int, int, int) | DataView オブジェクトのデータをテーブルにインポートします。 |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate/)(int, TextState) | 高さを設定します。 |

### 関連項目

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


