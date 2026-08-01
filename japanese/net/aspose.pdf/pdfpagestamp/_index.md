---
title: "クラス PdfPageStamp"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.PdfPageStamp クラス。PDF page をスタンプとして使用するスタンプを表すクラスです。"
type: docs
weight: 8560
url: /ja/net/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp class

PDF Page をスタンプとして使用するスタンプを表すクラスです。

```csharp
public sealed class PdfPageStamp : Stamp
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfPageStamp](pdfpagestamp/#constructor)(Page) | PdfPageStamp のコンストラクタ。 |
| [PdfPageStamp](pdfpagestamp/#constructor_1)(Stream, int) | ストリームから取得した document の指定された page を使用して Pdf page スタンプを作成します。 |
| [PdfPageStamp](pdfpagestamp/#constructor_2)(string, int) | 指定されたファイル内の document の指定された page を使用して Pdf page スタンプを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | コンテンツが背景としてスタンプされているかを示す bool 値を設定または取得します。値が true の場合、スタンプコンテンツは下部に配置されます。デフォルトでは、値は false で、スタンプコンテンツは上部に配置されます。 |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | スタンプの下余白を取得または設定します。 |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | page 上のスタンプの希望高さ。 |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | page 上のスタンプの水平配置を取得または設定します。 |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | スタンプの左余白を取得または設定します。 |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | スタンプの不透明度を示す値を取得または設定します。値は 0.0 から 1.0 の範囲です。デフォルトでは値は 1.0 です。 |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | スタンプの輪郭の不透明度を示す値を取得または設定します。値は 0.0 から 1.0 の範囲です。デフォルトでは値は 1.0 です。 |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | スタンプの輪郭幅の値を取得または設定します。デフォルトでは値は 1.0 です。 |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage/) { get; set; } | スタンプとして使用される page を取得または設定します。 |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | スタンプの右余白を取得または設定します。 |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | スタンプコンテンツの回転を[`Rotation`](../rotation/) の値に従って設定または取得します。注: このプロパティは 90 度の倍数 (0, 90, 180, 270 度) の角度を設定するためのものです。任意の角度を設定するには RotateAngle プロパティを使用します。ArbitraryAngle で設定された角度が 90 の倍数でない場合、Rotate プロパティは Rotation.None を返します。 |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | スタンプの回転角度を度単位で取得または設定します。このプロパティは任意の回転角度を設定できます。 |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | スタンプの上余白を取得または設定します。 |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | ページ上のスタンプの垂直位置揃えを取得または設定します。 |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | ページ上のスタンプの希望幅です。 |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | 左端から開始するスタンプの水平座標です。 |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | 下端から開始するスタンプの垂直座標です。 |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | スタンプのズーム係数です。スタンプの拡大縮小を可能にします。ZoomX と ZoomY のペアのプロパティは各軸ごとにズーム係数を個別に設定できることに注意してください。このプロパティを設定すると ZoomX と ZoomY の両方のプロパティが変更されます。ZoomX と ZoomY が異なる場合、Zoom プロパティは ZoomX の値を返します。 |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | スタンプの水平ズーム係数です。スタンプを水平に拡大縮小できます。 |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | スタンプの垂直ズーム係数です。スタンプを垂直に拡大縮小できます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | スタンプ ID を返します。 |
| override [Put](../../aspose.pdf/pdfpagestamp/put/)(Page) | 指定されたページにスタンプを配置します。 |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | スタンプ ID を設定します。 |

### 関連項目

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


