---
title: Class TextStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TextStamp クラス。テキストスタンプを表します
type: docs
weight: 11080
url: /ja/net/aspose.pdf/textstamp/
---
## TextStamp クラス

テキストスタンプを表します。

```csharp
public class TextStamp : Stamp
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextStamp](textstamp/#constructor)(FormattedText) | formattedText オブジェクトを使用して `TextStamp` クラスの新しいインスタンスを初期化します |
| [TextStamp](textstamp/#constructor_1)(string) | `TextStamp` クラスの新しいインスタンスを初期化します。 |
| [TextStamp](textstamp/#constructor_2)(string, TextState) | `TextStamp` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | フォントサイズの精度を自動調整します。デフォルト値: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | 有効にすると、フォントサイズはサイズのスタンプ矩形に合わせて自動的に調整されます: [`Width`](./width/) と [`Height`](./height/)。デフォルトの幅と高さはページの矩形から導出されます。 |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | コンテンツが背景としてスタンプされていることを示す bool 値を設定または取得します。値が true の場合、スタンプコンテンツは底に配置されます。デフォルトでは、値は false で、スタンプコンテンツは上に配置されます。 |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | スタンプの下余白を取得または設定します。 |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | このプロパティは、ページ上にスタンプがどのように描画されるかを決定します。Draw = true の場合、スタンプはグラフィックオペレーターとして描画され、draw = false の場合、スタンプはテキストとして描画されます。 |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | スタンプが配置された後の実際のフォントサイズです。（'AutoAdjustFontSizeToFitStampRectangle' オプションが有効な場合、コンストラクタを通じて提供された初期フォントサイズと異なる場合があります。） |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | ページ上のスタンプの希望の高さです。 |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | ページ上のスタンプの水平揃えを取得または設定します。 |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | テキストの整列を定義します。このプロパティが true に設定されている場合、テキストの左端と右端が揃えられます。デフォルト値: false。 |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | スタンプの左余白を取得または設定します。 |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | WordWrap オプションの最大行幅です。 |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | フォントが要求された文字を含まない場合の動作を定義するモードを取得または設定します。 |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | スタンプの不透明度を示す値を取得または設定します。値は 0.0 から 1.0 までです。デフォルトでは値は 1.0 です。 |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | スタンプのアウトライン不透明度を示す値を取得または設定します。値は 0.0 から 1.0 までです。デフォルトでは値は 1.0 です。 |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | スタンプのアウトライン幅の値を取得または設定します。デフォルトでは値は 1.0 です。 |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | ユーザーフォントが必要な文字を含まない場合に置き換えに使用されるフォントを取得または設定します。 |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | スタンプの右余白を取得または設定します。 |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | スタンプコンテンツの回転を [`Rotation`](../rotation/) 値に従って設定または取得します。注意。このプロパティは、90度の倍数（0、90、180、270度）の角度を設定するためのものです。任意の角度を設定するには RotateAngle プロパティを使用します。ArbitraryAngle で設定された角度が 90 の倍数でない場合、Rotate プロパティは Rotation.None を返します。 |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | スタンプの回転角度を度単位で取得または設定します。このプロパティは任意の回転角度を設定することを可能にします。 |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | テキストのスケーリングを定義します。このプロパティが true に設定され、幅の値が指定されている場合、テキストは指定された幅に合わせてスケーリングされます。 |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | スタンプ内のテキストの揃え方です。 |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | スタンプのテキストプロパティを取得します。詳細については [`TextState`](./textstate/) を参照してください。 |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | スタンプの上余白を取得または設定します。 |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | テキストを配置するための座標原点を定義します。TreatYIndentAsBaseLine = true の場合（Draw = true のときのデフォルト）、YIndent 値はテキストのベースラインとして扱われます。TreatYIndentAsBaseLine = false の場合（Draw = false のときのデフォルト）、YIndent 値はテキストの底（降下線）として扱われます。 |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | ページ上のスタンプとして使用される文字列値を取得または設定します。 |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | ページ上のスタンプの垂直揃えを取得または設定します。 |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | ページ上のスタンプの希望の幅です。 |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | テキストレンダリングのワードラップモードを取得または設定します。 |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | 左から始まる水平スタンプ座標です。 |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | 下から始まる垂直スタンプ座標です。 |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | スタンプのズーム係数です。スタンプをスケーリングすることができます。このプロパティの設定は、ZoomX と ZoomY の両方のプロパティを変更します。ZoomX と ZoomY が異なる場合、Zoom プロパティは ZoomX の値を返します。 |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | スタンプの水平方向のズーム係数です。スタンプを水平方向にスケーリングすることができます。 |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | スタンプの垂直方向のズーム係数です。スタンプを垂直方向にスケーリングすることができます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | スタンプ ID を返します。 |
| override [Put](../../aspose.pdf/textstamp/put/)(Page) | ページにテキストスタンプを追加します。 |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | スタンプ ID を設定します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| enum [NoCharacterAction](../../aspose.pdf/textstamp.nocharacteraction) | フォントが必要な文字を含まない場合に実行するアクション。 |

### 参照

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)