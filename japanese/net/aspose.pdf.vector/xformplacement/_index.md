---
title: Class XFormPlacement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.XFormPlacement クラス。XForm の配置を表します。XForm がページに 1 回以上表示される場合、この XForm に関連付けられたすべての XformPlacements は共通のグラフィック要素を持ちますが、異なるグラフィック状態を持ちます。
type: docs
weight: 11260
url: /ja/net/aspose.pdf.vector/xformplacement/
---
## XFormPlacement クラス

XForm の配置を表します。XForm がページに 1 回以上表示される場合、この XForm に関連付けられたすべての XformPlacements は共通のグラフィック要素を持ちますが、異なるグラフィック状態を持ちます。

```csharp
public sealed class XFormPlacement : GraphicElement
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | この XForm 内のグラフィック要素を取得します。 |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | グラフィック要素の行列を取得します。行列は要素が作成されるときに設定されます。SetPosition() が呼び出されると変更されます。 |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | XForm の名前を取得します。 |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | 要素を表す演算子のコレクションを取得します。 |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | 要素が存在する現在の `XFormPlacement` を取得します。 |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | グラフィック要素が抽出されるページを取得します。 |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | この XFormPlacement に関連付けられた XForm を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | 現在の要素をページに追加します。追加する要素が多い場合は、[`AddGraphics`](../../aspose.pdf/page/addgraphics/) を使用する方が良いです。 |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | [`GraphicElement`](../graphicelement/) クラスによって使用されるすべてのリソースを解放します。 |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | 現在の要素をページから削除します。削除する要素が多い場合は、[`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/) を使用する方が良いです。 |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | 要素を単一の SVG 画像に変換します。 |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | 要素を単一の SVG 画像ファイルに変換します。 |

### 参照

* クラス [GraphicElement](../graphicelement/)
* 名前空間 [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* アセンブリ [Aspose.PDF](../../)