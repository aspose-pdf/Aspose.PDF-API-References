---
title: "クラス PageNumberStamp"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.PageNumberStamp クラス。ページ番号スタンプを表し、ページに番号付けするために使用されます。"
type: docs
weight: 8370
url: /ja/net/aspose.pdf/pagenumberstamp/
---
## PageNumberStamp class

ページ番号スタンプを表し、ページに番号付けするために使用されます。

```csharp
public sealed class PageNumberStamp : TextStamp
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PageNumberStamp](pagenumberstamp/#constructor)() | `PageNumberStamp` クラスの新しいインスタンスを初期化します。フォーマットは "#" に設定されます。 |
| [PageNumberStamp](pagenumberstamp/#constructor_1)(FormattedText) | 書式設定されたテキストで PageNumberStamp を作成します。 |
| [PageNumberStamp](pagenumberstamp/#constructor_2)(string) | `PageNumberStamp` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | フォントサイズの精度を自動的に調整します。デフォルト値: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | 有効にすると、フォントサイズは自動的に調整され、サイズが [`Width`](../textstamp/width/) と [`Height`](../textstamp/height/) のスタンプ矩形に合わせられます。デフォルトの幅と高さはページ矩形から取得されます。 |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | コンテンツが背景としてスタンプされているかを示す bool 値を設定または取得します。値が true の場合、スタンプコンテンツは下部に配置されます。デフォルトでは、値は false で、スタンプコンテンツは上部に配置されます。 |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | スタンプの下余白を取得または設定します。 |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | このプロパティはページ上でスタンプが描画される方法を決定します。Draw = true の場合、スタンプはグラフィックオペレーターとして描画され、draw = false の場合はテキストとして描画されます。 |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | スタンプが配置された後の実際のフォントサイズです。（コンストラクタで指定された初期フォントサイズと、'AutoAdjustFontSizeToFitStampRectangle' オプションが有効な場合は異なる場合があります。） |
| [Format](../../aspose.pdf/pagenumberstamp/format/) { get; set; } | ページ番号をスタンプするための文字列値です。値には文字 ‘#’ を含める必要があり、スタンプ処理中にページ番号に置き換えられます。 |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | page 上のスタンプの希望高さ。 |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | page 上のスタンプの水平配置を取得または設定します。 |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | テキストの両端揃えを定義します。このプロパティが true に設定されている場合、テキストの左端と右端が揃えられます。デフォルト値: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | スタンプの左余白を取得または設定します。 |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | WordWrap オプションの最大行高さです。 |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | フォントが要求された文字を含まない場合の動作を定義するモードを取得または設定します。 |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle/) { get; set; } | このスタンプで使用される番号付けスタイルです。 |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | スタンプの不透明度を示す値を取得または設定します。値は 0.0 から 1.0 の範囲です。デフォルトでは値は 1.0 です。 |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | スタンプの輪郭の不透明度を示す値を取得または設定します。値は 0.0 から 1.0 の範囲です。デフォルトでは値は 1.0 です。 |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | スタンプの輪郭幅の値を取得または設定します。デフォルトでは値は 1.0 です。 |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | 必要な文字がユーザーフォントに含まれていない場合に置換に使用されるフォントを取得または設定します。 |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | スタンプの右余白を取得または設定します。 |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | スタンプコンテンツの回転を[`Rotation`](../rotation/) の値に従って設定または取得します。注: このプロパティは 90 度の倍数 (0, 90, 180, 270 度) の角度を設定するためのものです。任意の角度を設定するには RotateAngle プロパティを使用します。ArbitraryAngle で設定された角度が 90 の倍数でない場合、Rotate プロパティは Rotation.None を返します。 |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | スタンプの回転角度を度単位で取得または設定します。このプロパティは任意の回転角度を設定できます。 |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | テキストのスケーリングを定義します。このプロパティが true に設定され、Width の値が指定されている場合、テキストは指定幅に合わせてスケールされます。 |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber/) { get; set; } | 開始ページ番号の値を取得または設定します。この値から他のページが番号付けされます。 |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | スタンプ内のテキストの配置です。 |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | スタンプのテキストプロパティを取得します。詳細は [`TextState`](../textstamp/textstate/) を参照してください。 |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | スタンプの上余白を取得または設定します。 |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | テキスト配置の座標原点を定義します。TreatYIndentAsBaseLine = true（Draw = true のデフォルト）の場合、YIndent の値はテキストのベースラインとして扱われます。TreatYIndentAsBaseLine = false（Draw = false のデフォルト）の場合、YIndent の値はテキストの底部（ディセントライン）として扱われます。 |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | ページ上のスタンプとして使用される文字列値を取得または設定します。 |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | ページ上のスタンプの垂直位置揃えを取得または設定します。 |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | ページ上のスタンプの希望幅です。 |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | テキストレンダリングのワードラップモードを取得または設定します。 |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | 左端から開始するスタンプの水平座標です。 |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | 下端から開始するスタンプの垂直座標です。 |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | スタンプのズーム係数です。スタンプの拡大縮小を可能にします。ZoomX と ZoomY のペアのプロパティは各軸ごとにズーム係数を個別に設定できることに注意してください。このプロパティを設定すると ZoomX と ZoomY の両方のプロパティが変更されます。ZoomX と ZoomY が異なる場合、Zoom プロパティは ZoomX の値を返します。 |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | スタンプの水平ズーム係数です。スタンプを水平に拡大縮小できます。 |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | スタンプの垂直ズーム係数です。スタンプを垂直に拡大縮小できます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | スタンプ ID を返します。 |
| override [Put](../../aspose.pdf/pagenumberstamp/put/)(Page) | ページ番号を追加します。 |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | スタンプ ID を設定します。 |

### 関連項目

* class [TextStamp](../textstamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


