---
title: Class AbsorbedCell
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.AbsorbedCell クラス。ページ上に存在するテーブルのセルを表します
type: docs
weight: 10410
url: /ja/net/aspose.pdf.text/absorbedcell/
---
## AbsorbedCell クラス

ページ上に存在するテーブルのセルを表します

```csharp
public class AbsorbedCell : IComparable<AbsorbedCell>, ITableElement
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BorderInfo](../../aspose.pdf.text/absorbedcell/borderinfo/) { get; } | FlowEngine.TableAbsorber.UseFlowEngine プロパティが true に設定されているとき、セルの境界情報を返します。 |
| [ColSpan](../../aspose.pdf.text/absorbedcell/colspan/) { get; } | TableAbsorber.UseFlowEngine プロパティが true に設定されているとき、セルが跨ぐべき列の数を返します。 |
| [Rectangle](../../aspose.pdf.text/absorbedcell/rectangle/) { get; } | ページ上のセルの位置を説明する矩形を取得します |
| [TextFragments](../../aspose.pdf.text/absorbedcell/textfragments/) { get; } | セルに含まれるテキストを説明する [`TextFragment`](../textfragment/) オブジェクトのコレクションを取得します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CompareTo](../../aspose.pdf.text/absorbedcell/compareto/)(AbsorbedCell) | 現在の AbsorbedCell オブジェクトを別の AbsorbedCell オブジェクトと比較し、現在のオブジェクトが他のオブジェクトより前、後、または同じ位置にあるかを示す整数を返します。 |

### 参照

* インターフェース [ITableElement](../itableelement/)
* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)