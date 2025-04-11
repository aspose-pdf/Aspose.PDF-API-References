---
title: Class SvgExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.SvgExtractionOptions クラス。PDF ドキュメントページからベクター グラフィックスを抽出するためのオプション クラスを表します。
type: docs
weight: 11240
url: /ja/net/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions クラス

PDF ドキュメントページからベクター グラフィックスを抽出するためのオプション クラスを表します。

```csharp
public class SvgExtractionOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SvgExtractionOptions](svgextractionoptions/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | サブパスを画像に自動的にグループ化するオプションを取得および設定します。このオプションは [`GroupStrength`](./groupstrength/) オプションを除外します。 |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | PDF ドキュメントからすべてのサブパスを別々の SVG 画像に抽出するオプションを取得および設定します。 |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | SVG 抽出のための抽出エリアを定義するバウンディング矩形を取得および設定します。 |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | サブパスを画像にグループ化する強度のオプションを取得および設定します。サブパスのグループ化の度合いを構成できます。値の範囲は 0 から 1 です。値が 0 の場合は [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/) オプションが有効になります。値が 1 の場合は、ページ上のすべてのベクターパスの単一画像が作成されます。このオプションは [`AutoGrouping`](./autogrouping/) が false の場合に効果があります。デフォルト値は `0.8` です。 |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | 結果の SVG で使用される最小ストローク幅を取得または設定します。PDF がより細いストローク幅を使用している場合は、この幅に置き換えられます。デフォルト値は 0.5 です。 |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | サブパスが [`ExtractionAreaBound`](./extractionareabound/) で指定された矩形内にあるかどうかを厳密にチェックするオプションを取得および設定します。false に設定すると、[`ExtractionAreaBound`](./extractionareabound/) に完全に含まれないサブパスが抽出されます。デフォルト値は `True` です。 |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | ページ上で見つかった XForm を展開するかどうかを決定するフラグを取得および設定します。XForm 要素は異なる SVG ファイルに含まれる場合があります。ページコンテンツからの Do ステートメントによってレンダリングされた XForms のみが展開されます。ネストされた XForms は展開されません。 |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | 指定された述語に対応する XForm のみを展開するオプションを取得および設定します。 |

### 参照

* 名前空間 [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* アセンブリ [Aspose.PDF](../../)