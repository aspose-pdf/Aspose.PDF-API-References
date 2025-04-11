---
title: Class PageNumberStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PageNumberStamp クラス。ページ番号スタンプを表し、ページに番号を付けるために使用されます。
type: docs
weight: 8230
url: /ja/net/aspose.pdf/pagenumberstamp/
---
## PageNumberStamp クラス

ページ番号スタンプを表し、ページに番号を付けるために使用されます。

```csharp
public sealed class PageNumberStamp : TextStamp
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PageNumberStamp](pagenumberstamp/#constructor)() | `PageNumberStamp` クラスの新しいインスタンスを初期化します。フォーマットは "#" に設定されます。 |
| [PageNumberStamp](pagenumberstamp/#constructor_1)(FormattedText) | フォーマットされたテキストによって PageNumberStamp を作成します。 |
| [PageNumberStamp](pagenumberstamp/#constructor_2)(string) | `PageNumberStamp` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | フォントサイズの精度を自動的に調整します。デフォルト値: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | 有効にすると、フォントサイズはサイズ [`Width`](../textstamp/width/) と [`Height`](../textstamp/height/) のスタンプ矩形に合わせて自動的に調整されます。デフォルトの幅と高さはページの矩形から導出されます。 |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | コンテンツが背景としてスタンプされていることを示す bool 値を設定または取得します。値が true の場合、スタンプコンテンツは下に配置されます。デフォルトでは、値は false で、スタンプコンテンツは上に配置されます。 |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | スタンプの下余白を取得または設定します。 |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | このプロパティは、ページ上でスタンプがどのように描画されるかを決定します。Draw = true の場合、スタンプはグラフィックオペレーターとして描画され、draw = false の場合、スタンプはテキストとして描画されます。 |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | スタンプが配置された後の実際のフォントサイズです。（'AutoAdjustFontSizeToFitStampRectangle' オプションが有効な場合、コンストラクタを通じて提供された初期フォントサイズと異なる場合があります。） |
| [Format](../../aspose.pdf/pagenumberstamp/format/) { get; set; } | ページ番号をスタンプするための文字列値です。値には、スタンプ処理中にページ番号に置き換えられる文字 '#' を含める必要があります。 |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | ページ上のスタンプの希望の高さです。 |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | ページ上のスタンプの水平揃えを取得または設定します。 |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | テキストの整列を定義します。このプロパティが true に設定されている場合、テキストの左端と右端が揃えられます。デフォルト値: false。 |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | スタンプの左余白を取得または設定します。 |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | WordWrap オプションの最大行幅です。 |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | フォントが要求された文字を含まない場合の動作を定義するモードを取得または設定します。 |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle/) { get; set; } | このスタンプで使用される番号付けスタイルです。 |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | スタンプの不透明度を示す値を取得または設定します。値は 0.0 から 1.0 までです。デフォルトでは、値は 1.0 です。 |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | スタンプのアウトライン不透明度を示す値を取得または設定します。値は 0.0 から 1.0 までです。デフォルトでは、値は 1.0 です。 |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | スタンプのアウトライン幅の値を取得または設定します。デフォルトでは、値は 1.0 です。 |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | ユーザーフォントが必要な文字を含まない場合に置き換えに使用されるフォントを取得または設定します。 |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | スタンプの右余白を取得または設定します。 |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | スタンプコンテンツの回転を [`Rotation`](../rotation/) 値に従って設定または取得します。注意。このプロパティは、90度の倍数（0、90、180、270度）の角度を設定するためのものです。任意の角度を設定するには RotateAngle プロパティを使用します。ArbitraryAngle で設定された角度が90の倍数でない場合、Rotate プロパティは Rotation.None を返します。 |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | スタンプの回転角度を度単位で取得または設定します。このプロパティは、任意の回転角度を設定することを可能にします。 |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | テキストのスケーリングを定義します。このプロパティが true に設定され、Width 値が指定されている場合、テキストは指定された幅に合わせてスケーリングされます。 |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber/) { get; set; } | 開始ページの番号の値を取得または設定します。他のページはこの値から番号が付けられます。 |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | スタンプ内のテキストの揃え方です。 |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | スタンプのテキストプロパティを取得します。詳細については [`TextState`](../textstamp/textstate/) を参照してください。 |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | スタンプの上余白を取得または設定します。 |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | テキストを配置するための座標原点を定義します。TreatYIndentAsBaseLine = true の場合（Draw = true のときのデフォルト）、YIndent 値はテキストのベースラインとして扱われます。TreatYIndentAsBaseLine = false の場合（Draw = false のときのデフォルト）、YIndent 値はテキストの下部（降下線）として扱われます。 |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | ページ上のスタンプとして使用される文字列値を取得または設定します。 |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | ページ上のスタンプの垂直揃えを取得または設定します。 |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | ページ上のスタンプの希望の幅です。 |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | テキストレンダリングのワードラップモードを取得または設定します。 |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | 左から始まる水平スタンプ座標です。 |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | 下から始まる垂直スタンプ座標です。 |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | スタンプのズーム係数です。スタンプをスケーリングすることを可能にします。このプロパティの設定は、ZoomX と ZoomY の両方のプロパティを変更します。ZoomX と ZoomY が異なる場合、Zoom プロパティは ZoomX の値を返します。 |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | スタンプの水平ズーム係数です。スタンプを水平方向にスケーリングすることを可能にします。 |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | スタンプの垂直ズーム係数です。スタンプを垂直方向にスケーリングすることを可能にします。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | スタンプ ID を返します。 |
| override [Put](../../aspose.pdf/pagenumberstamp/put/)(Page) | ページ番号を追加します。 |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | スタンプ ID を設定します。 |

### 参照

* クラス [TextStamp](../textstamp/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)