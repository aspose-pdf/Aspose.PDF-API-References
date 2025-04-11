---
title: TextFragmentState.CoordinateOrigin
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentState プロパティ。テキストの CoordinateOrigin を取得または設定します。CoordinateOrigin が Descender の場合、テキストの Y 座標はフォントの最も低い点に対応します。CoordinateOrigin が BaseLine の場合、テキストの Y 座標はフォントのベースラインに対応します。デフォルト値は Descender です。フォントの Descent 値が大きすぎると、テキストが他のフォントよりも高くレンダリングされることがあります。この場合、より良いテキストレンダリングのために CoordinateOrigin BaseLine を選択できます。
type: docs
weight: 40
url: /ja/net/aspose.pdf.text/textfragmentstate/coordinateorigin/
---
## TextFragmentState.CoordinateOrigin プロパティ

テキストの CoordinateOrigin を取得または設定します。CoordinateOrigin が Descender の場合、テキストの Y 座標はフォントの最も低い点に対応します。CoordinateOrigin が BaseLine の場合、テキストの Y 座標はフォントのベースラインに対応します。デフォルト値は Descender です。フォントの Descent 値が大きすぎると、テキストが他のフォントよりも高くレンダリングされることがあります。この場合、CoordinateOrigin BaseLine を選択することで、より良いテキストレンダリングが可能です。

```csharp
public override CoordinateOrigin CoordinateOrigin { get; set; }
```

### 関連項目

* enum [CoordinateOrigin](../../coordinateorigin/)
* class [TextFragmentState](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)