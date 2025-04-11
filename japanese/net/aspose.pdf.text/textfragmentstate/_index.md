---
title: Class TextFragmentState
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragmentState クラス。テキストフラグメントのテキスト状態を表します
type: docs
weight: 10970
url: /ja/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState クラス

テキストフラグメントのテキスト状態を表します。

```csharp
public sealed class TextFragmentState : TextState
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | 指定された [`TextFragment`](../textfragment/) オブジェクトを使用して `TextFragmentState` オブジェクトの新しいインスタンスを初期化します。この `TextFragmentState` の初期化はサポートされていません。TextFragmentState は [`TextState`](../textfragment/textstate/) プロパティでのみ利用可能です。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | [`TextFragment`](../textfragment/) オブジェクトで表されるテキストの背景色を設定します |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | [`TextFragment`](../textfragment/) オブジェクトで表されるテキストの文字間隔を取得または設定します。 |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | テキストの CoordinateOrigin を取得または設定します。CoordinateOrigin が Descender の場合、テキストの Y 座標はフォントの最下点に対応します。CoordinateOrigin が BaseLine の場合、テキストの Y 座標はフォントのベースラインに対応します。デフォルト値は Descender です。フォントの Descent 値が大きすぎる場合、テキストは他のフォントよりも高くレンダリングされることがあります。この場合、より良いテキストレンダリングのために CoordinateOrigin BaseLine を選択できます。 |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | テキストの矩形境界が描画されるフラグを取得または設定します。 |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | [`TextFragment`](../textfragment/) オブジェクトで表されるテキストのフォントを取得または設定します |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | [`TextFragment`](../textfragment/) オブジェクトで表されるテキストのフォントサイズを取得または設定します |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | [`TextFragment`](../textfragment/) オブジェクトで表されるテキストのフォントスタイルを設定します |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | [`TextFragment`](../textfragment/) オブジェクトで表されるテキストの前景色を取得または設定します |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | 書式設定オプションを取得または設定します。オプションの設定は、生成シナリオでのみ有効になります。 |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | テキストの水平配置を取得または設定します。 |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | [`TextFragment`](../textfragment/) オブジェクトで表されるテキストの水平スケーリングを取得または設定します。 |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | テキストの不可視性を取得または設定します。 |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | テキストの行間隔を取得または設定します。 |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | テキストのレンダリングモードを取得または設定します。 |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | 回転角度を度単位で取得または設定します。 |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | [`TextFragment`](../textfragment/) オブジェクトで表されるテキストの打ち消し線を取得または設定します |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | [`TextFragment`](../textfragment/) のレンダリング（ストロークテキスト、矩形境界）の色ストローク操作を取得または設定します |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | [`TextFragment`](../textfragment/) オブジェクトで表されるテキストの下付き文字を取得または設定します。 |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | [`TextFragment`](../textfragment/) オブジェクトで表されるテキストの上付き文字を取得または設定します。 |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | テキストのタブストップを取得します。 |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | [`TextFragment`](../textfragment/) オブジェクトで表されるテキストの下線を取得または設定します |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | テキストの単語間隔を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | 別の textState から設定を適用します。 |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | 入力文字列が定義された矩形内に配置できるかどうかを確認します。 |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | 文字の高さを測定します。（2 つのメソッド） |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | 文字列を測定します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | デフォルトフォントのスペース文字の幅におけるタブのデフォルト値。 |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | このタグをテキストに配置してタブを宣言できます。 |

## 備考

テキストの次のプロパティを変更する方法を提供します：フォント ([`Font`](./font/) プロパティ) フォントサイズ ([`FontSize`](./fontsize/) プロパティ) フォントスタイル ([`FontStyle`](./fontstyle/) プロパティ) 前景色 ([`ForegroundColor`](./foregroundcolor/) プロパティ) 背景色 ([`BackgroundColor`](./backgroundcolor/) プロパティ) `TextFragmentState` プロパティを変更すると、内部の [`Segments`](../textfragment/segments/) コレクションが変更される可能性があることに注意してください。TextFragment は集約オブジェクトであり、内部セグメントを再配置したり、単一のセグメントに統合したりすることがあります。[`Segments`](../textfragment/segments/) コレクションを変更せずに維持する必要がある場合は、内部セグメントを個別に変更してください。

## 例

この例は、[`TextState`](../textstate/) オブジェクトを使用してテキストの色とフォントサイズを変更する方法を示しています。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 参照

* クラス [TextFragmentAbsorber](../textfragmentabsorber/)
* クラス [Document](../../aspose.pdf/document/)
* クラス [TextState](../textstate/)
* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)