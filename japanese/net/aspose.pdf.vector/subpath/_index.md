---
title: "クラス SubPath"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Vector.SubPath クラス。ページ上のベクターグラフィックオブジェクトを表します。基本的にベクターグラフィックオブジェクトは 2 つの SubPath グループで表現されます。そのうちの一つは線と曲線の集合で表され、もう一つは矩形として提示され、時々混同されることがあります。通常、色の付いた矩形領域ですが、非常に多くの場合この矩形はページの先頭に配置され、ページ全体の白い領域を定義します。そのため SubPath を取得しますが、視覚的にはページ上のテキストしか見えません。"
type: docs
weight: 11410
url: /ja/net/aspose.pdf.vector/subpath/
---
## SubPath class

ページ上のベクターグラフィックオブジェクトを表します。基本的に、ベクターグラフィックオブジェクトは 2 つの SubPath グループで表現されます。そのうちの一つは線と曲線の集合で表され、もう一つは矩形として表され、時々混同されることがあります。通常は色を持つ矩形領域ですが、この矩形はページの先頭に配置され、ページ全体の白い領域を定義することが多いです。そのため SubPath は取得できますが、視覚的にはページ上のテキストしか見えません。

```csharp
public sealed class SubPath : GraphicElement
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | グラフィック要素のマトリックスを取得します。マトリックスは要素が作成されたときに設定され、SetPosition() が呼び出されると変更されます。 |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | 要素を表すオペレーターのコレクションを取得します。 |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | 要素が配置されている現在の [`XFormPlacement`](../xformplacement/) を取得します。 |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | 現在の座標空間における位置を取得または設定します。[`Parent`](../graphicelement/parent/) が null でない場合、要素は xForm 座標空間を持ちます。 |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | グラフィック要素が抽出されるページを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | 現在の要素をページに追加します。多数の要素を追加する場合は、[`AddGraphics`](../../aspose.pdf/page/addgraphics/) を使用した方が良いです。 |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | [`GraphicElement`](../graphicelement/) クラスが使用するすべてのリソースを解放します。 |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | 現在の要素をページから削除します。多数の要素を削除する場合は、[`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/) を使用した方が良いです。 |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | 要素を単一の SVG 画像に変換します。 |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | 要素を単一の SVG 画像ファイルに変換します。 |

### 関連項目

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


