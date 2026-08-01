---
title: "クラス SvgExtractionOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Vector.SvgExtractionOptions クラス。PDF ドキュメントページからベクターグラフィックを抽出するためのオプションクラスを表します。"
type: docs
weight: 11430
url: /ja/net/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions class

PDF ドキュメントページからベクターグラフィックを抽出するためのオプションクラスを表します。

```csharp
public class SvgExtractionOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SvgExtractionOptions](svgextractionoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | サブパスを自動的に画像にグループ化するオプションを取得または設定します。このオプションは [`GroupStrength`](./groupstrength/) オプションを除外します。 |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | PDF ドキュメントからすべてのサブパスを個別の SVG 画像に抽出するオプションを取得または設定します。 |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | SVG 抽出の抽出領域を定義するバウンディング矩形を取得または設定します。 |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | サブパスを画像にグループ化する強度のオプションを取得または設定します。サブパスのグループ化の度合いを構成できます。値の範囲は 0 から 1 です。0 の値は [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/) オプションが有効であることに対応し、1 の値はページ上のすべてのベクターパスを単一の画像にします。このオプションは [`AutoGrouping`](./autogrouping/) が false のときに効果があります。デフォルト値は `0.8` です。 |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | 結果の SVG で使用される最小ストローク幅を取得または設定します。PDF がそれより細いストローク幅を使用している場合、この幅に置き換えられます。デフォルト値は 0.5 です。 |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | `ExtractionAreaBound`（[`ExtractionAreaBound`](./extractionareabound/)）で指定された矩形内にサブパスが完全に収まっているかを厳密にチェックするかどうかのオプションを取得または設定します。false に設定すると、[`ExtractionAreaBound`](./extractionareabound/) に完全に含まれていないサブパスも抽出されます。デフォルト値は `True` です。 |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | ページ上で見つかった XFrom を展開するかどうかを決定するフラグを取得または設定します。XFrom 要素は別々の SVG ファイルに分割される可能性があります。ページコンテンツの Do ステートメントでレンダリングされた XForm のみが展開され、ネストされた XForm は展開されません。 |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | 指定された述語に対応する XForm のみを展開するオプションを取得または設定します。 |

### 関連項目

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


