---
title: Class FloatingBox
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FloatingBox クラス。
type: docs
weight: 4870
url: /ja/net/aspose.pdf/floatingbox/
---
## FloatingBox クラス

```csharp
public class FloatingBox : BaseParagraph
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FloatingBox](floatingbox/#constructor)() | `FloatingBox` クラスの新しいインスタンスを初期化します。 |
| [FloatingBox](floatingbox/#constructor_1)(float, float) | 指定された幅と高さで `FloatingBox` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | 浮動ボックスの背景色を示す [`Color`](../color/) オブジェクトを取得または設定します。 |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | ページの背景画像を取得または設定します（生成者専用、ドキュメントを読み取るときには設定されません）。 |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | 浮動ボックスの境界情報を示す [`BorderInfo`](../borderinfo/) オブジェクトを取得または設定します。 |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | 列情報を取得または設定します。 |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | 浮動ボックスの高さを示す float 値を取得または設定します。 |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 段落の水平揃えを取得または設定します。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントのハイパーリンクを取得または設定します（PDF 生成者用）。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列にあるかどうかを示す bool 値を取得または設定します。デフォルトは false です（PDF 生成用）。 |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインであるかどうかを示す bool 値を取得または設定します。デフォルトは false です（PDF 生成用）。 |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されることを強制する bool 値を取得または設定します。デフォルトは false です（PDF 生成用）。 |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です（PDF 生成用）。 |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | 段落が次のページで繰り返される必要があるかどうかを示す bool 値を取得または設定します。デフォルト値は false です。この属性は、段落自体とその ReferenceParagraphID が参照するオブジェクトの両方が RepeatingRows に含まれている場合にのみ有効です。 |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | テーブルの左座標を取得または設定します。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外部マージンを取得または設定します（PDF 生成用）。 |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | 浮動ボックスのパディングを示す [`MarginInfo`](../margininfo/) オブジェクトを取得または設定します。 |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | セル内のすべての段落を示す [`Paragraphs`](./paragraphs/) コレクションを取得または設定します。 |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | ページ上の FloatingBox の位置を決定するためのバリアントを指定します。 |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | テーブルの上座標を取得または設定します。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直揃えを取得または設定します。 |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | 浮動ボックスの幅を示す float 値を取得または設定します。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z-オーダーを示す int 値を取得または設定します。大きな ZIndex を持つグラフは、小さな ZIndex を持つグラフの上に配置されます。ZIndex は負の値を持つことができます。負の ZIndex を持つグラフは、ページ内のテキストの後ろに配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | 新しい `FloatingBox` オブジェクトをクローンします。浮動ボックス内の段落はクローンされません。 |

### 参照

* クラス [BaseParagraph](../baseparagraph/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)