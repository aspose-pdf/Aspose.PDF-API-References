---
title: "クラス TextFragmentState"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text.TextFragmentState クラス。テキストフラグメントのテキスト状態を表します。"
type: docs
weight: 11150
url: /ja/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class

テキストフラグメントのテキスト状態を表します。

```csharp
public sealed class TextFragmentState : TextState
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | 指定された [`TextFragment`](../textfragment/) オブジェクトを使用して `TextFragmentState` オブジェクトの新しいインスタンスを初期化します。この `TextFragmentState` の初期化はサポートされていません。TextFragmentState は [`TextState`](../textfragment/textstate/) プロパティと共にのみ使用可能です。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | テキストの背景色を設定します。対象は [`TextFragment`](../textfragment/) オブジェクトです。 |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | テキストの文字間隔を取得または設定します。対象は [`TextFragment`](../textfragment/) オブジェクトです。 |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | テキストの CoordinateOrigin を取得または設定します。CoordinateOrigin が Descender の場合、テキストの Y 座標はフォントの最下点に対応します。CoordinateOrigin が BaseLine の場合、テキストの Y 座標はフォントのベースラインに対応します。既定値は Descender です。フォントの Descent 値が大きすぎると、テキストが他のフォントよりも高く描画されることがあります。このような場合、より適切なテキスト描画のために CoordinateOrigin を BaseLine に設定できます。 |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | テキスト矩形の枠線が描画されるかどうかのフラグを取得または設定します。 |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | テキストのフォントを取得または設定します。対象は [`TextFragment`](../textfragment/) オブジェクトです。 |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | テキストのフォントサイズを取得または設定します。対象は [`TextFragment`](../textfragment/) オブジェクトです。 |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | テキストのフォントスタイルを設定します。対象は [`TextFragment`](../textfragment/) オブジェクトです。 |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | テキストの前景色を取得または設定します。対象は [`TextFragment`](../textfragment/) オブジェクトです。 |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | 書式設定オプションを取得または設定します。オプションの設定はジェネレータシナリオでのみ有効です。 |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | テキストの水平配置を取得または設定します。 |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | テキストの水平スケーリングを取得または設定します。対象は [`TextFragment`](../textfragment/) オブジェクトです。 |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | テキストの不可視性を取得または設定します。 |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | テキストの行間を取得または設定します。 |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | テキストのレンダリングモードを取得または設定します。 |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | 回転角度（度）を取得または設定します。 |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | テキストの取り消し線を取得または設定します。対象は [`TextFragment`](../textfragment/) オブジェクトです。 |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | `[`TextFragment`](../textfragment/)` のレンダリングにおけるカラー描画操作（テキストのストローク、矩形枠）を取得または設定します。 |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | テキストのサブスクリプトを取得または設定します。対象は [`TextFragment`](../textfragment/) オブジェクトです。 |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | テキストの上付き文字を取得または設定します。対象は [`TextFragment`](../textfragment/) オブジェクトです。 |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | テキストのタブストップを取得します。 |
| [TabTag](../../aspose.pdf.text/textstate/tabtag/) { get; } | テキスト内にこのタグを配置してタブ設定を宣言できます。 |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | テキストの下線を取得または設定します。これは[`TextFragment`](../textfragment/)オブジェクトで表されます。 |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | テキストの単語間隔を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | 別の textState から設定を適用します。 |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | 入力文字列が定義された矩形内に配置できるかどうかをチェックします。 |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | 文字の高さを測定します。（2つのメソッド） |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | 文字列を測定します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | デフォルトフォントのスペース文字幅におけるタブ設定のデフォルト値です。 |

## 備考

テキストの以下のプロパティを変更する方法を提供します：フォント（[`Font`](./font/) プロパティ）、フォントサイズ（[`FontSize`](./fontsize/) プロパティ）、フォントスタイル（[`FontStyle`](./fontstyle/) プロパティ）、前景色（[`ForegroundColor`](./foregroundcolor/) プロパティ）、背景色（[`BackgroundColor`](./backgroundcolor/) プロパティ）。`TextFragmentState` のプロパティを変更すると、TextFragment が集約オブジェクトであり、内部セグメントを再配置したり単一のセグメントに結合したりする可能性があるため、内部の [`Segments`](../textfragment/segments/) コレクションが変更されることに注意してください。[`Segments`](../textfragment/segments/) コレクションを変更せずに保持する必要がある場合は、内部セグメントを個別に変更してください。

## 例

この例は、[`TextState`](../textstate/) オブジェクトを使用してテキストの色とフォントサイズを変更する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現箇所の前景色を変更する
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// 最初のテキスト出現のフォントサイズを変更する
absorber.TextFragments[1].TextState.FontSize = 15;

// 保存 document
doc.Save(@"D:\Tests\output.pdf");  
```

### 関連項目

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* class [TextState](../textstate/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


