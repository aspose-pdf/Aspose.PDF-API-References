---
title: Class PdfPageStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfPageStamp クラス。クラスは PDF ページをスタンプとして使用するスタンプを表します
type: docs
weight: 8420
url: /ja/net/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp クラス

クラスは PDF ページをスタンプとして使用するスタンプを表します。

```csharp
public sealed class PdfPageStamp : Stamp
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfPageStamp](pdfpagestamp/#constructor)(Page) | PdfPageStamp のコンストラクタ。 |
| [PdfPageStamp](pdfpagestamp/#constructor_1)(Stream, int) | ストリームからドキュメント内の指定されたページの Pdf ページスタンプを作成します。 |
| [PdfPageStamp](pdfpagestamp/#constructor_2)(string, int) | 指定されたファイル内のドキュメントの指定されたページから Pdf ページスタンプを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | コンテンツが背景としてスタンプされていることを示す bool 値を設定または取得します。値が true の場合、スタンプコンテンツは下に配置されます。デフォルトでは、値は false で、スタンプコンテンツは上に配置されます。 |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | スタンプの下余白を取得または設定します。 |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | ページ上のスタンプの希望の高さ。 |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | ページ上のスタンプの水平配置を取得または設定します。 |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | スタンプの左余白を取得または設定します。 |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | スタンプの不透明度を示す値を取得または設定します。値は 0.0 から 1.0 です。デフォルトでは値は 1.0 です。 |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | スタンプのアウトライン不透明度を示す値を取得または設定します。値は 0.0 から 1.0 です。デフォルトでは値は 1.0 です。 |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | スタンプのアウトライン幅の値を取得または設定します。デフォルトでは値は 1.0 です。 |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage/) { get; set; } | スタンプとして使用されるページを取得または設定します。 |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | スタンプの右余白を取得または設定します。 |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | スタンプコンテンツの回転を [`Rotation`](../rotation/) 値に従って設定または取得します。注意。このプロパティは 90 度の倍数（0、90、180、270 度）の角度を設定するためのものです。任意の角度を設定するには RotateAngle プロパティを使用します。ArbitraryAngle で設定された角度が 90 の倍数でない場合、Rotate プロパティは Rotation.None を返します。 |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | スタンプの回転角度を度単位で取得または設定します。このプロパティは任意の回転角度を設定することを可能にします。 |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | スタンプの上余白を取得または設定します。 |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | ページ上のスタンプの垂直配置を取得または設定します。 |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | ページ上のスタンプの希望の幅。 |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | 左から始まる水平スタンプ座標。 |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | 下から始まる垂直スタンプ座標。 |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | スタンプのズーム係数。スタンプをスケールすることを可能にします。このプロパティの設定は、ZoomX と ZoomY の両方のプロパティを変更します。ZoomX と ZoomY が異なる場合、Zoom プロパティは ZoomX の値を返します。 |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | スタンプの水平ズーム係数。スタンプを水平方向にスケールすることを可能にします。 |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | スタンプの垂直ズーム係数。スタンプを垂直方向にスケールすることを可能にします。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | スタンプ ID を返します。 |
| override [Put](../../aspose.pdf/pdfpagestamp/put/)(Page) | 指定されたページにスタンプを置きます。 |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | スタンプ ID を設定します。 |

### 参照

* クラス [Stamp](../stamp/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)