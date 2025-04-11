---
title: Class SubPath
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.SubPath クラス。ページ上のベクターグラフィックスオブジェクトを表します。基本的に、ベクターグラフィックスオブジェクトは二つのグループの SubPaths で表されます。一つは線と曲線のセットで表されます。もう一つは長方形として表され、時には混同されることがあります。通常、それは色を持つ長方形の領域ですが、非常に多くの場合、この長方形はページの最初に配置され、ページ全体の空間を白で定義します。したがって、SubPath を取得しますが、視覚的にはページ上のテキストのみが見えます。
type: docs
weight: 11220
url: /ja/net/aspose.pdf.vector/subpath/
---
## SubPath クラス

ページ上のベクターグラフィックスオブジェクトを表します。基本的に、ベクターグラフィックスオブジェクトは二つのグループの SubPaths で表されます。一つは線と曲線のセットで表されます。もう一つは長方形として表され、時には混同されることがあります。通常、それは色を持つ長方形の領域ですが、非常に多くの場合、この長方形はページの最初に配置され、ページ全体の空間を白で定義します。したがって、SubPath を取得しますが、視覚的にはページ上のテキストのみが見えます。

```csharp
public sealed class SubPath : GraphicElement
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | グラフィック要素の行列を取得します。要素が作成されるときに行列が設定されます。SetPosition() が呼び出されると変更されます。 |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | 要素を表すオペレーターのコレクションを取得します。 |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | 要素が存在する現在の [`XFormPlacement`](../xformplacement/) を取得します。 |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | 現在の座標空間における位置を取得または設定します。もし [`Parent`](../graphicelement/parent/) が !:null でない場合、要素は xForm 座標空間を持ちます。 |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | グラフィック要素が抽出されたページを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | 現在の要素をページに追加します。追加する要素が多い場合は、[`AddGraphics`](../../aspose.pdf/page/addgraphics/) を使用する方が良いです。 |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | [`GraphicElement`](../graphicelement/) クラスによって使用されるすべてのリソースを解放します。 |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | 現在の要素をページから削除します。削除する要素が多い場合は、[`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/) を使用する方が良いです。 |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | 要素を単一の SVG 画像に変換します。 |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | 要素を単一の SVG 画像ファイルに変換します。 |

### 参照

* クラス [GraphicElement](../graphicelement/)
* 名前空間 [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* アセンブリ [Aspose.PDF](../../)