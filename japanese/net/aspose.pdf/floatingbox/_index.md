---
title: "クラス FloatingBox"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.FloatingBox クラス。"
type: docs
weight: 4990
url: /ja/net/aspose.pdf/floatingbox/
---
## FloatingBox class

```csharp
public class FloatingBox : BaseParagraph
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FloatingBox](floatingbox/#constructor)() | 新しい `FloatingBox` クラスのインスタンスを初期化します。 |
| [FloatingBox](floatingbox/#constructor_1)(float, float) | 指定された幅と高さで `FloatingBox` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | 取得または設定する [`Color`](../color/) オブジェクトは、FloatingBox の背景色を示します。 |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | 取得または設定するページの背景画像（ジェネレータ専用で、Document を読み込む際には設定されません）。 |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | 取得または設定する [`BorderInfo`](../borderinfo/) オブジェクトは、FloatingBox の枠情報を示します。 |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | 取得または設定する列情報 |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | 取得または設定する float 値は、FloatingBox の高さを示します。 |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 段落の水平揃えを取得または設定します。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントハイパーリンクを取得または設定します（PDF ジェネレータ用）。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインかどうかを取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されるように強制する bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | 取得または設定する bool 値は、段落を次のページで繰り返す必要があるかどうかを示します。デフォルト値は false です。この属性は、段落自体と、その ReferenceParagraphID が参照するオブジェクトの両方が RepeatingRows に含まれている場合にのみ有効です。 |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | テーブルの左座標を取得または設定します。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側余白を取得または設定します（pdf 生成用） |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | 取得または設定する [`MarginInfo`](../margininfo/) オブジェクトは、FloatingBox のパディングを示します。 |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | 取得または設定する [`Paragraphs`](./paragraphs/) コレクションは、セル内のすべての段落を示します。 |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | ページ上の FloatingBox の位置を決定するバリアントを指定します。 |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | テーブルの上座標を取得または設定します。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直配置を取得または設定します |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | 取得または設定する float 値は、FloatingBox の幅を示します。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z 順序を示す整数値を取得または設定します。ZIndex が大きいグラフは ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフはページ内のテキストの背後に配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | `FloatingBox` オブジェクトを新しくクローンします。FloatingBox 内の Paragraphs はクローンされません。 |

### 関連項目

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


