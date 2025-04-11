---
title: Class Graph
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Drawing.Graph クラス。グラフのグラフィックス生成者段落を表します
type: docs
weight: 3940
url: /ja/net/aspose.pdf.drawing/graph/
---
## グラフ クラス

グラフ - グラフィックス生成者段落を表します。

```csharp
public sealed class Graph : BaseParagraph
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Graph](graph/#constructor)(double, double) | `Graph` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Border](../../aspose.pdf.drawing/graph/border/) { get; set; } | ボーダーを取得または設定します。 |
| [GraphInfo](../../aspose.pdf.drawing/graph/graphinfo/) { get; set; } | グラフ情報（色、線の幅など）を示す [`GraphInfo`](./graphinfo/) オブジェクトを取得または設定します。 |
| [Height](../../aspose.pdf.drawing/graph/height/) { get; set; } | グラフの高さを示す float 値を取得または設定します。単位はポイントです。 |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 段落の水平揃えを取得または設定します。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントのハイパーリンク（PDF生成用）を取得または設定します。 |
| [IsChangePosition](../../aspose.pdf.drawing/graph/ischangeposition/) { get; set; } | 段落処理後に現在の位置を変更するかどうかを取得または設定します。（デフォルトは true） |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列にあるかどうかを示す bool 値を取得または設定します。デフォルトは false です。（PDF生成用） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインであるかどうかを取得または設定します。デフォルトは false です。（PDF生成用） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されることを強制する bool 値を取得または設定します。デフォルトは false です。（PDF生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。（PDF生成用） |
| [Left](../../aspose.pdf.drawing/graph/left/) { get; set; } | テーブルの左座標を取得または設定します。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側のマージンを取得または設定します。（PDF生成用） |
| [Shapes](../../aspose.pdf.drawing/graph/shapes/) { get; set; } | グラフ内のすべての形状を示す [`Shapes`](./shapes/) コレクションを取得または設定します。 |
| [Title](../../aspose.pdf.drawing/graph/title/) { get; set; } | グラフのタイトルを示す文字列値を取得または設定します。 |
| [Top](../../aspose.pdf.drawing/graph/top/) { get; set; } | テーブルの上部座標を取得または設定します。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直揃えを取得または設定します。 |
| [Width](../../aspose.pdf.drawing/graph/width/) { get; set; } | グラフの幅を示す float 値を取得または設定します。単位はポイントです。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z-オーダーを示す int 値を取得または設定します。大きな ZIndex を持つグラフは、小さな ZIndex を持つグラフの上に配置されます。ZIndex は負の値を取ることができます。負の ZIndex を持つグラフは、ページ内のテキストの後ろに配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../aspose.pdf.drawing/graph/clone/)() | グラフをクローンします。 |

### 参照

* クラス [BaseParagraph](../../aspose.pdf/baseparagraph/)
* 名前空間 [Aspose.Pdf.Drawing](../../aspose.pdf.drawing/)
* アセンブリ [Aspose.PDF](../../)