---
title: "Graph クラス"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Drawing.Graph クラス。グラフ グラフィックス ジェネレータ段落を表します"
type: docs
weight: 4060
url: /ja/net/aspose.pdf.drawing/graph/
---
## Graph class

グラフ - グラフィックジェネレータ段落を表します。

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
| [Border](../../aspose.pdf.drawing/graph/border/) { get; set; } | 境界線を取得または設定します。 |
| [GraphInfo](../../aspose.pdf.drawing/graph/graphinfo/) { get; set; } | [`GraphInfo`](./graphinfo/) オブジェクトを取得または設定します。このオブジェクトは、色や線幅などのグラフ情報を示します。 |
| [Height](../../aspose.pdf.drawing/graph/height/) { get; set; } | グラフの高さを示す float 値を取得または設定します。単位はポイントです。 |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 段落の水平揃えを取得または設定します。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントハイパーリンクを取得または設定します（PDF ジェネレータ用）。 |
| [IsChangePosition](../../aspose.pdf.drawing/graph/ischangeposition/) { get; set; } | 段落の処理後に現在の位置を変更するかどうかを取得または設定します。（デフォルトは true） |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインかどうかを取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されるように強制する bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [Left](../../aspose.pdf.drawing/graph/left/) { get; set; } | テーブルの左座標を取得または設定します。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側余白を取得または設定します（pdf 生成用） |
| [Shapes](../../aspose.pdf.drawing/graph/shapes/) { get; set; } | グラフ内のすべての形状を示す [`Shapes`](./shapes/) コレクションを取得または設定します。 |
| [Title](../../aspose.pdf.drawing/graph/title/) { get; set; } | グラフのタイトルを示す文字列値を取得または設定します。 |
| [Top](../../aspose.pdf.drawing/graph/top/) { get; set; } | テーブルの上座標を取得または設定します。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直配置を取得または設定します |
| [Width](../../aspose.pdf.drawing/graph/width/) { get; set; } | グラフの幅を示す float 値を取得または設定します。単位はポイントです。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z 順序を示す整数値を取得または設定します。ZIndex が大きいグラフは ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフはページ内のテキストの背後に配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../aspose.pdf.drawing/graph/clone/)() | グラフをクローンします。 |

### 関連項目

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Drawing](../../aspose.pdf.drawing/)
* assembly [Aspose.PDF](../../)


