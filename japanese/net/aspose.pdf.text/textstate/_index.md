---
title: Class TextState
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextState クラス。テキストのテキスト状態を表します。
type: docs
weight: 11070
url: /ja/net/aspose.pdf.text/textstate/
---
## TextState クラス

テキストのテキスト状態を表します。

```csharp
public class TextState
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextState](textstate/#constructor)() | テキスト状態オブジェクトを作成します。 |
| [TextState](textstate/#constructor_2)(Color) | 前景色の指定でテキスト状態オブジェクトを作成します。 |
| [TextState](textstate/#constructor_1)(double) | フォントサイズの指定でテキスト状態オブジェクトを作成します。 |
| [TextState](textstate/#constructor_4)(string) | フォントファミリの指定でテキスト状態オブジェクトを作成します。 |
| [TextState](textstate/#constructor_3)(Color, double) | 前景色とフォントサイズの指定でテキスト状態オブジェクトを作成します。 |
| [TextState](textstate/#constructor_6)(string, double) | フォントファミリとフォントサイズの指定でテキスト状態オブジェクトを作成します。 |
| [TextState](textstate/#constructor_5)(string, bool, bool) | フォントファミリとフォントスタイルの指定でテキスト状態オブジェクトを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [BackgroundColor](../../aspose.pdf.text/textstate/backgroundcolor/) { get; set; } | テキストの背景色を設定します。 |
| virtual [CharacterSpacing](../../aspose.pdf.text/textstate/characterspacing/) { get; set; } | テキストの文字間隔を取得または設定します。 |
| virtual [CoordinateOrigin](../../aspose.pdf.text/textstate/coordinateorigin/) { get; set; } | テキストの CoordinateOrigin を取得または設定します。CoordinateOrigin が Descender の場合、テキストの Y 座標はフォントの最下点に対応します。CoordinateOrigin が BaseLine の場合、テキストの Y 座標はフォントのベースラインに対応します。デフォルト値は Descender です。フォントの Descent 値が大きすぎる場合、テキストは他のフォントよりも高くレンダリングされることがあります。この場合、より良いテキストレンダリングのために CoordinateOrigin BaseLine を選択できます。 |
| virtual [Font](../../aspose.pdf.text/textstate/font/) { get; set; } | テキストのフォントを取得または設定します。 |
| virtual [FontSize](../../aspose.pdf.text/textstate/fontsize/) { get; set; } | テキストのフォントサイズを取得または設定します。 |
| virtual [FontStyle](../../aspose.pdf.text/textstate/fontstyle/) { get; set; } | テキストのフォントスタイルを設定します。 |
| virtual [ForegroundColor](../../aspose.pdf.text/textstate/foregroundcolor/) { get; set; } | テキストの前景色を取得または設定します。 |
| virtual [HorizontalAlignment](../../aspose.pdf.text/textstate/horizontalalignment/) { get; set; } | テキストの水平揃えを取得または設定します。 |
| virtual [HorizontalScaling](../../aspose.pdf.text/textstate/horizontalscaling/) { get; set; } | テキストの水平スケーリングを取得または設定します。 |
| virtual [Invisible](../../aspose.pdf.text/textstate/invisible/) { get; set; } | テキストの不可視性を取得または設定します。これは基本的に [`RenderingMode`](./renderingmode/) の状態を反映しますが、一部の特別なケース（クリッピングなど）を除きます。 |
| virtual [LineSpacing](../../aspose.pdf.text/textstate/linespacing/) { get; set; } | テキストの行間隔を取得または設定します。 |
| virtual [RenderingMode](../../aspose.pdf.text/textstate/renderingmode/) { get; set; } | テキストのレンダリングモードを取得または設定します。 |
| virtual [StrikeOut](../../aspose.pdf.text/textstate/strikeout/) { get; set; } | テキストの取り消し線を取得または設定します。これは [`TextSegment`](../textsegment/) オブジェクトで表されます。 |
| virtual [StrokingColor](../../aspose.pdf.text/textstate/strokingcolor/) { get; set; } | テキストの前景色を取得または設定します。 |
| virtual [Subscript](../../aspose.pdf.text/textstate/subscript/) { get; set; } | テキストの下付き文字を取得または設定します。 |
| virtual [Superscript](../../aspose.pdf.text/textstate/superscript/) { get; set; } | テキストの上付き文字を取得または設定します。 |
| virtual [Underline](../../aspose.pdf.text/textstate/underline/) { get; set; } | テキストの下線を取得または設定します。これは [`TextFragment`](../textfragment/) オブジェクトで表されます。 |
| virtual [WordSpacing](../../aspose.pdf.text/textstate/wordspacing/) { get; set; } | テキストの単語間隔を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [ApplyChangesFrom](../../aspose.pdf.text/textstate/applychangesfrom/)(TextState) | 別の textState から設定を適用します。 |
| [MeasureHeight](../../aspose.pdf.text/textstate/measureheight/)(char) | 文字の高さを測定します。 |
| virtual [MeasureString](../../aspose.pdf.text/textstate/measurestring/)(string) | 文字列を測定します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | デフォルトフォントのスペース文字の幅におけるタブのデフォルト値。 |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | テキストにこのタグを配置してタブを宣言できます。 |

### 参照

* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)