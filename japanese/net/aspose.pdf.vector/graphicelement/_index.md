---
title: "クラス GraphicElement"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Vector.GraphicElement クラス。ページ上のグラフィックオブジェクトの基底クラスを表します。"
type: docs
weight: 11370
url: /ja/net/aspose.pdf.vector/graphicelement/
---
## GraphicElement class

ページ上のグラフィックオブジェクトの基底クラスを表します。

```csharp
public abstract class GraphicElement : IDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | グラフィック要素のマトリックスを取得します。マトリックスは要素が作成されたときに設定され、SetPosition() が呼び出されると変更されます。 |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | 要素を表すオペレーターのコレクションを取得します。 |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | 要素が配置されている現在の [`XFormPlacement`](../xformplacement/) を取得します。 |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | 現在の座標空間で位置を取得または設定します。[`Parent`](./parent/) が !:null でない場合、要素は xForm 座標空間を持ちます。 |
| abstract [Rectangle](../../aspose.pdf.vector/graphicelement/rectangle/) { get; } | `GraphicElement` のバウンディング Rectangle を取得します。 |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | グラフィック要素が抽出されるページを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | 現在の要素をページに追加します。多数の要素を追加する場合は、[`AddGraphics`](../../aspose.pdf/page/addgraphics/) を使用した方が良いです。 |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | `GraphicElement` クラスで使用されるすべてのリソースを解放します。 |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | 現在の要素をページから削除します。多数の要素を削除する場合は、[`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/) を使用した方が良いです。 |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg)() | 要素を単一の SVG 画像に変換します。 |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg_1)(string) | 要素を単一の SVG 画像ファイルに変換します。 |

### 関連項目

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


