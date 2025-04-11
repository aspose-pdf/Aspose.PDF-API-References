---
title: Class ImageStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImageStamp クラス。グラフィックスタンプを表します
type: docs
weight: 5930
url: /ja/net/aspose.pdf/imagestamp/
---
## ImageStamp クラス

グラフィックスタンプを表します。

```csharp
public sealed class ImageStamp : Stamp
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ImageStamp](imagestamp/#constructor)(Stream) | `ImageStamp` クラスの新しいインスタンスを初期化します。 |
| [ImageStamp](imagestamp/#constructor_1)(string) | 指定されたファイルの画像によって画像スタンプを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeText](../../aspose.pdf/imagestamp/alternativetext/) { get; set; } | 画像スタンプの代替テキストを取得または設定します。 |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | コンテンツが背景としてスタンプされることを示すブール値を設定または取得します。値が true の場合、スタンプコンテンツは下に配置されます。デフォルトでは、値は false で、スタンプコンテンツは上に配置されます。 |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | スタンプの下余白を取得または設定します。 |
| override [Height](../../aspose.pdf/imagestamp/height/) { get; set; } | 画像の高さを取得または設定します。この画像を設定することで、画像を垂直にスケーリングできます。 |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | ページ上のスタンプの水平配置を取得または設定します。 |
| [Image](../../aspose.pdf/imagestamp/image/) { get; } | スタンプに使用される画像ストリームを取得します。 |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | スタンプの左余白を取得または設定します。 |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | スタンプの不透明度を示す値を取得または設定します。値は 0.0 から 1.0 までです。デフォルトでは、値は 1.0 です。 |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | スタンプのアウトライン不透明度を示す値を取得または設定します。値は 0.0 から 1.0 までです。デフォルトでは、値は 1.0 です。 |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | スタンプのアウトライン幅の値を取得または設定します。デフォルトでは、値は 1.0 です。 |
| [Quality](../../aspose.pdf/imagestamp/quality/) { get; set; } | 画像スタンプの品質をパーセントで取得または設定します。有効な値は 0..100% です。 |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | スタンプの右余白を取得または設定します。 |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | スタンプコンテンツの回転を [`Rotation`](../rotation/) 値に従って設定または取得します。注意。このプロパティは 90 度の倍数（0、90、180、270 度）の角度を設定するためのものです。任意の角度を設定するには RotateAngle プロパティを使用します。ArbitraryAngle で設定された角度が 90 の倍数でない場合、Rotate プロパティは Rotation.None を返します。 |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | スタンプの回転角度を度単位で取得または設定します。このプロパティを使用すると、任意の回転角度を設定できます。 |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | スタンプの上余白を取得または設定します。 |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | ページ上のスタンプの垂直配置を取得または設定します。 |
| override [Width](../../aspose.pdf/imagestamp/width/) { get; set; } | 画像の幅を取得または設定します。このプロパティを設定することで、画像を水平方向にスケーリングできます。 |
| override [XIndent](../../aspose.pdf/imagestamp/xindent/) { get; set; } | 左から始まる水平スタンプ座標を取得および設定します。 |
| override [YIndent](../../aspose.pdf/imagestamp/yindent/) { get; set; } | 下から始まる垂直スタンプ座標を取得および設定します。 |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | スタンプのズーム係数。スタンプをスケーリングできます。このプロパティの設定は、ZoomX と ZoomY の両方のプロパティを変更します。ZoomX と ZoomY が異なる場合、Zoom プロパティは ZoomX の値を返します。 |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | スタンプの水平ズーム係数。スタンプを水平方向にスケーリングできます。 |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | スタンプの垂直ズーム係数。スタンプを垂直方向にスケーリングできます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | スタンプ ID を返します。 |
| override [Put](../../aspose.pdf/imagestamp/put/)(Page) | ページにグラフィックスタンプを追加します。 |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | スタンプ ID を設定します。 |

### 参照

* クラス [Stamp](../stamp/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)